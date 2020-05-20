# Homography

Homography describes the projective geometry of two cameras and a world plane. 
In simple terms, homography maps images of points which lie on a world plane from one camera view to another.

Homography can be calculated using relative rotation and translation between two cameras.
But it is often the case that we don’t have the relative pose between two views 
(or to put in a different way we don’t always have two calibrated cameras) and 
still we are required to calculate the mapping between first image and second image for the planar points in the world.

This pdf will be helpful to understand math behind it https://cseweb.ucsd.edu/classes/wi07/cse252a/homography_estimation/homography_estimation.pdf
