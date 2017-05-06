# Finding Lane Lines on the Road

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

Overview
---

Finding Lane Lines is the final project of the Lesson 2 of the [Udacity - Self-Driving Car NanoDegree](http://www.udacity.com/drive). The goal is the take an image from the car camera e.g.:

<img src="test_images/solidWhiteRight.jpg" width="480" />

and find lane lines on it using Python and OpenCV library:

<img src="test_images_output/solidWhiteRight.jpg" width="480" />

More info at [writeup.md](writeup.md).

## Files

* `README.md` - this file
* `P1.ipynb` - IPython notebook with code which implements a pipeline to find lane lines
* `test_images/` - directory with test images
* `test_images_output/` - directory with processed test images
* `test_videos/` - directory with test videos
* `test_videos_output/` - directory with processed test videos
* `writeup.md` - brief report with pipeline used to find lane lines 
* `writeup-images/` - images to describe pipeline

## How to Run the Code

Make sure you have installed `conda` or `docker` as described at [CarND-Term1-Starter-Kit](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md)

1. Clone repository
    ```
    git clone https://github.com/yura/CarND-LaneLines-P1-Solution.git
    ```
2. Change dir
    ```
    cd CarND-LaneLines-P1-Solution
    ```
3. Run Jupyter Notebook
    ```
    jupyter notebook P1.ipynb
    ```
