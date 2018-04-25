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

---

Alex has recently come to know about the new form of electricty that can transform the industrization. He is really excited to learn about it. So, he plans to build a basic circuit to start learning with that can replicate *XOR* gate but he is not using electric gate, instead he tries to implement this "new" concept that is just brought up in his knowledge. 

As Alex is new-bie in the field and he really does not know much about this field concepts but all he knows that there is tool Regression that can build *XOR* gate. So, he just picks up the tool and starts building his first basic *XOR* gate. His detailed demo of gate can be seen on the following link: [Make first gate](https://www.kaggle.com/hamzafar/derivation-in-context-of-logistic-regression)

In his first attempt, Alex just used only two input values to validate his gate operation either it's working fine or not. But surperising his gate is giving him superb results as it is working ~100% accurately. He does not hold himself and after making his hands dirty to build *XOR* gate with simple input he thinks to generalize this circut gate with more complex inputs to check how his work is robust. In the link [Regression for XOR](https://www.kaggle.com/hamzafar/regression-for-xor) he automates the gate and check it on various load setting(by load setting we mean different shape of input data).

But, alas, his automated Regression gate is not powreful to cope up load testing! :(

There is a guy in Alex class, who always secures more marks than him and also beat Alex in different competitions in the school, and Alex was really jealous from him. One day his smart fried told him about concept of Artificial Neural Network and **its power of aproximation to every equation in the universe**. Alex, got excited about the concept and was really happy to deploy it to solve his *XOR* problem. So, he deployed a simple [two neural network using KISS principle](https://www.kaggle.com/hamzafar/two-layers-neural-network).


He is excited, as his simple Network is giving him excellent results as compared to Regression. So, he generalized the simple architecture into complex one. He deployed it [Multi Layer Perceptrons](https://www.kaggle.com/hamzafar/multi-layer-neural-network).

:( :( The newbie  is not having pretty good results, and his [Multi Layer Perceptrons](https://www.kaggle.com/hamzafar/multi-layer-neural-network) is not giving better results than Regression. 

[RNN](https://www.kaggle.com/hamzafar/recurrent-neural-network) being deployed.
& Lstm

### Result Comparision:

Alex, is so curious to see which model is working best for *XOR* gate, so he generated the curve graph, 3 different dataset (training) whose length (row) is *10000, 100000 and 1000000* respectively and width (columns) is *50*. Below is the table, he is comparing among Regression and Multi-Layer Neural Network.

Data Set | Regression | Multi-layer Neural Network |
------------- |:-------------:| -----:|
10000 | ![](https://www.kaggleusercontent.com/kf/2733275/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..bDUoZx9WohwdfjKANXATog.PYB9s2tVWOXNsBBFJySeT6k0Ty1Llnl87dng8c4ynErrfFj4jPOAs2RF4vhVbvKVCrIUNNwch9p7ypGDirG0-pQ2NFZ0bKiZkO3ZaBmUkGk.pdks7UU7yKLkKklKZHRx3w/__results___files/__results___26_1.png) | ![](https://www.kaggleusercontent.com/kf/2889912/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..FE0SDfrL7Sid7oTkASLnCA.SyVGLnOGgIAzMySmxQTPoBib9RJ_UlUE9c9VTlWCwyjYxZ_DwD_E-FwjXPTA7zxhiEbBezmTdJF8ruLf5a5udKDDHQByDq0DXjpd5rZqyWg5GlpMLQ-MPvl4iarcGvqV.PU380UbuFd1hpiAqRPPeMQ/__results___files/__results___50_1.png) |
100000 | ![](https://www.kaggleusercontent.com/kf/2733275/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..XKzdh1JmWu1XN48m4BwVYg.0D58jAm1fc1Wg69sIkmSkMbJnsdBBfKjJgqi2gajIeJCcWlMTH5rgNCEnrUkG7_qd5l_BKEZRvEgVUTW5QRNMGVWqc8fg_9790oZ0jdRrFw.g2p18waAluAU6pTiJdkVnQ/__results___files/__results___26_3.png) |![](https://www.kaggleusercontent.com/kf/2889912/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..FE0SDfrL7Sid7oTkASLnCA.SyVGLnOGgIAzMySmxQTPoBib9RJ_UlUE9c9VTlWCwyjYxZ_DwD_E-FwjXPTA7zxhiEbBezmTdJF8ruLf5a5udKDDHQByDq0DXjpd5rZqyWg5GlpMLQ-MPvl4iarcGvqV.PU380UbuFd1hpiAqRPPeMQ/__results___files/__results___50_3.png) |
1000000 | ![](https://www.kaggleusercontent.com/kf/2733275/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..XKzdh1JmWu1XN48m4BwVYg.0D58jAm1fc1Wg69sIkmSkMbJnsdBBfKjJgqi2gajIeJCcWlMTH5rgNCEnrUkG7_qd5l_BKEZRvEgVUTW5QRNMGVWqc8fg_9790oZ0jdRrFw.g2p18waAluAU6pTiJdkVnQ/__results___files/__results___26_5.png) | ![](https://www.kaggleusercontent.com/kf/2889912/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..FE0SDfrL7Sid7oTkASLnCA.SyVGLnOGgIAzMySmxQTPoBib9RJ_UlUE9c9VTlWCwyjYxZ_DwD_E-FwjXPTA7zxhiEbBezmTdJF8ruLf5a5udKDDHQByDq0DXjpd5rZqyWg5GlpMLQ-MPvl4iarcGvqV.PU380UbuFd1hpiAqRPPeMQ/__results___files/__results___50_5.png) |


RNN


**(WORK IN PROGRESS!! He is exploring to build gate more powerful.)**
