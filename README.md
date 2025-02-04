# MSW-Slope-Shear-Modulus-Prediction-using-ML-and-XAI-techniques
This repository contains the code and the dataset for the prediction of shear modulus of the MSW waste using a serries of ML algorithms along with XAI techniques.
Predicting Shear Modulus of Municipal Solid Waste (MSW)
Overview

This repository contains a dataset and code to predict the shear modulus (G) of Municipal Solid Waste (MSW) using boosting-based ensemble machine learning algorithms combined with explainable AI techniques. The study addresses the challenges of traditional MSW testing, such as unpleasant odors, degradation, and the high cost of laboratory experiments, by providing a reliable and efficient predictive modeling framework.
Dataset

The current work utilizes the cyclic triaxial test data of 153 samples of MSW. The dataset was originally reported by (Alidoust, Keramati, et al., 2021) and the samples were collected from an MSW dumpside at Kahrizak, Iran. 

The dataset includes 153 data points collected from the literature, with the following features:

    No.: Data point index
    ShS: Shear strain (%)
    Age: Age of MSW (years)
    POP: Plastic content (%)
    CP: Confining pressure (kPa)
    UW: Unit weight of MSW (kN/m³)
    F: Loading frequency (Hz)
    G: Shear modulus (kPa) (target variable)

Methodology

    Objective: To predict the dynamic shear modulus (G) of MSW using ensemble learning techniques.
    Algorithms: Six boosting-based ensemble models (e.g., XGBoost, LightGBM) were developed and assessed for predictive performance.
    Feature Importance: Explainable AI methods, such as SHAP (SHapley Additive exPlanations), were used to analyze the contribution of each input feature to the predictions.
    Sensitivity Analysis: A parametric sensitivity analysis was conducted to evaluate the influence of key features on the shear modulus.

Key Findings

    Superior Model Performance: One of the ensemble models achieved the best performance, with high R2R2 values for both training and testing data.
    Feature Contributions: Sensitivity analysis highlighted the significant impact of shear strain, unit weight, and plastic content on the shear modulus predictions.
    Model Explainability: Explainable AI techniques provided transparent insights into the influence of input features, enhancing trust in the predictive framework.

Applications

This work provides an efficient and interpretable tool for estimating the shear modulus of MSW, enabling practitioners to save time and resources while accurately assessing MSW's dynamic properties across different sites.
Repository Structure

    data/: Contains the dataset used in this study.
    models/: Includes scripts to train, evaluate, and explain the ensemble models.
    plots/: Visualizations of feature importance and sensitivity analysis.
    README.md: Project description and methodology.

Citation

If you use this dataset or code, please cite this work as follows:

    "Predicting Shear Modulus of Municipal Solid Waste Using Ensemble Machine Learning and Explainable AI."
