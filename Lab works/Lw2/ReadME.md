Laboratory work #2:
Numerical Methods; Bisection Methods.

Desctiption:
The method consists of repeatedly bisecting the interval defined by these values and then selecting the subinterval in which the function changes sign, and therefore must contain a root.

![image](https://user-images.githubusercontent.com/90827811/150868440-04b157f4-ef72-4bce-ae41-4375c4aab12c.png)


Source: https://en.wikipedia.org/wiki/Bisection_method




My function:
Bessel function (J0):

![image](https://user-images.githubusercontent.com/90827811/150023729-282fc7ed-7e41-4266-93d0-9a8090b74010.png)

The output of the code with following values:
1) Left border = -6
2) Right border = 9
3) Desired value = 0.1
4) Desired presicion = 0.0001

![2](https://user-images.githubusercontent.com/90827811/150865238-5ac6b7ee-c5f8-4f4f-a0b3-635e1ed0e2d0.png)



Gnuplot output:

![image](https://user-images.githubusercontent.com/90827811/150867960-91afac8b-e5fa-42b2-ad4f-087ccf036ad3.png)


The code includes:

1) Dialogue with a user obtaining the left border about x-axis:
2) Dialogue with a user obtaining the right border about x-axis:
3) Dialogue with a user obtaining the value of C (where C is => J0(x) = C)
4) Dialigue with a user obataining the precision (or accuracy)
5) Calculating and showing the value of x for equation J0(x) = C for x between a and b
6) Calculating and showing the value of J0(x) for this x
7) Displays the number of iteration needed to get to the final result
