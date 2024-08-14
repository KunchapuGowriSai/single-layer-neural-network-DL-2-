Neural Network for Wine Quality Classification
This repository contains a simple implementation of a neural network to classify wine quality based on a few features. The model is trained to predict whether the quality of a wine is good (quality >= 6) or not good (quality < 6) using the Wine Quality dataset.

Dataset
The dataset used in this project is the Wine Quality dataset, which can be found on the UCI Machine Learning Repository. In this implementation, only a subset of the features from the dataset is used for training the neural network.

Features Selected:

Fixed Acidity
Volatile Acidity
Citric Acid
Residual Sugar
Chlorides
Target:

Binary classification of wine quality:
1 for good wine (quality >= 6)
0 for not good wine (quality < 6)
Project Structure
winequality-red.csv: The dataset file.
neural_network.py: The script that contains the neural network implementation.
README.md: This file, which provides an overview of the project.
Neural Network Structure
Input Layer: 5 neurons (one for each feature).
Hidden Layer: 10 neurons.
Output Layer: 1 neuron (for binary classification).
Training Parameters
Number of Epochs: 2000
Learning Rate: 0.68
How to Run the Code
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/KunchapuGowriSai/single-layer-neural-network-DL-2-
cd wine-quality-classification
Install the necessary dependencies (if you don't have them installed already):

bash
Copy code
pip install numpy pandas matplotlib scikit-learn
Run the script:

bash
Copy code
python neural_network.py
The script will train the neural network and plot the validation loss and accuracy over the epochs.

Results
The script outputs the following during training:

Validation Loss: The mean squared error between the predicted output and the actual target.
Validation Accuracy: The proportion of correct predictions on the validation set.
Example Plots

for any enquery-mail- kunchapugowrisai143@gmail.com
Validation Loss Over Epochs
Validation Accuracy Over Epochs
These plots will be displayed after the training process.

Contributing
If you'd like to contribute to this project, feel free to submit a pull request or open an issue for discussion.
