# Kernel-perceptron

This script implements the perceptron update rule for non-linearly separable data using the kernel form. The goal is to learn a decision function using Linear Learning Machines (LLM) for data where a linear(decision) boundary between the classes cannot be drawn. The points are mapped to a (usually) higher dimensional space which separates the two classes by a hyperplane using a dual represenation of the dot product between the points (which implies similarity between the points).

 A new point is then classified by the learned hyperplane. 
 
 The following kernel is used:
 
*K(x1, x2) = <x1, x2><sup>2* 
  
  
