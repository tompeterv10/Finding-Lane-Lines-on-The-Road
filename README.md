# Finding-Lane-Lines-on-The-Road

Details about the files in repository
----------------------------------------
1. The folders test_image_output and test_video_output contains the output images and videos respectively.
2. The original images and videos are provided in the test_images_Original and test_videos folder.
3. The code P1Image.ipynb and P1Video.ipynb are the respective files which is used to find lane lines on the image and video respectively.

Software Used
--------------
Python 3
Jupyter Notebook, OpenCV libraries etc

Overview
--------
First the image of lane lines read and converted to gray scale image. 
The kernel size for gaussian blur is selected as 5 and canny transform is applied which helps in finding the edges in an image.Then the region of interest is marked by selecting the coordinates by trial and error method.Then the lines are drawn by finding the slope of left and right lines and join the points which lie in the same slope using hough transform. Once the lines are drawn we superimpose the image on original image to display the lane lines on the road for each image.





