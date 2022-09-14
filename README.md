# Junior-Data-Scientist-Assignment


Part 1 Q1 :
-
---
### Write a regex to extract all the numbers with orange color background from the below text in italics.

```bash
data = {"orders":[{"id":1},{"id":2},{"id":3},{"id":4},{"id":5},{"id":6},{"id":7},{"id":8},{"id":9},{"id":10},{"id":11},{"id":648},{"id":649},{"id":650},{"id":651},{"id":652},{"id":653}],"errors":[{"code":3,"message":"[PHP Warning #2] count(): Parameter must be an array or an object that implements Countable (153)"}]}
```
**Solution** - Wrote a class with exception handling. For code, please click here 


Part 1 Q2 :
-
---

```python
## Problem Statement 

We have to Train a machine learning model that predicts the customer who is going to be checked in. Once done, please test 
the prediction with below test data.


**Solution** - (https://colab.research.google.com/drive/1FBZnDKpgANxDroLTXeZAgfWYrJrmGC1K?usp=sharing)





Part 2 Q1 :
-
---

### Write about any difficult problem that you solved. (According to us difficult - is something which 90% of people would have only 10% probability in getting a similarly good solution).

- I have observed personally, people are good at programming, however sometimes lagging in understanding the business.
- In one of our project, at the initial stage we were facing problem to understand the business and to get start with the solution, at that time I have created & represented HLD, LLD and Wireframe with all my related research, after getting approval we started working on it.
- This is one of the incident, I have contributed in so many such scenarios.


Part 2 Q2 :
-
---





### Explain back propagation and tell us how you handle a dataset if 4 out of 30 parameters have null values more than 40 percentage

Backpropagation is the process of neural network training. It is the method of fine-tuning the weights of a neural network based on the error rate obtained in the previous epoch (i.e., iteration). Proper tuning of the weights allows you to reduce error rates and make the model reliable by increasing its generalization.

Backpropagation in neural network is a short form for “backward propagation of errors.” It is a standard method of training artificial neural networks. This method helps calculate the gradient of a loss function with respect to all the weights in the network.

here are the following are ways to handle missing data values:

1. If the data set is large:

We can just simply remove the rows with missing data values.
It is the quickest way, we use the rest of the data to predict the values.
2. For smaller data sets:

We can substitute missing values with the mean or average of the rest of the data using the pandas' data frame in python. There are different ways to do so, such as df.mean(), df.fillna(mean).



