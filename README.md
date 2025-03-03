java c
Computer graphics
1.   A CCD camera chip of dimensions 10 x 10 mm, and having 2048 x 2048 elements, is focused on a square, flat area, located 0.5 m away. How many line pairs per mm will this camera be able to resolve? The camera is equipped with a 35-mm lens. (Hint: Model the imaging process with the focal length of the camera lens substituting for the focal length of the eye.) Draw a diagram to show how you model this question and write down the detailed steps of solving it.
2.   The following shows a perspective projection where the eye is at the origin, the viewing direction is the opposite of the z-axis, and the projection plane is z=-1.(1)   A point at (x,y,z) in the viewing frustum is projected on (x’,y’,z’). Give the formula to form. x’, y’, z’.
x’=  y’=  z’=  (2)   Give the 4*4 matrix that represents the projection.
3. Given an image of 2x2, enlarge it into a 5x5 one and fill in the new image with pixel values using
1) Nearest Neighbor Interpolation
2) Bilinear Interpolation
[Detailed steps must be given.]
7 
5 
3 
1 
1)

























2)

























4. Given an image of 9x9, reduce it into a 4x4 one and fill in the new image with pixel values using Fractional Linear Reduction. [Detailed steps must be given.]
1 1 
1 
1 
1 
1 
1 
1 
1 
2 
2 
2 
2 
2 
2 
2 
2 
2 
3 
3 
3 
3 
3 
3 
3 
3 
3 
6 
6 
6 
6 
6 
6 
6 
6 
6 
5 
5 
5 
5 
5 
5 
5 
5 
5 
4 
4 
4 
4 
4 
4 
4 
4 
4 
7 
7 
7 
7 
7 
7 
7 
7 
7 
8 
8 
8 
8 
8 
8 
8 
8 
8 
9 
9 
9 
9 
9 
9 
9 
9 
9 

















5. The following sub-problems about affine transformation is based on the following assumptions:
a. The output image employs the same coordinate system as the input image.
b. The dimensions of the output image are identical to those of the input image (pixels that fall outside the image boundaries are not displayed).
Please write the expression for (x', y'), the coordinates of (x, y)   after transformation, based on the given conditions; add the necessary auxiliary lines and labels to the provided image, and give a detailed derivation process.
Rotation
1.2

Translation

Shear (horizontal)

Shear (vertical)

6. Given a 3   × 3   image, use bilinear interpolation to enlarge it to a 4   × 6   image. [Calculate by hand. Detailed steps must be given.]
142 
87 
213 
56 
199 
34 
178 
22 
245 



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
