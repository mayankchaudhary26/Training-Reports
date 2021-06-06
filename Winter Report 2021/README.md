                                                                    🎓  WINTER TRAINING REPORT
                                                                                On
                                                                    Neural Networks & Deep learning


                                             Submitted to Guru Gobind Singh Indraprastha University, Delhi (India)
                                         in partial fulfillment of the requirement for the award of the degree of B.TECH

                                                                                in

                                                              ELECTRONICS AND COMMUNICATIONS ENGINEERING

                                                                            Submitted By
                                                                          MAYANK CHOUDHARY

                                                                        Roll. No. 35515002818




                                                              DEPTT. OF ELECTRONICS AND COMMUNICATIONS

                                                           🏫MAHARAJA SURAJMAL INSTITUTE OF TECHNOLOGY ,
                                                                         NEW DELHI-110058

                                                                           FEBRUARY 2021



👩‍🏫👨‍🏫

# ACKNOWLEDGEMENT
A research work owes its success from commencement to completion, to the people in love with researchers at various stages. Let me in this page express my gratitude to all those who helped us in various stage of this study. First, I would like to express my sincere gratitude indebtedness to Mr. PUNEET AZAD (HOD, Department of Information Technology, Maharaja Surajmal Institute of Technology,New delhi) for allowing me to undergo the winter training of 30 days at ………...................................COURSERA................................................

I am grateful to my instructor Andrew Ng for this easy to learn course and their way of teaching marks a really strong effect.

Last but not least, I pay my sincere thanks and gratitude to all the Staff Members of Maharaja Surajmal Institute of Technology,New delhi for their support and for making our training valuable and fruitful.

<br>


📝

# Contents
## 1. Introduction to Deep Learning
1.1  What is neural network?
1.2  Supervised Learning with Neural Networks

## 2. Logistic Regression as a Neural Network
2.1   Logistic regression and gradient descent
2.2   Python and Vectorization

## 3. Shallow Neural Network
3.1   Activation functions
3.2   Back propagation intuition 

## 4. Deep Neural Network

4.1   Deep L-layer neural network
4.2   Forward Propagation in Deep network
4.3   Forward and backward propagation
4.4   Parameters vs Hyperparameters
4.5   Programming assignment of deep neural network application


<br>
<br>
<br>

# What are neural networks?


Neural networks, also known as artificial neural networks (ANNs) or simulated neural net-works (SNNs), are a subset of machine learning and are at the heart of deep learn-ing algorithms. Their name and structure are inspired by the human brain, mimicking the way that biological neurons signal to one another.
Artificial neural networks (ANNs) are comprised of a node layers, containing an input layer, one or more hidden layers, and an output layer. Each node, or artificial neuron, connects to another and has an associated weight and threshold. If the output of any individual node is above the specified threshold value, that node is activated, sending data to the next layer of the network. Otherwise, no data is passed along to the next layer of the net-work.

![image](https://user-images.githubusercontent.com/56837137/120936271-aec79e80-c724-11eb-83c5-55a73fe17108.png)

                                     
# Different types of Neural Networks in Deep Learning
 
![image](https://user-images.githubusercontent.com/56837137/120936596-3a8dfa80-c726-11eb-80b8-a2da7cf33f0d.png)



# Standard/Artificial Neural Network (ANN)

A single perceptron (or neuron) can be imagined as a Logistic Regression. Artificial Neural Network, or ANN, is a group of multiple perceptrons/ neurons at each layer. ANN is also known as a Feed-Forward Neural network because inputs are processed only in the forward direction:

![image](https://user-images.githubusercontent.com/56837137/120936606-4bd70700-c726-11eb-8e52-e55dcd4bbfb5.png)
ANN



Artificial Neural Network is capable of learning any nonlinear function. Hence, these networks are popularly known as Universal Function Approximators. ANNs have the capacity to learn weights that map any input to the output.
One of the main reasons behind universal approximation is the activation function. Activation functions introduce nonlinear properties to the network. This helps the network learn any complex relationship between input and output.
 
![image](https://user-images.githubusercontent.com/56837137/120936614-58f3f600-c726-11eb-988e-4112511216c6.png)




# Recurrent Neural Network (RNN)

A looping constraint on the hidden layer of ANN turns to RNN.
•	RNN captures the sequential information present in the input data i.e. dependency be-tween the words in the text while making predictions:

•	RNNs share the parameters across different time steps. This is popularly known as Parameter Sharing. This results in fewer parameters to train and decreases the computational cost
 
![image](https://user-images.githubusercontent.com/56837137/120936619-614c3100-c726-11eb-99c2-e2d4c3c27958.png)



# Convolution Neural Network (CNN)
Convolutional neural networks (CNN) are all the rage in the deep learning community right now. These CNN models are being used across different applications and domains, and they’re especially prevalent in image and video processing projects.

•	CNN learns the filters automatically without mentioning it explicitly. These filters help in extracting the right and relevant features from the input data.
•	CNN captures the spatial features from an image. Spatial features refer to the ar-rangement of pixels and the relationship between them in an image. They help us in identifying the object accurately, the location of an object, as well as its relation with other objects in an image.

![image](https://user-images.githubusercontent.com/56837137/120936624-6a3d0280-c726-11eb-86fa-83bfc7cc3820.png)


# Logistic Regression as a Neural Network

Logistic regression is a binary classification method. It can be modelled as a function that can take in any number of inputs and constrain the output to be between 0 and 1.  This means, we can think of Logistic Regression as a one-layer neural network. For a binary output, if the true label is y (y = 0 or y = 1) and y_hat is the predicted output – then y_hat represents the probability that y = 1 -  given inputs w and x. Therefore, the probability that y = 0 given inputs w and x is (1 - y_hat), as shown below.
 
![image](https://user-images.githubusercontent.com/56837137/120936642-7cb73c00-c726-11eb-988f-bcd4a1606a91.png)
![image](https://user-images.githubusercontent.com/56837137/120936646-80e35980-c726-11eb-910d-548a8c725718.png)



# What is a Gradient?

A gradient measures how much the output of a function changes if you change the inputs a little bit
It simply measures the change in all weights with regard to the change in error. You can also think of a gradient as the slope of a function. The higher the gradient, the steeper the slope and the faster a model can learn. But if the slope is zero, the model stops learning. Said it more mathematically, a gradient is a partial derivative with respect to its inputs.
![image](https://user-images.githubusercontent.com/56837137/120936654-893b9480-c726-11eb-807b-98c1fc660f84.png)


# What is Vectorization ?

Vectorization is used to speed up the Python code without using loop. Using such a function can help in minimizing the running time of code efficiently. Various operations are being performed over vector such as dot product of vectors which is also known as scalar product as it produces single output, outer products which results in square matrix of dimension equal to length X length of the vectors, Element wise multiplication which products the element of same indexes and dimension of the matrix remain unchanged.

 
![image](https://user-images.githubusercontent.com/56837137/120936660-8f317580-c726-11eb-8be7-59a24f991eed.png)

































