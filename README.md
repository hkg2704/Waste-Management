# Waste-Management
AICTE - Shell Internship on Al with Green Skills Week1
Waste Management Image Classification
This repository contains a script for preprocessing and analyzing a waste management dataset for image classification tasks. The goal is to classify waste into categories such as "organic" and "recyclable." Below is an overview of the workflow:

Features:
Dataset Loading:

Images are loaded from directories specified in train_path (training dataset) and test_path (test dataset).
Each subfolder in these directories corresponds to a waste category (e.g., "organic", "recyclable").
Image Preprocessing:

Images are read using OpenCV (cv2.imread) and converted to RGB format.
Processed images are stored in x_data with their respective labels in y_data.
Data Organization:

A pandas DataFrame is created to store image-label pairs for easier analysis.
Dataset Analysis:

Visualizes the class distribution using a pie chart with percentage labels, colors, and a shadow effect for better aesthetics.
Visualization:
A pie chart is generated to show the proportion of waste categories in the dataset, helping to identify class imbalances.
Next Steps:
Train a deep learning model (e.g., CNN) on this dataset to classify waste into respective categories.
Test the model's performance using accuracy metrics, confusion matrices, and classification reports.
Dependencies:
Python libraries: numpy, pandas, matplotlib, cv2, tensorflow/keras, glob, tqdm.
