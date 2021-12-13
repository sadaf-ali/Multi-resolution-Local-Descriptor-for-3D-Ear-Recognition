# Multi-resolution-Local-Descriptor-for-3D-Ear-Recognition
Several approaches have shown promising results in human ear recognition. However, factors such as the pose, illumination, and scaling have an enormous impact on recognition performance. 3D models are insensitive to these factors and are found to be better at enhancing recognition performance with strong geometric information. Low cost 3D data acquisition has also boosted the research community in recent times to explore more about 3D object recognition. We present a local multi-resolution descriptor in this paper to recognize human ears in 3D. For each key-point in 3D ear, a local reference frame (LRF) is constructed. Using multi-radii, we find neighbors at each key-point and the neighbors obtained from each radius are projected to create a depth image using the LRF. Further, a descriptor is computed by employing neural network based auto-encoders and the local statistics of the depth images. The descriptor is used to locate the potential correspondence matching points in the probe and gallery images for a coarse arrangement, followed by a fine alignment to compute the registration error. The obtained registration error is used as the matching score. The proposed technique is assessed on UND-J2 dataset to demonstrate its effectiveness.



For Codes, kindly send an email to iit.sadaf@gmail.com

Reference/Citation:  I. I. Ganapathi, **Syed Sadaf Ali** and S. Prakash. Multi-resolution Local Descriptor for 3D Ear Recognition , In
Proc. of 18th Int. Conf. of the Biometrics Special Interest Group (BIOSIG 2019), Darmstadt, Germany.
