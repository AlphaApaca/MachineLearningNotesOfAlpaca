# Machine Learning Notes of Alpaca



## Chapter 0: Some Concepts of Machine Learning

In this chapter, I will summarize all related concepts about machine learning, to let me make a more profound understanding about essential concepts of ML.

### 0.1 Machine Learning definition

##### Arthur Samuel (1959). Machine Learning:

***Field*** of study that <u>gives computers the ability to learn</u> *without being explicitly programmed.*

##### Tom Mitchell (1998) Well-posed Learning Problem:

***<u>A computer program</u>*** is said to <u>learn from **experience E**</u> with <u>respect to some **task T**</u> <u>and some **performance measure P**</u>, 

if its performance on T, as measured by P, improves with experience E.

###### For Checkers playing example:

+ **experience E** : having the program play tens of thousands of games against itself.
+ **task T** : Play checkers
+ **performance measure P** : the probability that it wins the next game of checkers against some new opponent.

### 0.2 Machine learning algorithms

#### Main two types:

+ **Supervised learning**
+ **Unsupervised learning**

#### Others:

+ Reinforcement learning
+ Recommender systems.

#### Also talk about: 

Practical advice for applying learning algorithms.

## Chapter 1: Supervised learning & Unsupervised learning

##### Supervised Learning: “right answers” given

+ **Regression:** Predict <u>continuous valued</u> output

+ **Classification:** <u>Discrete valued</u> output (0 or 1）

##### Unsupervised Learning

+ clustering algorithm