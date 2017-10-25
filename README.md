# A Deep Neural Network Speech Recongnizer

## Overview
This project analyzes several different neural networks, including various types of Recurrent Neural Networks and convolutional neural networks, for their ability to take speech data and return the corresponding text. As input this project uses speech snipits from the [LibriSpeech dataset](http://www.openslr.org/12/). This work was done to complete a project for the Udacity Artificial Intelligence Nanodegree (AIND). The original project instructions can be found in the `Project_Instructions.md` file.

## Contents
To understand this project it is recommended to start by looking at the following two files:

 `vui_notebook.ipynb` - A Jupyter Notebook containing the textual description of the project's scope, executable script, and the script output.
 
 `sample_models.py` - This file contains the implementation details of the models called in the `vui_notebook,ipynb` script

## Requirements
This project requires Python 3.6 to run. The `requirements.txt` file contains the additional Python packages needed to run this project.

This project is designed to be run on a Computer containing a Nvidia GPU compatible with Tensorflow. Running this project only on a CPU will likely take a prohibitively long time.

## Usage
To run the project open and execute the Jupyter Notebook. In the terminal execute:

`jupyter notebook vui_notebook.ipynb`
