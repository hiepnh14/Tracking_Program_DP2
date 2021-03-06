# Design Practice 2 tracking program

[//]: # (## Nagoya University G30 Engineering)
## Authors: 
- G. Franco,
- H.H. Nguyen,
- S. Nazirjonov

## Project Description 
Ball tracking program for DP2 class. Used to trace ball across board using webcam feed or MP4 video file. Uses OpenCV module to identify and track ball via color selection and background subtraction methods, and logs ball data using custom data models created with Pydantic. Applies NumPy and SkLearn math to calculate physical movement properties.

## Modules/Libraries Used
- OpenCV
- NumPy
- Imutils
- MatplotLib
- PyTest
- Pydantic
- CSV
- Tabulate
- Datetime
- Scikit-Learn

## How to run program
Install the necessary requisite modules, then run "main.py" file.
Change the input video by changing the directory of the video in main.py.
