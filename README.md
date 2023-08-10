# Welcome to My Convex Optimization
## Task
The task was an introduction to some convex optimization tools to solve problems such as root of function f and linear problems

## Description
I optimized a simple function using the following convex optimization tool;
def print_a_function: It was used to find the minimum of function f.
def find_root_newton_raphson(f, f_deriv, start, tol=1e-6, max_iter=1000): It used the Newton-Raphson method to find a root of f using f_deriv
def find_root_bisection(f, a, b): It implemented the bisection method for finding the root of a function f
root_brentq = brentq(f_prime, -2, 2)- this was used to check against the bisection method if the root of functon f gotten above is correct. It is called Brent's method for optimization
def gradient_descent(f, f_prime, start, learning_rate=0.1, eps=1e-6): is a numerical optimization algorithm that can be used to find the minimum of a differentiable function f
def solve_linear_problem(A, b, c): It took-in the linear problems(A, b, c)and solve them using the simplex algorithm.

## Installation
There was no need for installation as it can easily be run on local machine using jupyter notebook and other necessary dependencies

## Usage
The code was run on a jupyter notebook whose http address can be gotten by running this in the terminal:
jupyter notebook --no-browser
Then the jupyter http address can be followed and the password: 'qwasar' inputed

### The Core Team
Bukola Veronica Oladele(veronica_b)

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>


