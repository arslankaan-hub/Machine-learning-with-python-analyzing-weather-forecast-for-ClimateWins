Project Summary
This project focuses on analysing long-term weather patterns across Europe to evaluate how machine learning can support climate forecasting and daily weather classification for ClimateWins, a European nonprofit organisation. Using more than a century of historical observations collected from 18 official weather stations, the analysis examines temperature trends, atmospheric conditions, seasonal behaviours and the likelihood of favourable or hazardous weather events. While extensive research exists on climate modelling, this project emphasises building a structured machine-learning workflow and developing a clear, presentation-ready assessment of algorithm performance.

Through exploratory data analysis, supervised learning methods (k-Nearest Neighbours, Decision Trees and Artificial Neural Networks), gradient-descent optimisation and pattern evaluation, the project identifies which models best capture nonlinear climate dynamics and provide reliable predictions. The findings highlight regional variability, data-quality issues (such as single-class stations) and model-specific strengths and limitations, leading to evidence-based recommendations for future analysis.

By addressing key questions such as whether long-term climate signals can be detected, how accurately pleasant-weather days can be classified and how hazard-risk probabilities can be estimated, the project delivers insight for strategic climate planning, forecasting improvements and future machine-learning development.

Key Questions

Can machine learning detect early indicators of long-term climate change using historical temperature and precipitation patterns?

How accurately can models classify daily conditions as pleasant or unpleasant across different European stations?

Can machine learning estimate the probability of hazardous weather events such as storms, heatwaves or sudden temperature drops?

Which supervised learning algorithms provide the most reliable performance on multivariate climate data?

How do regional, seasonal and station-level differences influence model accuracy and generalisation?

What impact do data biases, station inconsistencies and feature distributions have on predictive outcomes?

Folders
01 Project Management – Contains the project brief and all planning documents.
02 Data – Includes datasets sourced from the European Climate Assessment & Dataset project:

Original Data: Raw CSV files with long-term daily weather measurements.

Prepared Data: Cleaned, merged and structured datasets ready for modelling.
03 Scripts – Jupyter Notebooks used for:

Data preparation and preprocessing

Gradient-descent optimisation

Supervised learning (KNN, Decision Tree, ANN)

Accuracy evaluation and station-level comparison
04 Analysis – Contains saved visualisations, optimisation plots, accuracy tables, confusion matrices and model-comparison charts.
05 Presentation – Final slides summarising findings, biases, model performance and next steps.

Code Overview

pandas – Data cleaning, merging and transformation.

numpy – Numerical operations and feature handling.

matplotlib – Visualisation of temperature trends, optimisation curves and model outputs.

seaborn – Statistical plots and feature-relationship analysis.

scikit-learn – Classification algorithms (KNN, Decision Tree, ANN).

TensorFlow / Keras (if used) – Neural network construction and optimisation.

json / geopandas (optional) – For spatial or station-mapping extensions.

Disclaimer
This dataset was sourced from the European Climate Assessment & Dataset (ECA&D) project and used for educational and analytical purposes as part of the CareerFoundry Data Analytics Program.
