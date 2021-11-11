# Ransac-Sift-Matching-Alignment
## Image alignment
We want to transform thefirst image to its location in the second image. This can be done using the
cv2.warpPerspective function before and the transformation matrix H obtained using RANSAC. Complete
the following code to do this. The code alternatingly displays the second image and the
transformed source object.
### input:
1- images of objects:
<p float="left" align="center">
  <img src="https://github.com/arashasg/Ransac-Sift-Matching-Alignment/blob/master/Images%20of%20Objects%20and%20the%20Scene/obj3.jpg"  width="250px" height="250px"/>
  <img src="https://github.com/arashasg/Ransac-Sift-Matching-Alignment/blob/master/Images%20of%20Objects%20and%20the%20Scene/obj4.jpg"  width="250px" height="250px"/>
  <img src="https://github.com/arashasg/Ransac-Sift-Matching-Alignment/blob/master/Images%20of%20Objects%20and%20the%20Scene/obj5.jpg"  width="250px" height="250px"/>
  <img src="https://github.com/arashasg/Ransac-Sift-Matching-Alignment/blob/master/Images%20of%20Objects%20and%20the%20Scene/obj8.jpg"  width="250px" height="250px"/>
  <img src="https://github.com/arashasg/Ransac-Sift-Matching-Alignment/blob/master/Images%20of%20Objects%20and%20the%20Scene/obj9.jpg"  width="250px" height="250px"/>
</p>
2- image of the scene:
<p float="left" align="center">
  <img src="https://github.com/arashasg/Ransac-Sift-Matching-Alignment/blob/master/Images%20of%20Objects%20and%20the%20Scene/scene.jpg"  width="350px" height="350px"/>
</p>

### Output:
<p float="left" align="center">
  <img src="https://github.com/arashasg/Ransac-Sift-Matching-Alignment/blob/master/Images%20of%20Objects%20and%20the%20Scene/OutPut.PNG"  width="700px" height="350px"/>
</p>