# Implementing Gradient Descent by hand 
An intuitive view of gradient descent and derivative concept.

**Gradient descent** is an optimization algorithm used in machine learning and mathematical optimization. It's a method for finding the minimum of a function by iteratively adjusting the parameters in the direction of the steepest descent of the function. The goal is to reach the local or global minimum of the function by taking steps proportional to the negative of the gradient of the function at the current point. This process is repeated iteratively until a convergence criterion is met. Gradient descent is a fundamental technique used in training machine learning models, particularly in tasks like training neural networks.

In this repository, we'll get closer to this concept through the geometric representation of some mathematical concepts, so that we can follow the behavior of gradient descent through some cool animations:

1. **Derivative**

 .  The principal concept underlying gradient descent implementation. **Derivative definition** is a local concept, calculated between an interval (between two points) in which the function is continuous (two input values $x_{1}$ and $x_{2}$, where $h=x_{2}-x_{1}$), and represented as the limit of that same interval when it gets down to 0, we usually found it as:

$$ f´(x)=\lim_{h \to 0}\frac{f(x_{1}+h)-f(x_{1})}{h}$$

  
  ![](animations/Derivative.gif)
