#  DSA_21_group2
## **Dynamic Time Warping in Time Series Analysis**

This is the folder for DSA Spring 21 Project "Dynamic Time Warping in Time Series Analysis" 

## Group members

Zihao Ding  
net id: zd75  email: zd75@scarletmail.rutgers.edu  

Hongpeng Zhang  
net id: hz227   email: hz227@scarletmail.rutgers.edu  

## Files
-- DTW_code   &nbsp; (Folder contains the Code for DTW)  
&nbsp;&nbsp; &nbsp; &nbsp; |-- BasicDTW.py &nbsp; (Python code for the DTW project, in Python 3.6)&nbsp;  
&nbsp; &nbsp; &nbsp; &nbsp;|-- Data &nbsp; (Folder contains the Data we used for DTW runtime testing)&nbsp;  
-- ScreenShots &nbsp; (Folder contains the image made for presentation)  
-- DTW_Presentation.pdf &nbsp; (The Presentation)  
--DTW_573_Final_Project.pdf &nbsp; (The final project report)  

##  Brief description of project:

The real world is full of time series data, as almost every data collected by real world sensors is time series data. Many engineering tasks requires analysis on such data. For example, human speech produces time series data naturally, and recognition of its content is based on comparisons between multiple series of data. The analysis of time series data requires  proper tools, and one of which is Dynamic Time Warping (DTW).

In time series analysis, dynamic time warping (DTW) is one of the algorithms for measuring similarity between two temporal sequences, which may vary in speed. For instance, similarities in walking could be detected using DTW: even if two people are walking in different speed, DTW can still find out if their gait frequency and distance are similar, in other word, they are walking in the similar pattern. DTW is very useful in time series analysis as it can normalize the data in time.

In this project, we explains the DTW algorithm in detail and tested its performance.  
For more details please refer to the paper attached.

## **INSTRUCTIONS** for compile the project:
- The BasicDTW.py was written in Python 3.6 on a win10 machine.  
- To compile the BasicDTW.py, please first make sure you have the [**numpy**](https://pypi.org/project/numpy/) and [**pandas**](https://pypi.org/project/pandas/) library.  
- If you would like to also get the colored DTW result matrix in the hand computable example part of the code,  [**matplotlib**](https://pypi.org/project/matplotlib/) is also required.
- The BasicDTW.py mainly is in two parts:  
> The first part is the general DTW function where you can select which DTW algorithm to use when calculating the DTW distance. (Basic DTW and DTW with window, more refer to paper) To run the code please refer to the ' === MAIN Function, change INPUT from here ===' tag in the code. follow the instruction there to change the input, input size, and which DTW method to use.

>The second part is a simple hand computable DTW example with result visualization. To run the code, please refer to the '===DTW simple example with visualization ===' tag in the code. The compile of this part is in comment as default, if you would like to run this part, please follow the instruction in the code file to uncomment the main part in order to run the code. 


TLDR: 
```
$ python BasicDTW.py
```
