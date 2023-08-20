# Implementing Gradient Descent by hand 
An intuitive view of gradient descent and derivative concept.

**Gradient descent** is an optimization algorithm used in machine learning and mathematical optimization. It's a method for finding the minimum of a function by iteratively adjusting the parameters in the direction of the steepest descent of the function. The goal is to reach the local or global minimum of the function by taking steps proportional to the negative of the gradient of the function at the current point. This process is repeated iteratively until a convergence criterion is met. Gradient descent is a fundamental technique used in training machine learning models, particularly in tasks like training neural networks.

The principal concept underlying gradient descent implementation is the **Derivative**. A derivative is usually presented as the rate of change of a function, for example $f(x)$ with respect to a variable (in this case x) representing the sensitivity of $f(x)$ for any value assumed by x: 
  
$$\frac{\Delta f}{\Delta x}$$


   **Derivative definition** is a local concept, calculated between an interval (between two points) in which the function is continuous (two input values $x_{1}$ and $x_{2}$, where $h=x_{2}-x_{1}$), and represented as the limit of that same interval when it gets down to 0, we usually found it as:

$$ f´(x)=\lim_{h \to 0}\frac{f(x_{1}+h)-f(x_{1})}{h}$$

   If we draw a line between the two input values (also known as the images of $x_{1}$ and $x_{2}$) what we obteined is a line that crosses the function $f(x)$ in the interval defined by $x_{1}$ and $x_{2}$ (secant line), as the interval is reduced, the images of the two input values, $f(x_{1})$ and $f(x_{2})$, tend to get closer, at a point that there is no distance between these, making $h=x_{2}-x_{1}=0$

   ![](animation/simple_descent_1.gif)
