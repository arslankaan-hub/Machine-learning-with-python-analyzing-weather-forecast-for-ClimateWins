# Project Summary

This project analyzes long-term European weather data to evaluate how machine learning can support climate forecasting and daily weather classification. Using historical observations from 18 European weather stations, the analysis investigates temperature trends, atmospheric conditions, seasonal patterns and the likelihood of favourable or hazardous weather events.

Through exploratory data analysis, gradient-descent optimisation and supervised machine learning models, the project identifies which algorithms perform best when classifying daily conditions and detecting climate-related patterns. The findings provide insights into regional variability, model reliability and data-quality limitations.

By addressing key questions such as how accurately weather can be classified, whether climate-shift indicators can be detected and which models generalize best across stations, the analysis supports future forecasting strategies and further research.

## Key Questions

-Can machine learning detect early indicators of long-term climate change?

-How accurately can daily weather be classified as pleasant or unpleasant?

-Can hazardous-weather probabilities be estimated from multivariate data?

-Which supervised learning algorithms perform best on this dataset?

## Folders

*01 Project Management* – Contains the project brief.

*02 Data* – ( Data is not uploaded due to size issues) Includes:

'Original Data': Raw CSV climate datasets from ECA&D.

'Prepared Data': Cleaned and merged datasets ready for analysis.

*03 Scripts* – Jupyter Notebooks with code for each stage of the analysis:

-Data Preparation & Cleaning

-Gradient Descent Optimisation

-KNN Classification

-Decision Tree Classification

-Artificial Neural Network Model

-Model Evaluation

*05 Sent to Client*

-Powerpoint presentation of project

# Code Overview

**pandas** – Data loading, cleaning and manipulation

**numpy** – Numerical computations and array operations

**seaborn** – Statistical visualisations

**matplotlib.pyplot** – Plotting loss curves, accuracy charts and confusion matrices

**os / operator** – File handling and utility functions

**scipy** – Scientific operations used in preprocessing or calculations

**scikit-learn modules used**

**datasets** – Importing sample structures when needed

**metrics** – Accuracy scoring and evaluation

**multilabel_confusion_matrix, confusion_matrix, ConfusionMatrixDisplay – Model performance assessment**

**accuracy_score** – Classification accuracy measurement

**KNeighborsClassifier** – k-Nearest Neighbour model

**DecisionTreeClassifier** – Decision Tree model

**MultiOutputClassifier** – Handling multi-output targets

**train_test_split, cross_val_score – Model validation tools**

**figure** – Plot structure and layout control

# Disclaimer

This dataset was sourced for educational purposes as part of the CareerFoundry Data Analytics Program using publicly available data from the European Climate Assessment & Dataset (ECA&D) project.
