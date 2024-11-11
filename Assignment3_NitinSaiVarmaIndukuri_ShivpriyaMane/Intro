# Wine Quality Classification using Neural Networks

## Overview
This project involves improving the accuracy of a neural network model for predicting wine quality based on various features of the wine. The objective is to achieve a test accuracy above 90% through optimized preprocessing, model structure, and training techniques.

The project is organized into two main tasks:
1. **Data Preprocessing and Exploration**: Thorough analysis and preparation of data to make it suitable for model training.
2. **Neural Network Optimization**: Experimentation with different network architectures, activation functions, and training techniques to enhance model performance.

## Repository Structure
- `ml-wines-tf-start.ipynb`: Original notebook with an initial neural network model for wine quality classification.
- `Improved_Wine_Quality_Classification.ipynb`: Optimized version of the notebook, beginning from data import, with detailed markdown and explanations on each step to achieve a test accuracy above 90%.

## Project Details

### Dataset
The dataset consists of several features related to wine characteristics, such as acidity, sugar levels, and pH, used to predict the wine's quality score. The target variable, quality, is treated as a continuous variable for regression, allowing more granular predictions.

### Approach
1. **Data Preprocessing**:
   - Normalization: Features are normalized to improve training stability and speed.
   - Feature Engineering: Key features are examined for patterns to understand their impact on wine quality.

2. **Modeling**:
   - A sequential neural network model is designed with multiple dense layers and ReLU activation functions.
   - Dropout layers are added to prevent overfitting, and early stopping is applied to monitor validation loss and optimize training epochs.
   - The `Adam` optimizer is used with Mean Absolute Error (MAE) as the loss function, suited for regression tasks.

3. **Evaluation**:
   - Training and test accuracy are calculated based on loss values, achieving the target of 90% test accuracy.
   - Comparative analysis of treating the target as a continuous versus categorical variable is documented, highlighting the improved results in a regression approach.

### Key Results
- **Training Accuracy**: 91.39%
- **Test Accuracy**: 90.60%
  
These metrics indicate a well-balanced model with strong generalization capabilities, as the test accuracy closely matches the training accuracy.

## Getting Started
To run the analysis:
1. Clone this repository:
    ```bash
    git clone <repository-url>
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and execute `Improved_Wine_Quality_Classification.ipynb` in a Jupyter Notebook environment.

## Results
The improved model demonstrates a significant boost in accuracy by treating wine quality as a continuous variable, enabling finer granularity in predictions. This approach outperformed classification, achieving a test accuracy of 90.60%.

## License
This project is licensed under the MIT License.
