Exoplanet Detection Neural Network:
This project uses TensorFlow and Scikit-learn to build a deep learning model capable of classifying 
potential exoplanet signals using NASA Kepler telescope datasets. The project includes preprocessing, 
feature scaling, class balancing, neural network training, evaluation metrics, and visualization of 
model performance. 

The project includes:
-Data preprocessing and feature scaling
-Handling imbalanced datasets using class weighting
-Neural network training with TensorFlow/Keras
-Model evaluation using accuracy metrics and confusion matrices
-Visualization of training performance and prediction results
  
Technologies:
-Python
-TensorFlow / Keras
-Scikit-learn
-Pandas
-NumPy
-Matplotlib
-Seaborn

Features:
-Standardized input data using 'StandardScaler'
-Built a multi-layer neural network with:
  -Dense layers
  -Dropout regularization
  -Batch normalization
-Used early stopping to reduce overfitting
-Applied class weighting to improve performance on imbalanced data
-Visualized:
  -Training accuracy
  -Validation accuracy
  -Loss curves
  -Confusion matrix

Results:
The model was trained to classify exoplanet signals using neural network-based binary classification techniques. 
Performance was evaluated using:
Accuracy score
Classification report
Confusion matrix
Validation metrics

Dataset:
This project uses the NASA Kepler Exoplanet Search Dataset.
Dataset source:
Kaggle Exoplanet Search Dataset: https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data

How to run:
Download the following files and place them in the project root directory:
ExoTrain.csv and ExoTest.csv
