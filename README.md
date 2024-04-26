# Experiment-07-Linear and joint interpolation of industrial manipulator
# Date: 26-04-2024
# Name: Ashwin kumar K
# Reference Number: 212221223001
# Department: IT
### Aim :
To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 


### Program : 
DART studio screen shots for linear interpolation 
![robo-1](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/2c8ee6bf-73f2-4953-86ba-111691cffd5b)









DART studio screen shots for joint interpolation 
![robo-1(1)](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/5fd07f71-c0e6-4cb1-939b-d553c47a66c1)








### Robot movements 

![robo-1(2)](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/edfe42bd-0035-4b75-8d69-de93f11f4370)

![robo-1(3)](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/e696370f-561a-46f6-bcb1-586b9ee8031e)

![robo-1(4)](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/fcf1bbd1-194d-4ba7-9050-a7fe049a798a)

![robo-1(5)](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/56933d3d-1676-4fe2-8268-1f631b593a8c)








### Results:  
Hence,the Linear and joint interpolation of industrial manipulator is successfully executed.
