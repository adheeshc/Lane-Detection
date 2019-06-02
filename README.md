# Lane-Detection

## **PROJECT DESCRIPTION**

The aim of this project is to do simple Lane Detection to mimic Lane Departure Warning systems used in Self Driving Cars. The task is to design an algorithm to detect lanes on the road, as well as estimate the road curvature to predict car turns.

Please refer to [Project Report](https://github.com/adheeshc/Lane-Detection/blob/master/Report/Project%202.pdf) for further description

### Encoding Stage

<p align="center">
  <img src="/Images/ref_marker_grid.png" alt="Reference Marker">
</p>

### Detection Stage

<p align="center">
  <img src="/Images/Detection.png" alt="Detect Tag" width="200"/>
</p>


### Tracking Stage

<p align="center">
  <img src="/Images/track.png" alt="Track Tag">
</p>


### Superimposing Lena

<p align="center">
  <img src="/Images/Lena_on_Tag.gif" alt="Lena on Tag">
</p>

### Placing a Virtual 3D Cube

<p align="center">
  <img src="/Images/Cube_on_Tag.gif" alt="Cube on Tag">
</p>

## **DEPENDANCIES**

- Python 3
- OpenCV
- Numpy
- Copy (built-in)


## **FILE DESCRIPTION**

- Code Folder/[Code 1(Both).py](https://github.com/adheeshc/Lane-Detection/blob/master/Code/Code%201(Both).py) - The code file can be run on both Project video and Challenge Video but isnt optimal for either
- Code Folder/[Code 2(Project only).py](https://github.com/adheeshc/Lane-Detection/blob/master/Code/Code%202%20(Project%20Only).py) - The code file has been optimized for the Project Video
- Code Folder/[OPTIONAL_HoughLines_Project2.py](https://github.com/adheeshc/Lane-Detection/blob/master/Code/OPTIONAL_HoughLines_Project2.py) - The code file where Hough Lines was attempted. It was later ignored due to reasons mentioned in [Project Report](https://github.com/adheeshc/Lane-Detection/blob/master/Report/Project%202.pdf) 

- Datasets folder - Contains 2 video input files 

- Images folder - Contains images for github use (can be ignored)

- Output folder - Contains output videos

- Report folder - Contains [Project Report](https://github.com/adheeshc/Lane-Detection/blob/master/Report/Project%202.pdf)

## **RUN INSTRUCTIONS**

- Make sure all dependancies are met
- Ensure the location of the input video files are correct in the code you're running
- Comment/Uncomment as reqd

- RUN Code 1(Both).py for both project and challenge video
- RUN Code 2(Project Only).py for project video (Optimized)
- RUN OPTIONAL_HoughLines_Project2.py for Hough Lines method
