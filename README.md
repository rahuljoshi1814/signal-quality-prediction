# signal-quality-prediction
This project involves building and evaluating a deep learning model to predict the signal quality of communications equipment based on various signal parameters.The dataset contains various signal parameters collected from multiple signal tests, with the target variable being the signal strength.

## Project Overview
In this project, building and evaluate a deep learning model to predict the signal strength of communication equipment. The project includes the following key steps:

- Data Import and Understanding: explore the dataset to understand its structure, features, and target variable.
- Data Preprocessing: The data is preprocessed by splitting it into features (X) and target variable (Y), followed by splitting it into training and testing sets, - normalizing the features, and encoding the target variable for neural network compatibility.
- Model Design and Training: A neural network model is designed and trained on the preprocessed data.and then experiment with different architectures to improve model performance.
- Model Evaluation: The trained models are evaluated on the test set, and the results are visualized using training and validation loss/accuracy plots.
- Performance Improvement: updation of the model architecture to enhance performance and compare the results with the initial model.

## Installation
- pip install tensorflow keras pandas numpy scikit-learn matplotlib

## Usage
- Clone the Repository:
- Prepare the Dataset: Ensure the dataset is named appropriately as expected by the code.
- Run the Project:

## Results
- The results include the model's performance on the test set, displayed as:
    - Initial Model: The test accuracy and loss of the initial neural network architecture.
    - Updated Model: The test accuracy and loss of the updated neural network architecture.

- Visualizations include:
  - Training and Validation Loss: A plot showing the loss during training and validation.
  - Training and Validation Accuracy: A plot showing the accuracy during training and validation.
 
The project successfully demonstrates the use of deep learning to predict the signal quality of communication equipment. The updated model shows improved performance over the initial architecture, with higher test accuracy and better generalization.
