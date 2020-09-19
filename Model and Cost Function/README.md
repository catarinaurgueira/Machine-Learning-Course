# Machine Learning - Introduction

"A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T, as measured by P, improves with experience E."

For example: if we have an email program that watches which emails you do or do not mark as spam, and based on that learns how to better filter spam. 
Classifying emails as spam or not spam in the task T. 
Watching you label emails as spam or not spam is the experience E. 
And the number (or fraction) of emails correctly classified as spam/not spam is the perfomance P.

Another example: a computer program that plays checkers. 
The Experience E is the experience of playing many games of checkers. The task T is the task of playing checkers. And the perfomance P is the probability that the program will win the next game.

There are two main types of learning algorithms are: 
* Supervised learning
* Unsupervised learning


## Supervised Learning

The main idea is to teach the computer how to do something. 

We are given a data set and already know what our correct output should look like, having the idea that there is a relantionship between the input and the output.

### **Regression**

Regression: Predict continuous valued output, meaning that we are trying to map input variables to some continuos functoin. For example, the price for the house.

Example of a regression problem: You have a large inventory of identical items. You want to predict how many of these items will sell over the next 3 months. 

Another example:  Given a picture of a person, we have to predict their age on the basis of the given picture.

### **Classification**

Classification: Predict results in a discrete output, meaning that we are trying to map input variables into discrete categories.

Example of a classification problem: You'd like software to examine individual customer accounts, and for each account decide if it has been hacked/compromised.

Another example: Given a patient with a tumor, we have to predict whether the tumor is malignant or benign.


## Unsupervised Learning

The main idea is to let the computer learn by itself.

Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.

We can derive this structure by clustering the data based on relationships among the variables in the data.

With unsupervised learning there is no feedback based on the prediction results.

### **Clustering**

Clustering: Take a collection of 1,000,000 different genes, and find a way to automatically group these genes into groups that are somehow similar or related by different variables, such as lifespan, location, roles, and so on.

### **Non-clustering**

Non-clustering: The "Cocktail Party Algorithm", allows you to find structure in a chaotic environment. (i.e. identifying individual voices and music from a mesh of sounds at a cocktail party).



