# Perceptron - Inspired by The Coding Train 🚂💻

Welcome to the **Perceptron** project! 🎉 This is a fun, visual demo of a simple machine learning algorithm, inspired by The Coding Train (aka Daniel Shiffman). We're going to build a **Perceptron** that learns to classify points based on a linear boundary. 🚀

## About

A **Perceptron** is a type of artificial neuron that helps solve binary classification problems. This code randomly generates points and trains a perceptron to classify them based on their position. The perceptron will try to draw a line (or hyperplane) that best divides the points into two categories.

The training process is visualized with a **decision boundary** that updates as the perceptron learns. Pretty cool, right? 😎

## How It Works

1. **Random Points**: 
   The program generates a bunch of random points on a 2D grid. Each point is labeled either green or red based on a simple condition: if the x-coordinate is greater than the y-coordinate, it’s green. Otherwise, it’s red.

2. **Training**: 
   The perceptron gets these points as inputs, adjusts its weights and bias through training, and tries to predict the correct label for each point.

3. **Learning**: 
   The perceptron uses the **sign function** to decide which side of the boundary the point falls. Over time, as it trains on more points, it gets better and better at correctly classifying them.

4. **Visualization**: 
   You get a **scatter plot** showing the points, color-coded by the perceptron’s predictions. After training, you also get to see the **decision boundary** that the perceptron draws to separate the two categories.

## Fun Fact

Did you know? The Perceptron was invented in 1958 by **Frank Rosenblatt** and was one of the earliest neural network models. It's one of the building blocks of modern deep learning! 🧠

## Happy Coding!
Feel free to tweak the parameters, add more features, or challenge the perceptron with different kinds of data. If you're inspired by The Coding Train's tutorials, you're in great company! 🎬✨
