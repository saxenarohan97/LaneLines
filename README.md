# LaneLines
An OpenCV pipeline for detecting lane lines in video streams

Check out the P1.ipynb file for the code.

I start off by using the Canny edge detection algorithm to detect edges. Then I use Hough transform to represent the images in parameter space, using which I detect lines in the region of interest. This is first tested on images, and then on videos.
