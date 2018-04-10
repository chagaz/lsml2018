# Large Scale Machine Learning 2018 Practical Sessions

## Day 1 Introduction to Machine Learning with Python

This repository contains Jupyter notebooks for the first  afternoon of practical sessions of the LSML 2018 course.

To run the notebooks, you need to start Jupyter by typing

  ```jupyter notebook```

in a terminal. This will open a file navigator in your web browser. Navigate to this repository. You can then open any notebook by clicking on it.

If you are already familiar with Python and numerical Python (numpy) as well as matplotlib, you can start with Notebook 3. We recommend, however, doing the small problems in Notebooks 1 and 2 to familiarize yourselves with Jupyter and refresh your knowledge of these tools.

The focus of our first afternoon of practicals is going to be Notebooks 3 and 4, which introduce data manipulation and machine learning with scikit-learn. If you still have time, you can get started on Notebook 5.

## Day 2 Feature engineering with Python

We have so far assumed that our data is represented by a well-behaved matrix X with n rows/samples and p columns, each corresponding to a feature. An important part of data science, however, is to transform raw data in such features.

Start with Notebook 5 (from Day 1) and move on to Notebook 6, where you'll explore data pre-processing in more details.

## Day 3 Deep learning

If you have never trained a ConvNet before (in particular, if you did not take the "Apprentissage Artificiel" course by Fabien Moutarde, start with http://perso.mines-paristech.fr/fabien.moutarde/ES_MachineLearning/TP_convNets/TP_convNets.html

Then you can move on to transfer learning with deep networks at http://perso.mines-paristech.fr/fabien.moutarde/ES_LSML/TP_TransferLearning-ConvNet/TP_TransferLearning-ConvNets.html

## Day 4 Stochastic gradient descent

A large part of machine learning rests on convex optimization and gradient descent techniques. How does one perform gradient descent with large data? This is what you'll explore in Notebook 7.

## Personal installation
Everything that is needed to do the labs should be installed on the Mines machines.

If you want to do the labs on your own machine, you will need to have Python and all the relevant packages installed. The easiest way to install all the requirements is to install [Anaconda](https://www.continuum.io/downloads). If you prefer, you can also install only the required packages (numpy, scipy, matplotlib, seaborn, scikit-learn, pandas, jupyter) with pip if you already have Python.
