# Deep-Learning
Perceptron Programming, Neural Network Training, and Convolutional Neural Network.


Perceptron Programming:

Write a Python code that shows the action of the perceptron algorithm for the given dataset at
the end of this assignment. Start with an initial set of weights W = (0,0,0) and bias = 0. Use the
following different learning rates:
1- η = 0.1.
2- η = 0.2.
3- η = 0.3.


About Dataset
We have chosen a simple numpy array to implement the single layer perceptron algorithm. We
have considered a total of 13 samples with three features and one class label. The class label is
defined in binary 0 and 1. The training dataset contains eight data samples, while the validation
dataset contains five.


train_data = np.array([ 
                     [1.00, 0.08, 0.72, 1.0],
                     [1.00, 0.10, 1.00, 1.0],
                     [1.00, 0.26, 0.58, 1.0],
                     [1.00, 0.35, 0.95, 0.0],
                     [1.00, 0.45, 0.15, 1.0],
                     [1.00, 0.60, 0.30, 1.0],
                     [1.00, 0.70, 0.65, 0.0],
                     [1.00, 0.92, 0.45, 0.0] 
])


test_data = np.array([
                    [1.00, 0.42, 0.85, 0.0],
                    [1.00, 0.65, 0.55, 0.0],
                    [1.00, 0.20, 0.30, 1.0],
                    [1.00, 0.20, 1.00, 0.0],
                    [1.00, 0.85, 0.10, 1.0]
])



Neural Network Training:

Write a Python code that simulates the following neural network architecture. The given
architecture has three inputs (x1, x2, x3), one hidden layer consists of two neurons, and one
output layer. Assume that all neurons are using Sigmoid activation function. The loss function
(Error function) is square error (t
k – o
k
)
2
.
You need to train the given neural network, and update the weights using Stochastic Gradient
Descent approach. During each example training, the weights should be updated.
Assume the initial weights and biases values are the following:
W1= 0.2 W2= -0.3 W3= 0.4 W4= 0.1
W5= -0.5 W6= 0.2 W7= -0.3 W8= -0.2
b1= -0.4 b2= 0.2 b3= 0.1
After training the model for 20 epochs, Draw the loss amount after each epoch.


About Dataset
Use the attached csv file “moonDataset.csv”. The dataset has 200 examples of different values
of the inputs x1, x2, x3. There are two labels (0/1) for the entire dataset. The inputs and labels are
shown in the attached csv file.


 Convolutional Neural Network:

 Convolutional neural network (CNN) is a regularized type of feed-forward neural network that
learns feature engineering by itself via filters (or kernel) optimization. Vanishing gradients and
exploding gradients, seen during backpropagation in earlier neural networks, are prevented by
using regularized weights over fewer connections.
Extensive research is recorded for face recognition using CNNs, which is a key aspect of
surveillance applications. In most recent times, the Face Recognition technique is widely used in
University automation systems, Smart Entry management systems, etc. In this paper, a novel
CNN architecture for face recognition system is proposed including the process of collecting face
data of students. Experimentally it is shown that the proposed CNN architecture provides 99%
accuracy. Further, the proposed CNN framework is used to develop a “Smart Attendance
Management System (SAMS)“, which is a web-based application, to provide attendance of
students using face recognition, in real time. The proposed application is easy to deploy and
maintain.
In this project you need to build a face recognition system using CNN in Python. You can take a
look on any available source code available. The submitted code should include trained model
and test cases. It is preferable to customize the project to the class students, so you can recognize
them immediately.
