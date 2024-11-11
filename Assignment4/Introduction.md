# Dense Network for Addition of Multi-digit Numbers

## Overview
This project explores the capabilities and limitations of a dense (fully connected) neural network in performing addition tasks. The network is trained to add two numbers of a fixed digit length and is then tested to see if it can generalize to numbers with an additional digit.

## Project Structure
- `Assignment4_Group6_Shivpriya_Lokeshwaran-3.ipynb`: Main notebook containing the dense network model implementation, training, and evaluation. It includes detailed markdown explanations on the network's performance and limitations.

## Objective
1. **Train a Dense Network for Addition**: The network is trained to perform addition on two numbers up to a specific digit length.
2. **Test Generalization**: In inference mode, the model attempts to add numbers with an extra digit, testing its generalization capability beyond the trained digit length.

## Key Findings
- **Dense Network Limitations**: When trained on numbers of a specific digit length (e.g., 3-digit numbers), the dense network struggles to generalize to a higher digit length (e.g., 4-digit numbers) due to a lack of positional and carry-over awareness.
- **Sequence Accuracy**: The model achieves high accuracy on the trained digit length but fails to correctly predict complete sequences for longer numbers, showing a significant drop in accuracy.
- **Difference Between Dense and Recurrent Networks**: Dense networks lack memory, treating each input independently, while recurrent networks (RNNs) are designed to handle sequences by retaining information over time, making them more suitable for tasks requiring positional dependencies.

## Approach
1. **Data Preparation**: Input numbers are structured to represent addition problems within a fixed digit length.
2. **Model Training**: The dense network is trained with backpropagation to minimize the prediction error for addition tasks.
3. **Generalization Test**: Inference is performed on numbers with an extra digit to test the model's ability to generalize.

## Results
- The model achieves **99.55% accuracy** on the trained 3-digit numbers but only **50.36% per-character accuracy** on 4-digit numbers.
- Sequence accuracy on 4-digit numbers is **0%**, highlighting the model's inability to fully generalize.

## Conclusion
The results show that while dense networks can learn patterns within fixed lengths, they are not well-suited for tasks requiring an understanding of sequential or positional relationships, such as addition with varying digit lengths. For such tasks, recurrent architectures (RNNs, LSTMs) or transformers are more effective due to their inherent memory and ability to handle sequences.

## Getting Started
1. Clone this repository:
    ```bash
    git clone <repository-url>
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and run the notebook `Assignment4_Group6_Shivpriya_Lokeshwaran-3.ipynb` in Jupyter to explore the dense network training and evaluation.

## License
This project is licensed under the MIT License.
