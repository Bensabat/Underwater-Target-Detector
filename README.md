# Underwater-Target-Detector

## Goal

The purpose of this project is, in a first part to classify seabed images with or without target/checkerboard. In a second part, the goal is to localize target.

## Contents

The Notebook contains these following parts:
* 1.0 Import
* 2.0 Setting
* 3.0 Data Augmentation
* 4.0 Box annotation
* 5.0 Classification with SVM
* 6.0 Box detection
* 7.0 Model testing

The project contains:

* src folder containing the notebook file
* data folder containing
     * checkerboard dataset
     * seabed dataset
     * target dataset
* doc folder containing the report

## Installation

This program has been developed with Python programming language, under Jupyter Notebook.

This project use the following libraries:

- NumPy (image storing as NumPy arrays)
- Pandas (dataframe managment)
- Matplotlib (image display)
- Skimage	(geometric transformation on images)
- OpenCV 3+ (image processing, machine learning)
- Scikit-learn (machine learning)
- Keras (deep learning) (with TensorFlow backend)

## Execution

Run the Notebook `src/exploration.ipynb` into Jupyter and launch the cells.

- If you want to test the classification with your own dataset, go to part `7.1 Classification Testing`, launch the function `classification_testing(path)` with the path of your dataset.

- If you want to test the localization with your own dataset, go to part `7.2 Localization Testing`, launch the function `localization_testing(path)` with the path of your dataset.


## Bibliography

Some internet sources that helped me to understand the problem and propose a solution:

- Data Augmentation for Deep Learning: https://medium.com/nanonets/how-to-use-deep-learning-when-you-have-limited-data-part-2-data-augmentation-c26971dc8ced
- Github and lectures lab of teacher Ollion Charles : https://github.com/m2dsupsdlclass/lectures-labs/tree/master/labs/05_conv_nets_2

## Authors

EPITA School, SCIA Master 2 - Project for Computer Vision Course.

Authors: 
- **BENSABAT David** (bensab_d)
- **YVONNE Xavier** (xavier.yvonne)