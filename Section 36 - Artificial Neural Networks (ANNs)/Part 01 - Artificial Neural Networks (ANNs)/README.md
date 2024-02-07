# Artificial Neural Networks (ANNs)

## Plan of Attack

**What we will learn in this section:**

* The Neuron

* The Activation Function

* How do Neural Networks work? (example)

* How do Neural Networks learn?

* Gradient Descent

* Stochastic Gradient Descent

* Backpropagation
<hr>

## The Neuron

<img src="Images/The Neural Network.png" alt="The Neural Network in Deep Learning" width="70%">

<img src="Images/Additional Reading - Efficient BackProp.png" alt="Additional Reading - Efficient BackProp" width="70%">

http://yann.lecun.com/exdb/publis/pdf/lecun-98b.pdf
<hr>

## The Activation Function

<img src="Images/The Activation Function.png" alt="The Activation Function" width="70%">

<hr>

### Types of Functions in Activation Function

<img src="Images/Threshold Function.png" alt="Threshold Function" width="70%">

<img src="Images/Sigmoid Function.png" alt="Sigmoid Function" width="70%">

* **Sigmoid Function** is a function which is used in the logistic regression, if you recall, from the Machine Learning course.

<img src="Images/Rectifier Function.png" alt="Rectifier Function" width="70%">

<img src="Images/Hyperbolic Tangent (tanh) Function.png" alt="Hyperbolic Tangent (tanh) Function" width="70%">

<img src="Images/Additional Reading - Deep Sparse.png" alt="Additional Reading - Deep Sparse" width="70%">

http://jmlr.org/proceedings/papers/v15/glorot11a/glorot11a.pdf
<hr>

## How do Neural Networks work?

<img src="Images/Neural Networks working.png" alt="How do Neural Networks work?" width="70%">

    where,
        C = Cost Function (It tells us what is the error that you have in your prediction)

<img src="Images/Cost Functions Lists & Applications.png" alt="List of Cost Functions used in NNs, alongside applications" width="70%">

http://stats.stackexchange.com/questions/154879/a-list-of-cost-functions-used-in-neural-networks-alongside-applications
<hr>

## Stochastic Gradient Descent

<img src="Images/Additional Reading - Gradient Descent.png" alt="A NN in 13 lines of Python (Part 2 - Gradient Descent)" width="70%">

https://iamtrask.github.io/2015/07/27/python-network-part2/

<img src="Images/Additional Reading - Neural Networks and Deep Learning.png" alt="A NN in 13 lines of Python (Part 2 - Gradient Descent)" width="70%">

http://neuralnetworksanddeeplearning.com/chap2.html
<hr>

## Backpropagation

### Training the ANN with Stochastic Gradient Descent

**Step 1:** Randomly initialise the weights to small numbers close to 0 (but not 0).

**Step 2:** Input the first observation of your dataset in the input layer, each feature in one input node.

**Step 3:** *Forward-Propagation:* from left to right, the neurons are activated in a way that the impact of each neuron's activation is limited by the weights. Propagate the activations until getting the predicted result *y*.

**Step 4:** Compare the predicted result to the actual result. Measure the generated error.

**Step 5:** *Back-Propagation:* from right to left, the error is back-propagated. Update the weights according to how much they are responsible for the error. The learning rate decides by how much we update the weights.

**Step 6:** Repeat Steps 1 to 5 and update the weights after each observation (Reinforcement Learning). Or:<br>
&emsp;&emsp;&emsp;Repeat Steps 1 to 5 and update the weights only after a batch of observations (Batch Learning).

**Step 7:** When the whole training set passed through the ANN, that makes an epoch. Redo more epochs.
<hr>

## Additional Reading

[The Ultimate Guide to Artificial Neural Networks(ANN)](https://www.superdatascience.com/blogs/the-ultimate-guide-to-artificial-neural-networks-ann)
<hr>

## Extra Content: ANN Case Study (1 HR Course)

Dear Students,

Great job advancing in the course and completing the ANN section. As a bonus, we are sharing with you the following link to more practical material: Build an ANN Regression model to predict the electrical energy output of a Combined Cycle Power Plant. You can find it [here](https://www.udemy.com/course/linear-regression-with-artificial-neural-network/?referralCode=2E5BC40C4E666DC53A22) and keep up the awesome work!

Enjoy ML!
<hr>