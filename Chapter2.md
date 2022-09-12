# Chapter 2 Learning Objectives:
By the end of the chapter, you will be able to:

- Differentiate between traditional programming paradigms and the machine learning paradigm
- Compare and contrast AI, ML, and Deep Learning
- Describe the three types of machine learning – supervised, unsupervised, and reinforcement learning 
- Explain the process of training a typical machine learning system 
- Define features or attributes of data used in machine learning
- Define regression problems with examples
- Define classification problems with examples
- Explain the differences between regression and classification problems
- Describe what TensorFlow.js is
- Enumerate the advantages of performing machine learning using TensorFlow.js in JavaScript environments
- Explain the three ways of performing machine learning – using pre-made models, using transfer learning, and rolling out custom models

## AI vs. ML vs. Deep Learning
### AI
Definition: human intelligence exhibited by machines

Narrow AI: A system that can do one or maybe a few things as well or better than a human expert for that task

Examples of Narrow AI:
- text classification (automated forwarding based on message content)
- image classification (detecting cancer in images of brain tissue samples)

### ML
Definition: A program that runs and can learn from prior experience to find patterns in a given set of data. Can be retrained on a different dataset. 

Examples of Machine Learning:
- Object detection (where and how many of a thing are in an image whereas image detection detects the presence of something)
- Natural Language Processing (Spam detection; text content in emails are marked as spam from thousands of users and the model detects what is most likely to be spam; it is retrained every day; E.g.#2: Sentiment analysis of social media posts; Text Summarization; Language Translation)
- Linear Regression (a line of best fit to make a correlation between points of data on a graph; e.g. predicting house prices or stock prices)
- Audio Generation (turning your voice into a musical instrument; turning voice audio into human-readable text)
- Image Generation (Generating Human faces based on learned examples)

### Deep Learning
Uses Backpropagation to perform unsupervised learning. Contains multiple layers. 

### Compare & Contrast
Artificial Intelligence is the process of enabling human intelligence in systems. A subset of AI is Machine Learning. ML is an actual program that can learn from data. Deep Learning is a class of algorithm that can drive a machine learning program. 

## Demystifying Machine Learning
Machine Learning Models are initially untrained. There are three types of methods to train them:
- Supervised Learning: Data used to train the machine learning system is pre-labeled. (e.g. Classifying objects: Spam Detection, Text categorization, Object Recognition)
- Unsupervised Learning: Training using unstructured/unlabeled data. (e.g. Clustering: recommendation engines)
- Reinforcement Learning: Strengthens actions that return a reward. Weakens connections that return a punishment. (e.g. Game Development & Robotics) 

## How to Train ML systems
### Key Concepts
Data: 

Data is the information provided to, processed, and analyzed by a machine learning model. Input data can be images, tabular data, numbers, text, sensor recordings, sound samples, etc. 

Features/Attributes:

Features are characteristics or attributes of the input data used to train an ML system. They are the properties of the things you are trying to learn. 

Regression Model:

A regression model predicts a number based on numerical inputs. The output is the equation of a line, where the line itself is used to predict an output number based on the input feature values.

Classification Model:

A classification model predicts discrete classes or labels from several possible known classes or labels. The output is a line or a plane that separates different classes.

### Examples
[Teachable Machine](https://teachablemachine.withgoogle.com/)

[Family ML Recognition Model](https://teachablemachine.withgoogle.com/models/KogCD1fq4/)

[Family ML Gist](https://gist.github.com/efwoods/a84b45dbd0711d14e067ab86c1716cf1)