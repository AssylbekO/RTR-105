Lab work №3:

Numerical Methods; Numerical deffirentiation.

Description:
Numerical differentiation is the process of finding the numerical value of a derivative of a given function at a given point.


![image](https://user-images.githubusercontent.com/90827811/150869176-2242947c-63e3-49cf-a9df-eebf9580b5f2.png)





Goal for this particular laboratory work:


Understanding the usage of deffirentiation in coding and mathematics, calculating first and second order derivatives using analytical and finite formula.


Left border : 0
Right border : 3.14
Result:

![image](https://user-images.githubusercontent.com/90827811/151060056-77ff6aa0-ff57-4ce2-94e7-314bb157b37e.png)


This code successfully calculates and displays:
1) Dialogue with a user to obtain both left and right borders of the interval on the x-axis.
2) Dialogue with a user to obtain the desired presicion.
3) values of J0(x) for x between a and b 
4) values of J0'(x) for x between a and b (using analytical formula)
5) values of J0'(x) for x between a and b (using forward difference)
6) values of J0''(x) for x between a and b (using analytical formula)
7) values of J0''(x) for x between a and b (using forward difference)


With the help of WolframAlpha I found all of the necessary derivatives:
![image](https://user-images.githubusercontent.com/90827811/151060643-b521ae43-cc64-4699-bf70-27d8ef9c1486.png)

![image](https://user-images.githubusercontent.com/90827811/151060723-4b362146-9720-4bb9-8b1e-f3c0e9f4c689.png)




And most importantly by the help of GNUPLOTWEB I managed to present it graphically (with the derivative.dat file that I made):

By calculating the data with my code, in the interval from [0:6,28] and precision of 0.01 I found all of the points needed to do the graph.



Gnuplot output:


![image](https://user-images.githubusercontent.com/90827811/151035733-54da8e7a-5713-4583-83d2-a3879df1443a.png)











