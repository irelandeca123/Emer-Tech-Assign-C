# Emerging Technologies Project 2018

## Introduction
I am student of the B.Sc. (Hons) in Software Development at GMIT and as a part of this project we were asked to research
and create a number of notebooks including a script I will go through each one and how to use it below.
We were asked to include the following researches in notebook:

- **Numpy random notebook:** a research regarding the concepts behind and the use of the numpy random package, including plots 
of the various distributions.
- **Iris dataset notebook:** a research explaining the famous iris data set including the difficulty in writing an algorithm to separate
the three classes of iris based on the variables in the dataset.
- **MNIST dataset notebook:** a notebook explaining how to read the MNIST dataset efficiently into memory in Python.
- **Digit recognition script:** a Python script that takes an image file containing a handwritten digit and identifies the digit using a
supervised learning algorithm and the MNIST dataset.
- **Digit recognition notebook:** a jupyter notebook explaining how the above Python script works and discussing its performance.


## Layout
I have seperated each notebook & script as described above into individual folders making it easier to read, understand & access.
I reccomend reading the notebooks first provided before getting into the script as it will give you more knowledge and understanding of how
the actual code works if you are begginer and looking at building your own neural network.These are the most common libraries found in this 
research so make sure you have them installed:

- panda
- sklearn
- skimage
- numpy
- collections
- cv2
- matplotlib

## Packages
To install those libraries or packages outline above open your CMD and run the following command for each of them: pip3 install [name of dependency].

## Cloning Digit Recognition Script Repository
I highly recommend before working with the digit recognition script to read the notebook first as I have outlined everything
you need to know about the script , running it, usage & results obtained from running the script.

> Open Git Bash

> Change the current working directory to the location where you want the cloned directory to be made (cd)

> git clone https://github.com/irelandeca123/Emer-Tech-Assign-C/tree/master/DigitRecognition

>Press Enter. Your local clone will be created.

## How to run the digit recognition script
- 1.Clone the repository as outline above.
- 2.Generate the dataset: Run the script mnist_generator.py in order to train the classifier which will produce a file called digits_cls.pkl.
> python generateClassifier.py
or you can use any python environment compiler.
- 3.Testing the classifier: Run the script called digitrec.py in order to test the classifier.
> python digitrec.py

