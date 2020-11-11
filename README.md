# rigid_to_transformation
Topic:
Two dimensional rigid transformation
The 2D rigid transformation based on OpenCV can be extended to 3D structure to calculate R &amp; T (rotation and translation)

detailed description：
We are solving R, t: in the equation
B = R*A + t，
Where R, t are the transformations applied to dataset a to align them with dataset B as much as possible. The optimal rigid transformation matrix can be decomposed into the following steps:
1. Find the centroid of two datasets
2. Bring the two data sets to the origin and find the optimal rotation (matrix R)
3. Find the translation t

picture:
