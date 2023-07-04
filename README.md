# The Challenge of Vanishing/Exploding Gradients in Deep Neural Networks
==========================
# As known : Vanishing Gradient problem appear from using Tanh or Sigmoid Activation Functions & Exploding Gradient problem appear from using Relu Family Activation Functions.

# If we used aggregation between two activation functions it will balance between Vanishing and Exploding problems ??

# like using aggregation between Tanh & Leaky RELU.
# AD2(z) = Tanh(z) + 0.5*Leaky_Relu(z) <-- blue line in image
![]()

# However, Learning speed & Accuracy won't decrease when using aggregation than using Leaky RELU only 
## (please check this notebook in GitHub link --> https://lnkd.in/dkhkfWJA).

# Difference between just Leaky_Relu (green) and Aggregation 2 functions in post (blue).
# it seem decrease exploding because it decrease inputs, Aren't it? 🤔
![]()

## Demos link:  https://lnkd.in/dNdcFizE
 
