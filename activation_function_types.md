# **Activation Functions and When to Use Them?**
<br></br>
## **What is Activation Fuction.**
Activation functions are an extremely important feature of the artificial neural networks. They basically decide whether a neuron should be activated or not. Whether the information that the neuron is receiving is relevant for the given information or should it be ignored.
The activation function is the non linear transformation that we do over the input signal. This transformed output is then sen to the next layer of neurons as input.

<br></br>
## **Types Of of Activation Function**
There are several Types of Activation Function Which arae used in Machine learning and Neural Networks. we gona discuss soeme of them.

1. Identity
2. Binary Step
3. Sigmoid
4. Tanh
5. ReLU
6. Leaky ReLU
7. Softmax


### **Identity function**
An identity function, also called an identity relation or identity map or identity transformation, is a function that always returns the same value that was used as its argument.

### **Binary Step**
A binary step function is generally used in the Perceptron linear classifier. It thresholds the input values to 1 and 0, if they are greater or less than zero, respectively.

### **Sigmoid**
sigmoid function is normally used to refer specifically to the logistic function, also called the logistic sigmoid function

### **Tanh**
A tanh function ensures that the values stay between -1 and 1, thus regulating the output of the neural network. You can see how the same values from above remain between the boundaries allowed by the tanh function.

### **ReLU**
The main reason why ReLu is used is because it is simple, fast, and empirically it seems to work well.ReLU is the most widely used activation function while designing networks today. First things first, the ReLU function is non linear, which means we can easily backpropagate the errors and have multiple layers of neurons being activated by the ReLU function.

### **Leaky ReLU**
Leaky ReLU function is nothing but an improved version of the ReLU function.

### **Softmax**
The softmax function is also a type of sigmoid function but is handy when we are trying to handle classification problems. The sigmoid function as we saw earlier was able to handle just two classes. What shall we do when we are trying to handle multiple classes. Just classifying yes or no for a single class would not help then. The softmax function would squeeze the outputs for each class between 0 and 1 and would also divide by the sum of the outputs. This essentially gives the probability of the input being in a particular class