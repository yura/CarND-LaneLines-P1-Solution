# Feedback

* Increasing `min_line_len` and `max_line_gap` (~100 and above) for Hough Transform will make your lines longer and will have less number of breaks. (this will make the solid annotated line longer in the output) Increasing `max_line_gap` will allow points that are farther away from each other to be connected with a single line.
* Threshold increasing (~ 50-60) will rule out the spurious lines.(defines the minimum number of intersections in a given grid cell that are required to choose a line.)
* Kernel size in the Gaussian Filter will remove the noise making the image less blurry. Must be an odd number (3, 5, 7...)
* Use rho value of 2 or 1 which gives distance resolution in pixels of the Hough grid

## Links
* Self-Driving Car Project Q&A | Finding Lane Lines https://www.youtube.com/watch?v=hnXkCiM2RSg
* Robust and Real Time Detection of Curvy Lanes (Curves) Having Desired Slopes for Driving Assistance and Autonomous Vehicles http://airccj.org/CSCP/vol5/csit53211.pdf
* Style Guide for Python Code https://www.python.org/dev/peps/pep-0008/


## Few points to think upon

* Can a different colour space be used to make the pipeline more robust?
* Tune the parameters http://stackoverflow.com/questions/36598897/python-and-opencv-improving-my-lane-detection-algorithm
here
