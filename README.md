# README
Project Name: cot-4500-Pro1

# Description:
This code allows you to find the approximations and solutions to numbers and functions that the user provides. 

# Approximation Algorithm: 
Using the approx_algorithm function, user must input the original and tolerance value of the number they are attempting to approximate as well as the function being utilized which assigned to the variable x. 

# Bisection Method:
Using the bisection_method() function method allows users to find roots to continuous functions by calling the function, f(x), and returning the function that the user is trying to find the roots for by placing it in "return". The user must also put in left and right starting endpoints, desired error tolerance, and maximum iterations allowed within the bisection_method() argument within the main function.

# Fixed-point Iteration: 
Users can use the fixedpoint_iteration() function to solve equations by repeatedly applying a function to an initial guess, aiming to find a value (called a "fixed point") where the function applied to that value returns the same value. To do this, input the function you want to utilize within the g(x) function located on top of the function within the "return" portion of the function. Within main, the user must input the following within the fixed_iteration() argument: initial approximation, error tolerance, and max number of iterations.

# Newton-Raphson Method: 
The function newtonraph_method() allows users to approximate the roots of functions. For this function to work, place the function being used into the "return" portion of the h(x) function as well as placing the function's first deriavtive in the "return" part of the derive(x) function and place the following values within the newtonraph_method() argument in the main function: initial approximation, desired tolerance, and max number of iterations.

# Requirements: 
You only need to install the following libraries to utilize this code: 
      1) math
      2) numpy

pip install -r requirements.txt

# Run Program:
python main.py

