# **Finding Lane Lines on the Road** 

## Pipeline

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I .... 

1. Converted to grayscale

![grayscale](./writeup-images/01-grayscale.jpg)

2. Denoised using Gaussian filter with kernel 3

![denoised](./writeup-images/02-denoised.jpg)

3. Detected edges using Canny algorithm. Threshold values are calculated using the median of pixel intensities. More info at: [Zero-parameter, automatic Canny edge detection with Python and OpenCV](http://www.pyimagesearch.com/2015/04/06/zero-parameter-automatic-canny-edge-detection-with-python-and-opencv/)

![edges](./writeup-images/03-edges.jpg)

4. Masked region of interest

![masked-edges](./writeup-images/04-masked_edges.jpg)

5. Detected all possible lines using Hough Transform algorithm

![all-lines](./writeup-images/05-all_lines.jpg)

6. Filtered out lines which don't look like lane ones

6.1. Divided all lines to left and right lists by the slope of the line. Lines with the negative slope are left lane line candidates. Lines

### 2. 

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...



Please expand the reflection section a little more. "We would like you to share your thoughts on your lane finding pipeline... specifically, how could you imagine making your algorithm better / more robust? "


Проблемы:
смена полос
условия освещения
поворот камеры
требуется калибровка камеры для того чтобы понять как прямо стоят колёса

Creating a Great Writeup
---
For this project, a great writeup should provide a detailed response to the "Reflection" section of the [project rubric](https://review.udacity.com/#!/rubrics/322/view). There are three parts to the reflection:

1. Describe the pipeline

2. Identify any shortcomings

3. Suggest possible improvements

