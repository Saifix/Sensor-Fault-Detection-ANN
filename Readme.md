# Neural Network for Fault Detection in Tennessee Eastman Process Simulation Dataset

## Introduction
This project presents the development of a neural network model for fault detection using the Tennessee Eastman Process Simulation dataset. The dataset comprises fault-free and faulty instances, which were utilized to train and evaluate the model.

### Steps Taken 🚀
1. **Importing Libraries**: Necessary libraries including PyReadr for reading RData files, Matplotlib for visualization, Seaborn for statistical graphics, NumPy, and Pandas for data manipulation were imported.
2. **Importing Dataset**: The fault-free and faulty training datasets were located and imported using PyReadr for reading RData files and Pandas for data manipulation.
3. **Preprocessing Dataset**: Data preprocessing involved filtering, scaling, and encoding categorical variables using StandardScaler and OneHotEncoder from scikit-learn.
4. **Preparing Neural Network**: A neural network model was constructed using Keras, comprising multiple dense layers with SELU activation functions.
5. **Training Model**: The model was trained on the preprocessed data with early stopping to prevent overfitting.
6. **Evaluating the Model**: The model's performance was evaluated using confusion matrices and accuracy scores.

## Results
- **Training Performance**: The training history depicted decreasing loss and increasing accuracy over epochs, with some fluctuations indicating effective learning.
- **Evaluation Metrics**: The confusion matrix revealed the model's ability to accurately predict fault classes, with an overall accuracy score computed.
- **Real-time Fault Prediction**: Visualization of the model's predictions for real-time fault detection demonstrated its capability to identify fault classes over time.
- **t-SNE Visualization**: Using t-SNE, the clustering performance of the model was visualized, providing insights into its ability to distinguish between fault classes.

## Conclusion
This project demonstrates the application of neural networks for fault detection in industrial processes using the Tennessee Eastman Process Simulation dataset. Through meticulous preprocessing and model construction, a reliable fault detection system with promising performance metrics was achieved.
