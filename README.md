# Dental X-Ray Machine Learning Project

This project explores supervised machine learning techniques on dental X-ray data, combining both **regression** and **classification** tasks. The goal is to process annotated dental radiography images, extract meaningful labels, and build models that can support data-driven analysis in dental imaging.

## Project Overview

The notebook includes a complete experimental workflow for:

- loading a dental radiography dataset
- parsing XML annotation files
- extracting cavity-related labels
- preprocessing X-ray images
- preparing data for machine learning
- applying regression and classification models
- setting up train/test split and evaluation steps

## Objectives

This project focuses on two main prediction tasks:

- **Regression:** estimating cavity-related numeric information from annotated samples
- **Classification:** identifying whether a cavity is present or not

By combining both approaches, the project demonstrates how dental X-ray data can be used in different supervised learning scenarios.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow
- XML parsing
- Jupyter Notebook / Google Colab

## Machine Learning Methods

The project experiments with several supervised learning methods, including:

- Linear Regression
- Logistic Regression
- Random Forest Classifier
- Support Vector Classifier (SVC)
- Cross-validation techniques

## Dataset & Preprocessing

The dataset is based on annotated dental radiography images. Image annotations are parsed from XML files, and cavity labels are extracted for both regression and classification tasks.

Preprocessing steps include:

- converting images to grayscale
- resizing images
- normalizing pixel values
- flattening image arrays for model input
