# Perceptron_Task

A simple perceptron classifier is implemented by using 2 properties, sepal length and petal lenght to classify the dataset into versicolor and setosa flowers.

The perceptron classifier uses a **unit step function** to create a line that seperates the data points into binary classes labelled 1 and -1. 

We can then define a decision function (𝜙(𝑧)) that
takes a linear combination of certain input values, **x**, and a corresponding weight
vector, **w**, where z is the so-called net input 𝑧 = 𝑤1𝑥1 + 𝑤2𝑥2 +. . . .. This is compared with the threshhold value to classify the data points into either class.

The negative threshold is or weight is also called bias that is used with x=1.This is also called the bias unit.

The following steps are followed:

-intitialise the weights to random numbers or 0

-for each training example:

 -Compute output
 
 -update weights
 
 1. Intitialise the weights to random numbers or 0
 2. For each training example:
   - Compute the predicted output
   - Update the weights
     
 



