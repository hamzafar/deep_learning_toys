# Deep Learning Toys

## TL;DR
A collection of deep learning algorithms implemented from scratch using NumPy, inspired by Andrew Ng’s Deep Learning Specialization and the philosophy of leading researchers.  
The goal is to build intuition by coding everything manually — **no PyTorch, no TensorFlow**.

---

## Motivation

This repository is inspired by:

- **Andrew Ng** — strong foundations and intuition  
- **Geoffrey Hinton** — trust your intuition and code it  
- **Yoshua Bengio** — build small deep learning toys  
- **Andrej Karpathy & Ian Goodfellow** — implement algorithms from scratch  

Combining these ideas, this repo focuses on **minimal, educational implementations** that reveal how deep learning works internally.

---

## Philosophy

- 🚫 No deep learning frameworks (PyTorch / TensorFlow)
- ✅ NumPy-only implementations
- 🧩 Small, self-contained “toys” that demonstrate core concepts
- 📘 Code-first learning with clear math and logic

---

## Learning Progression

The notebooks follow a natural progression in model complexity and capability.



### 1. Logistic Regression (XOR)

- First attempt to model the XOR problem using regression  
- Works on simple inputs  
- Fails to generalize on complex or larger datasets  

**Notebooks:**
- [Derivation in the Context of Logistic Regression](https://github.com/hamzafar/deep_learning_toys/blob/master/derivation-in-context-of-logistic-regression.ipynb)   
  - Exploring derivation concepts and their application to a regression model  
  - Step-by-step regression with parameter updates using Gradient Descent  
  - Discussing model convergence
- [Regression for XOR](https://github.com/hamzafar/deep_learning_toys/blob/master/regression-for-xor.ipynb)  
  - Extends the previous work for XOR problem  
  - Handles varying dataset sizes  
  - Evaluates performance across different datasets and parameters

---

### 2. Multi-Layer Neural Network (MLP)

- Introduction of hidden layers  
- Demonstrates non-linear function approximation  
- Successfully solves XOR  
- Flexible architecture with configurable number of neurons  

**Notebooks:**
- [Two Layers Neural Network](https://github.com/hamzafar/deep_learning_toys/blob/master/two-layers-neural-network.ipynb)  
  - Constructing neurons for a Two-Layer Neural Network  
  - Implements feedforward and backpropagation
- [Multi-Layer Neural Network]( https://github.com/hamzafar/deep_learning_toys/blob/master/multi-layer-neural-network.ipynb)  
  - Exploring generic neural network architecture  
  - Deploying and evaluating performance on varying dataset lengths

---

### 3. Recurrent Neural Network (RNN)

- Introduces the concept of **memory**  
- Processes inputs sequentially  
- Hidden state carries information across time steps  
- Demonstrates how past context influences future predictions  

**Notebook:**
- [Recurrent Neural Network]( https://github.com/hamzafar/deep_learning_toys/blob/master/recurrent-neural-network.ipynb)  
  - Overview of RNNs and their implementation  
  - Evaluates performance on datasets with varying lengths of training examples
---

## Experiments & Results

The following models are trained and evaluated:

- Logistic Regression  
- Multi-Layer Neural Network  
- Recurrent Neural Network  

### Dataset Settings

- Binary datasets  
- Number of rows: **10,000 / 100,000**  
- Number of features: **50**  

Error curves and comparisons are included in the notebooks.

---

## What You Will Learn

- Forward and backward propagation  
- Gradient descent from scratch  
- Why XOR fails with linear models  
- How depth enables expressiveness  
- How memory works in neural networks  
- How deep learning models are built internally  

---

## Who This Repo Is For

- Students learning deep learning fundamentals  
- Engineers who want **framework-free understanding**  
- Anyone preparing for research, interviews, or teaching  
- People who believe **intuition > APIs**  

---

## Disclaimer

This repository is **not optimized for speed or production use**.  
It is intentionally simple and educational.

---

## Author

**Hamza Zafar**  
Senior AI & Data Science Consultant  
Focus: Deep Learning, Computer Vision, and AI Systems








---
# Deep Learning Toys:

## Background:
Getting inspiation from **Andrew_Ng** deep learning speccialization; **Heros of Deep Learning** I am compiling jupyter notebooks that focuses on the tips of the Heros. Below are main points; will be considering in this repo:

**1. Geofry Hinton:**
    Work on your own intiuation & code it
    
**2. Yoshua Bengio:**
    Create small deep learning toys
    
**3. Andrej Karpathy & Ian Good Fellow:**
    Deploy Algorithms from scratch
    
 
Compiling all tips together, we are making a toy that will understand Deep learning algorithms and deploy them from scratch. After then we will do some intuation in deep learning algorithms.  This Toy is really excited by new type of *Electricity* and really want to be an **Artificial Electrical Specialist**. Let's have toy story:

**[Please Note: The Algorithm from scratch, that are deployed on Kaggle Kernel, can be seen on the links in the story.]**

---

Alex has recently come to know about the new form of electricty that can transform the industrization. He is really excited to learn about it. So, he plans to build a basic circuit to start learning with that can replicate *XOR* gate but he is not using electric gate, instead he tries to implement this "new" concept that is just brought up in his knowledge. 

As Alex is new-bie in the field and he really does not know much about this field concepts but all he knows that there is tool Regression that can build *XOR* gate. So, he just picks up the tool and starts building his first basic *XOR* gate. His detailed demo of gate can be seen on the following link: [Make first gate](https://www.kaggle.com/hamzafar/derivation-in-context-of-logistic-regression)

In his first attempt, Alex just used only two input values to validate his gate operation either it's working fine or not. But surperising his gate is giving him superb results as it is working ~100% accurately. He does not hold himself and after making his hands dirty to build *XOR* gate with simple input he thinks to generalize this circut gate with more complex inputs to check how his work is robust. In the link [Regression for XOR](https://www.kaggle.com/hamzafar/regression-for-xor) he automates the gate and check it on various load setting(by load setting we mean different shape of input data).

But, alas, his automated Regression gate is not powreful to cope up load testing! :(

There is a guy in Alex class, who always secures more marks than him and also beat Alex in different competitions in the school, and Alex was really jealous from him. One day his smart fried told him about concept of Artificial Neural Network and **its power of aproximation to every equation in the universe**. Alex, got excited about the concept and was really happy to deploy it to solve his *XOR* problem. So, he deployed a simple [two neural network using KISS principle](https://www.kaggle.com/hamzafar/two-layers-neural-network).


He is excited, as his simple Network is giving him excellent results as compared to Regression. So, he generalized the simple architecture into complex one. He named it [Multi Layer Perceptrons](https://www.kaggle.com/hamzafar/multi-layer-neural-network). The architecture is flexible one, that it can include more neuorns(Logistic Regression Units) in it. These units stack up together to build a netowrk that is much bigger and deep than the simple network: made before.

Since, Alex was inspired by functions of brain and brain has one excellent functionality "Memory"; he wanted to replicate that concpet in his work. He came to know about the type of Artificial Neural Netowrk names as [Recurrent Neural Network](https://www.kaggle.com/hamzafar/recurrent-neural-network). They can read inputs x (such as bits) one at a time, and remember some information/context through the hidden layer activations that get passed from one time-step to the next. This allows a RNN to take information from the past to process later inputs.


### Result Comparision:

The three algorithms: Logistic Regression, Multi-layer Neural Network and Recurrent Neural Network, are trained on two different binary datasets whose length(number of rows) is *10000, 100000* and width (number of column) is *50*. The table below contains the error graphs of each algorithm.


Algorithms | Training Sample:10000 |Training Sample:100000 |
------------- |:-------------:| -----:|
Regression | ![](https://github.com/hamzafar/deep_learning_toys/blob/master/images/Reg-10000.png?raw=true) | ![](https://github.com/hamzafar/deep_learning_toys/blob/master/images/Reg-100000.png?raw=true)|
Multi-layer Neural Network | ![](https://raw.githubusercontent.com/hamzafar/deep_learning_toys/master/images/Two%20Layers_Neural_Network/nn-10000.png) | ![](https://github.com/hamzafar/deep_learning_toys/blob/master/images/Two%20Layers_Neural_Network/nn-100000.png?raw=true) |
Recurrent Neural Network | ![](https://github.com/hamzafar/deep_learning_toys/blob/master/images/rnn/rnn-10000-1000-007.png?raw=true) | ![](https://github.com/hamzafar/deep_learning_toys/blob/master/images/rnn/rnn-100000-1000-007.png?raw=true)|







**(WORK IN PROGRESS!! He is exploring to build gate more powerful.)**
