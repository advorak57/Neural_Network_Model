# Neural_Network_Model

Alphabet Soup Funding Success Prediction
Overview
This project aims to create a binary classification model using a deep neural network to predict the success of applicants funded by Alphabet Soup, a fictitious venture capital firm.

## Deliverables
- Preprocess data for a neural network model.

- Compile and evaluate a binary classification model.

- Optimize the model.

## Instructions

## Data Preparation

- Read applicants_data.csv into a Pandas DataFrame.

- Drop "EIN" and "NAME" columns.

- Encode categorical variables using OneHotEncoder.

- Create features (X) and target (y) datasets.

- Split datasets into training and testing sets.

- Scale features data with StandardScaler.
## Model Creation and Evaluation

Design a binary classification deep neural network using TensorFlow's Keras.

Compile and fit the model with binary_crossentropy loss, adam optimizer, and accuracy metric.

Evaluate the model using test data.

## Model Optimization

- Attempt at least two optimizations to improve model accuracy.

- Save and export the optimized model to an HDF5 file named AlphabetSoup.h5.
