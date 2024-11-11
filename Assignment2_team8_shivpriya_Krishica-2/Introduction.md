# SVM and Decision Tree Comparison on LES Dataset

## Overview
This repository contains an analysis comparing Support Vector Machine (SVM) and Decision Tree models applied to the LES dataset. The project is structured into two main parts:
- **Part 1:** SVM Lab Exercises
- **Part 2:** Application of SVM and Decision Tree Models on the LES Dataset

Each section emphasizes building a strong understanding of model functionality, performance comparison, and model handling of different data types.

## Repository Structure
- `Assignment2_Part1_Team8_Shivpriya_Krishica.ipynb`: Notebook for Part 1, focused on SVM labs, with step-by-step code execution and analysis.
- `Assignment-2_Part2_Krishica_Shivpriya.ipynb`: Primary notebook for Part 2, applying SVM and Decision Tree models to the LES dataset.
- `Assignment2_Part2_AlternateApproach.ipynb`: An alternate approach for Part 2, offering additional insights or methods.

## Part 1: SVM Lab Exercises
This part aims to build a foundational understanding of SVM:
1. **Notebook Structure:** Rather than running all cells in a single notebook, each section from `ml-svm-2.ipynb` is copied into a new blank notebook and executed step-by-step.
2. **Code Analysis:** Each section of code is examined to understand its functionality and logic, with particular attention to how SVM handles data.
3. **SVM Concepts:** Key concepts explored include hyperplane selection, margin maximization, and kernel applications.

## Part 2: SVM and Decision Tree on LES Dataset

### Dataset and Label Selection
- **Label Selection:** A feature (column) from the dataset is chosen as the label based on its predictability. The label is quantized if necessary.
- **Prediction Task:** The objective is to predict the quantized label using one or more of the other features in the dataset.

### Modeling and Comparison
1. **Decision Tree Model:** A Decision Tree model is trained on the selected features and label.
2. **SVM Model:** An SVM model is also trained using the same data.
3. **Performance Comparison:** Both models are evaluated and compared in terms of performance metrics, interpretability, and generalization capabilities. The strengths and limitations of each model in handling the dataset are analyzed.

### Key Insights
- **Performance Differences:** Comparison of the SVM and Decision Tree models in terms of accuracy, complexity, and generalization.
- **Interpretability:** Assessment of how each model provides insights into data patterns and label predictability.
- **Generalization:** Evaluation of each model’s ability to generalize from the training data to unseen data.

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
3. Open and execute the notebooks in a Jupyter Notebook environment.

## Results
The findings from this project include performance metrics and a qualitative analysis of each model's capabilities. The SVM model’s approach to margin maximization and kernel tricks is contrasted with the Decision Tree’s hierarchical feature-splitting method.

