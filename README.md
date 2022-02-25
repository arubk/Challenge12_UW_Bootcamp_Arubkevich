# Credit Risk Classification¶

This repository contains the code for a Jupyter notebook with using the knowledge of the imbalanced-learn library. I used a logistic regression model to compare two versions of the dataset (1st - use the original dataset, 2nd - resample the data by using the *RandomOverSampler* module from the imbalanced-learn library). I got the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

## Technologies

The application is written in Python 3.9.7 and uses the following libraries:

* numpy - 1.20.3
* pandas - 1.3.4
* sklearn -1.0.2
* imblearn - 0.9.0
* matplotlib - 3.4.3


The application runs from the command line on Windows, Linux or Mac OS systems, or from the Anaconda Navigator Software.

## Installation Guide
Download the repository code through GitHub and unpack the archive. Run the following commands to install all the dependencies:

pip install sklearn
pip install imblearn

PLease refer to Jupyter Notebook installation guide: https://jupyter.org/install.

## Usage
In the command line go to the folder containing the jupyter notebook. Run `jupyter notebook` to start the jupyter notebook. Alternatively, open Anaconda Navigator, click on "Launch Jupyter Notebook" to start the jupyter notebook.

## Contributors
Project author : A.Rubkevich

Contact information : anastasiyarubkevich@github.com

## License
MIT License

Copyright (c) 2021