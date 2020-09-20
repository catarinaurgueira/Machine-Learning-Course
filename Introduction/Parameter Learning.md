# Model and Cost Function

## Model Representation

Notation:
* m = Number of training examples. Is called the training set. 
* x's = "input" variable / features
* y's = "output" variable / "target" variable
</br>
</br>
* (x, y)= one training example
* (x(1), y(1)) = i training example


To describe the supervised learning problem slightly more formally, our goal is, given a training set, to learn a function h : X → Y so that h(x) is a “good” predictor for the corresponding value of y. </br>
This function h is called a hypothesis. 

**Function Hypothesis:**

X (input) &rarr; Function h &rarr; Predicted Y (output)

h theta (x) = theta zero + (theta one * x)

**The process is therefore like this:**

Training Set &rarr; Learning Algorithm &rarr; Function Hypothesis (h) 


When the target variable that we’re trying to predict is continuous, such as in our housing example, we call the learning problem a regression problem. When y can take on only a small number of discrete values (such as if, given the living area, we wanted to predict if a dwelling is a house or an apartment, say), we call it a classification problem.

## Cost Function

The cost function is used to measure the accuracy of the hypothesis function.
It quantifies the error between predicted values and expected values and presents it in the forme of a single real number. 

Idea: Choose theta zero and theta one, so that h theta (x) is close to y for our training examples (x,y).

The purpose of the Cost Function is to be either: 
* Minimized - then returned value is usually called cost, loss or error. The goal is to find the values of model parameters for which Cost Function return as small number as possible.
* Maximized - then the value it yields is named a reward. The goal is to find values of model parameters for which returned number is as large as possible
