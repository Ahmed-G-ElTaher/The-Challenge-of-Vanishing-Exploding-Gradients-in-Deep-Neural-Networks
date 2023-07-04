# The Challenge of Vanishing/Exploding Gradients in Deep Neural Networks 🌋 
==========================
## 📎 As known : Vanishing Gradient problem appear from using Tanh or Sigmoid Activation Functions & Exploding Gradient problem appear from using Relu Family Activation Functions.

## 💡 If we used aggregation between two activation functions it will balance between Vanishing and Exploding problems ??
# __________________________________________________________

## like using aggregation between Tanh & Leaky RELU. 👇
## 📌 AD2(z) = Tanh(z) + 0.5*Leaky_Relu(z) <-- blue line in image
![](https://github.com/Ahmed-G-ElTaher/The-Challenge-of-Vanishing-Exploding-Gradients-in-Deep-Neural-Networks/blob/main/desmos-graph.png)
# __________________________________________________________

## However, Learning speed & Accuracy won't decrease when using aggregation than using Leaky RELU only 📊  
## (please check this notebook in Colab link --> https://lnkd.in/dkhkfWJA).
# __________________________________________________________

## Difference between just Leaky_Relu (green) and Aggregation 2 functions in post (blue). 📏 
![](https://github.com/Ahmed-G-ElTaher/The-Challenge-of-Vanishing-Exploding-Gradients-in-Deep-Neural-Networks/blob/main/1678260917291.png)
## it seem decrease exploding because it decrease inputs, Aren't it? 🤔


## Demos link:  https://lnkd.in/dNdcFizE
 
