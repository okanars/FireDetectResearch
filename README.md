# FireDetectResearch
Analysis of deep learning models used for fire detection within the scope of a research project. The project includes the SqueezeNet, MobileNetv2, and FireNet models.
Of course! Here's the English version of the description and README file:


# Deep Learning Models for Fire Detection

This repository contains a research project focused on training and testing deep learning models for the early detection and monitoring of forest fires.

## Contents
1. [About the Project](#about-the-project)
2. [Models Used](#models-used)
3. [Results](#results)
4. [Setup and Usage](#setup-and-usage)
5. [Acknowledgments](#acknowledgments)

## About the Project
The early detection and monitoring of forest fires are among the most effective ways to prevent their spread. However, monitoring these events can be challenging as they often occur in hard-to-reach areas. This project employs deep learning models to overcome these challenges.

## Models Used
- **SqueezeNet:** A lightweight and efficient model. While it demonstrates high performance when trained with Pytorch, it couldn't be deployed successfully with TensorFlow.
- **MobileNetv2:** Overall, it has the highest accuracy, precision, and F1-Score values.
- **FireNet:** Its ability to detect non-fire images (recall) is slightly lower.

## Results
The training and testing results are presented in detail in the "Experimental Results" section. These results allow us to compare the performance of each model.

## Setup and Usage
1. Clone this repository to your local machine.
2. Install necessary libraries.
3. Run the files to execute the codes.

## Acknowledgments
The dataset used in this project was created by Ahmed Gamaleldin, Ahmed Atef, Heba Saker, and Ahmed Shaheen. The dataset is publicly available on Kaggle [here](https://www.kaggle.com/datasets/phylake1337/fire-dataset).
