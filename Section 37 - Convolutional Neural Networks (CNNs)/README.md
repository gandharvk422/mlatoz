# Convolutional Neural Networks (CNNs)
<hr>

## Plan of Attack

**What we will learn in this section:**

* What are Convolutional Neural Networks?

* **Step 1** - Convolution Operation

* **Step 1(b)** - ReLU (Rectified Linear Unit) Layer

* **Step 2** - Pooling

* **Step 3** - Flattening

* **Step 4** - Full Connection

* Summary

* EXTRA: Softmax & Cross-Entropy
<hr>

## What are Convolutional Neural Networks?

### Additional Reading

<img src="Images/Additional Reading - Gradient-Based Learning.png" alt="Gradient-Based Learning Applied to Document Recognition" width="70%">

[Gradient-Based Learning Applied to Document Recognition - By Yann LeCun et al. (1998)](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)
<hr>

## Step 1 - Convolution

<code>(f * g)(t) =<sup>def</sup> <sub>-∞</sub>∫<sup>∞</sup>f(Ƭ)g(t - Ƭ)dƬ</code>

<img src="Images/Additional Reading - Intro to CNNs.png" alt="Introduction to Convolutional Neural Networks" width="70%">

[Introduction to Convolutional Neural Networks - By Jianxin Wu (2017)](http://cs.nju.edu.cn/wujx/paper/CNN.pdf)
<hr>

## Step 1(B) - ReLU (Rectified Linear Unit) Layer

<img src="Images/Additional Reading - Understanding CNNs with A Mathematical Model.png" alt="Additional Reading - Understanding Convolutional Neural Networks with A Mathematical Model" width="70%">

[Understanding CNNs with A Mathematical Model - By C. C. Jay Kuo (2016)](https://arxiv.org/pdf/1609.04112.pdf)

<img src="Images/Additional Reading - Delving Deep into Rectifiers.png" alt="Additional Reading - Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification" width="70%">

[Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification - By Kaiming He et al. (2015)](https://arxiv.org/pdf/1502.01852.pdf)
<hr>

## Step 2 - Max Pooling

<img src="Images/Additional Reading - Evaluation of Pooling Operations.png" alt="Evaluation of Pooling Operations in Convolutional Architectures for Object Recognition" width="75%">

[Evaluation of Pooling Operations in Convolutional Architectures for Object Recognition - By Dominik Scherer et al. (2010)](http://ais.uni-bonn.de/papers/icann2010_maxpool.pdf)
<hr>

## Summary

<img src="Images/Additional Reading - The 9 Deep Learning Papers.png" alt="The 9 Deep Learning Papers You Need to Know About (Understanding CNNs Part 3)" width="75%">

[The 9 Deep Learning Papers You Need to Know About (Understanding CNNs Part 3) - By Adit Deshpande](https://adeshpande3.github.io/The-9-Deep-Learning-Papers-You-Need-To-Know-About.html)
<hr>

## EXTRA: Softmax & Cross-Entropy

**Softmax Function:** <code>*f<sub>j</sub>(z) = e<sup>z</sup>j / ∑<sub>k</sub> e<sup>z</sup>k*</code>

**Cross-Entropy Function:** <code>*L<sub>i</sub> = -log(e<sup>f<sub>y<sub>i</sub></sub></sup> / ∑<sub>j</sub> e<sup>f<sub>j</sub></sup>)*</code>

**Another Representation of Cross-Entropy Function:** <code>*H(p, q) = -∑<sub>x</sub> p(x) log q(x)*</code>

**Additional Reading:**

<img src="Images/Additional Reading - A Friendly Intro to Cross-Entropy Loss.png" alt="A Friendly Introduction to Cross-Entropy Loss" width="75%">

[A Friendly Introduction to Cross-Entropy Loss - By Rob DiPietro (2016)](https://rdipietro.github.io/friendly-intro-to-cross-entropy-loss/)

<img src="Images/Additional Reading - How to Implement a NN Intermezzo 2.png" alt="How to Implement a Neural Network Intermezzo 2" width="75%">

[How to Implement a Neural Network Intermezzo 2 - By Peter Roelants (2016)](http://peterroelants.github.io/posts/neural_network_implementation_intermezzo02/)
<hr>

## Additional Reading

[The Ultimate Guide to Convolutional Neural Networks(CNN)](https://www.superdatascience.com/blogs/the-ultimate-guide-to-convolutional-neural-networks-cnn)
<hr>
