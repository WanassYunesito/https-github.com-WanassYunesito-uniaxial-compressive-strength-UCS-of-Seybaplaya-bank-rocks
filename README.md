Deep Learning Neural Network for Statistical Modeling of Compressive Strength in Seybaplaya Bank Rocks
This repository contains MATLAB scripts and experimental data for the project entitled:

“Deep Learning Neural Network for Statistical Modeling of Compressive Strength in Seybaplaya Bank Rocks: A Multivariate Analysis Incorporating Water Content, Porosity, and Density Parameters”.

Table of Contents
Introduction
Repository Structure
MATLAB Version & Toolboxes
Usage
Data Description
Model Details
Results
License
Contact

Introduction

Rock compressive strength plays a pivotal role in geological and civil engineering projects. This research leverages a deep learning approach to model and predict uniaxial compressive strength (UCS) in Seybaplaya bank rocks based on water content, porosity, and density. By combining laboratory-derived datasets with MATLAB’s deep learning functions, we aim to accurately forecast UCS and identify influential parameters.

MATLAB Version & Toolboxes
MATLAB Release: R2024b (or whichever you used)
Required Toolboxes:
Deep Learning Toolbox
Statistics and Machine Learning Toolbox
Parallel Computing Toolbox for GPU acceleration
Before running the scripts, ensure you have the correct MATLAB version and the toolboxes listed above installed.

Usage
Clone or Download the Repository
git clone https://github.com/<WanassYunesito>/<https-github.com-WanassYunesito-uniaxial-compressive-strength-UCS-of-Seybaplaya-bank-rocks“ into following link: https://github.com/WanassYunesito/https-github.com-WanassYunesito-uniaxial-compressive-strength-UCS-of-Seybaplaya-bank-rocks>.git
cd (change directory) <https://github.com/WanassYunesito/https-github.com-WanassYunesito-uniaxial-compressive-strength-UCS-of-Seybaplaya-bank-rocks>

Open MATLAB and navigate to the cloned folder:
cd('<https://github.com/uniaxial-compressive-strength-UCS-of-Seybaplaya-bank-rocks>');[Codes_UCS_rocks.zip](https://github.com/user-attachments/files/18466349/Codes_UCS_rocks.zip)


Data Preprocessing
Run the preprocess_data.m script to clean the dataset, handle missing values, and apply any scaling or normalization if needed:

preprocess_data


Model Training
Train the neural network by running:

train_model

This script loads the preprocessed data, defines the deep learning architecture, and trains the network.

Note: Adjust the hyperparameters in the script as desired as number of layers, neurons, epochs.

Model Evaluation

Evaluate performance with: evaluate_model

This script applies the trained model to a test set and computes metrics such as RMSE, MAE, and R². It may also generate plots (e.g., predicted vs. actual UCS).

Data Description
Seybaplaya_Rocks.csv
water_content (fraction or percentage)
porosity (fraction or percentage)
density (g/cm³ or relevant unit)
ucs (Uniaxial Compressive Strength, in MPa)
The data were collected under standardized conditions to ensure reliability. Each row corresponds to an individual rock sample, annotated with measured property values and UCS.

Model Details
Neural Network Architecture:

Defined in train_model.m (e.g., a feed-forward network using MATLAB’s Layer Graph or fitnet for regression tasks).
Example layers: Fully connected (dense) layers + ReLU or other activation functions, culminating in a regression output layer.
Hyperparameters:

Learning Rate
Number of Hidden Layers / Neurons
Batch Size
Epochs
Edit these parameters within the MATLAB scripts to optimize performance based on your dataset.

Results
Model Performance:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Coefficient of Determination (R²)
Visualization:

Plots showing training and validation losses over epochs
Comparison of Predicted vs. Actual UCS
All generated figures can be found in the results/figures folder (if you save them automatically in the scripts). Numerical metrics or logs may also be stored in results/metrics.

License
If you plan to make your code open-source or have specific usage restrictions, include a license (Matlab academic). Create a file named LICENSE with your license text.

Contact
For questions or suggestions, you can reach out via:

Email: eyouness@pampano.unacar.mx
GitHub Issues: Open an Issue


Disclaimer: This project is for research purposes. The authors assume no liability for any direct or indirect use of this code or data. Please cite appropriately if you use any portion of this repository in your own work. Please!

[Codes_UCS_rocks.zip](https://github.com/user-attachments/files/18466276/Codes_UCS_rocks.zip)

