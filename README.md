# SeedClassification

🌾 Seed Classification Model
This project provides a machine learning model built with a Decision Tree Classifier to identify the type of seed based on its geometric properties. The model is trained on a dataset containing seven key features, and the included Jupyter Notebook allows for both model training and interactive prediction.

🧐 Overview
The core of this project is a machine learning pipeline that takes the following seven features of a seed as input:

Area

Perimeter

Compactness

Kernel Length

Kernel Width

Asymmetry Coefficient

Kernel Groove

Based on these measurements, the trained model predicts which of the three types of seeds it belongs to. The notebook also includes code for evaluating the model's performance using a confusion matrix and a classification report.

🚀 Getting Started
Prerequisites
Python 3.x

Jupyter Notebook or a similar environment to run the .ipynb file.

Installation
Clone the repository:

Bash

git clone https://github.com/your-username/seed-classification-model.git
cd seed-classification-model
Install the required libraries:

Bash

pip install pandas numpy scikit-learn
Usage
Ensure both seeds (1).csv and the seed.ipynb notebook are in the same directory.

Open and run the seed.ipynb notebook in your environment.

The notebook will guide you through the data loading, model training, and evaluation steps.

At the end, it will prompt you to enter the geometric values for the seed you want to classify.

After entering the values, the program will output its prediction.

Example
Here's a sample of the prediction output after the user enters the required values:

Enter Area value:15
Enter Perimeter value:14
Enter Compactness value:1
Enter Kernel Length value:5
Enter Kernel Width value:3
Enter Asymmetry Coeff value:2.0
Enter Kernel Groove value:5.0

The prediction: [1]
The seed is type 1
📁 Project Structure
seed.ipynb: The main Jupyter Notebook containing all the code for data processing, model training, evaluation, and user-input predictions.

seeds (1).csv: The dataset used to train the machine learning model.

README.md: This file.

🛠️ Built With
Pandas - For data manipulation and analysis.

Numpy - For numerical operations.

Scikit-learn - For building the Decision Tree Classifier and evaluating the model.

✍️ Authors
Suriya Panneerselvam
