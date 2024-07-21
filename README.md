# Breast Cancer Classification with PyTorch

This project implements a simple neural network using PyTorch to classify breast cancer tumors as malignant or benign. The model is trained and evaluated on the Wisconsin Breast Cancer Dataset.

## Project Structure

- **BreastCancerNN.ipynb:** Jupyter Notebook containing the code for data preprocessing, model definition, training, and evaluation.
- **README.md:** This file, providing an overview of the project.

## Dataset

The Wisconsin Breast Cancer Dataset is used for this project. It consists of features computed from digitized images of fine needle aspirates of breast mass. The features describe characteristics of the cell nuclei present in the images.

## Model

The neural network model consists of:

- An input layer with 30 neurons (corresponding to the 30 features in the dataset).
- A hidden layer with 64 neurons and ReLU activation.
- An output layer with 1 neuron and sigmoid activation for binary classification.

## Dependencies

- Python 3.x
- PyTorch
- scikit-learn

## How to Run

1. Open the `BreastCancerNN.ipynb` notebook in Google Colab.
2. Execute the cells in the notebook sequentially.
3. The notebook will output the training progress and final test accuracy.

## Results

The model achieves a test accuracy of 96.4912%.

## Future Improvements

- Experiment with different network architectures (e.g., more hidden layers, different activation functions).
- Hyperparameter tuning to optimize learning rate, batch size, etc.
- Implement cross-validation for more robust evaluation.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests.
