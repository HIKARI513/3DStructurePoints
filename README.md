# Unsupervised Learning of Intrinsic Structural Representation Points


## Description
Learning structures of 3D shapes is a fundamental problem in the field of computer graphics and geometry processing. We present a simple yet interpretable unsupervised method for learning a new structural representation in the form of 3D structure points. The 3D structure points produced by our method encode the shape structure intrinsically and exhibit semantic consistency across all the shape instances within the same category, which is a challenging goal not fully addressed by previous methods. Specifically, our method takes a 3D point cloud as input and encodes it as a set of local features. The local features are then passed through a novel point integration module to produce a set of 3D structure points. Chamfer distance is used as reconstruction loss to ensure the structure points lie close to the input point cloud. 
We evaluate the method with extensive experiments and show state-of-the-art accuracy on both semantic shape correspondence and segmentation label transfer tasks. Moreover, the PCA based shape embedding built upon consistent structure points demonstrates good performance in preserving the shape structures.


<div align="center">
<img src="https://github.com/NolenChen/3DStructurePoints/blob/master/figs/teaser.png" width="70%" height="70%"><br><br>
</div>
