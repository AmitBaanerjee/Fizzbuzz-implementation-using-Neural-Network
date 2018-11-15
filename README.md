#Task


We consider the task of FizzBuzz. In this task an integer divisible by 3 is printed as
Fizz, and integer divisible by 5 is printed as Buzz. An integer divisible by both 3 and
5 is printed as FizzBuzz. If an integer is not divisible by 3 or 5 or 15, it simply prints
the input as output (for this last case, the input number can be classified as Other in
Software 2.0, it should then be handled using Software 1.0, which prints the input as
output).
Your programs will be tested on how well they perform in converting integers from
1 to 100 to the FizzBuzz labels.

#Implementation of Fizzbuzz using neural network using Keras Library


First you need to create a training data set for numbers ranging from 101 to 1000.
We avoid training on integers 1 to 100 because that forms the testing set (In machine
learning it would be considered cheating to train on the testing set). We present this
training set to the program in the form of (input,output) pairs.
To design the learning program, you will have to make decisions on hyper-parameters
such as the learning rate, number of epochs, loss function, regularizer, etc. Since
outputs are discrete, you can use cross-entropy as your loss function. Plot the performance
of your program for different values of the hyper-parameters.
