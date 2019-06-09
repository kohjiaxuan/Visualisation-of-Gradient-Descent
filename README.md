# Visualisation-of-Gradient-Descent
1. By visualizing the gradient descent algorithm applied on a set of points that fits a quadratic equation, we understand better how the algorithm works. This is essential to understand how machine learning and numerous Python libraries work under te hood
2. Latest file is <b>FINAL. Gradient Descent with quadratic equation variable learning rate.ipynb</b> modified on 9 Jun 2019
3. Inspiration of this project was in <b>BA. ODE Equation solving with Pandas (Midpoint Method).ipynb</b>, which aimed to apply Euler/Midpoint Method (first order approximation) via numpy and pandas library
4. Older versions of Juypter Notebook are named in alphabetical order (BA to BBH)
5. Older designs of quadratic equation visualisation are also present in the repository, latest version is <b>Gradient_descent_23may.png</b>

## Implementing Gradient Descent on Python with numpy and pandas, visualisation with matplotlib
#### Graphs of cost function and parameter movement per iteration will be made
1. We are fitting a quadratic equation onto 16 points on the x-y plane. The best fit equation is 0.996x^2 - 1.9343x - 14.149 with R^2 of 0.993
2. The three parameters a0, a1, a2 in y = a0 + a1*x + a2*x^2 will start from 0 and it will change via gradient descent algorithm to eventually fit the points
3. Two dataframes are used. One is calc, which is the dataframe storing information on the current parameter values, their mean sq error to find the gradient vector
4. The second dataframe, learn, is to store information of how the cost function, gradient vectors and parameters move per iteration
5. An overlay of all the quadratic equations over 80 iterations is shown to understand how the graphs 'curls' to fit the plots
6. Plot of cost functions also show how the algorithm converges
7. The parameter movement is plotted in a 3D graph to understand how the algorithm 'walks' down the slope of cost function
8. My understanding and intepretation of the graphs are explained in the comments or markdown in the (FINAL. Gradient Descent with quadratic equation variable learning rate.ipynb) notebook. Please refer to the main notebook itself for the full details.

## Visualisation of Gradient Descent over 80 iterations (i=0 to 79)
![Gradient Descent for Quadratic Equation over 80 iterations](https://github.com/kohjiaxuan/Visualisation-of-Gradient-Descent/blob/master/Gradient_descent_23may.png)
<br>
Please refer to the main notebook itself for further analysis and other visualisations.

## Libraries used
numpy and pandas for calculations and structuring data results, and matplotlib (2D and 3D) for visualisation purposes
