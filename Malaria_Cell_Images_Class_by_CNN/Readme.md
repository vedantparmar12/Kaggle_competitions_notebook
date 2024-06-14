Project Overview

This project focuses on classifying Malaria cell images into two categories: "Parasitized" (0) and "Uninfected" (1). The goal is to develop an accurate model that can assist in the diagnosis of Malaria by automating the process of identifying infected cells.

Dataset

The project utilizes the Malaria Cell Images Dataset available on Kaggle. This dataset contains a collection of microscopic images of red blood cells, some of which are infected with the malaria parasite.

Model Architecture

The chosen model architecture for this project is LeNet-5, a classic convolutional neural network architecture designed for image classification tasks. LeNet-5 is known for its simplicity and efficiency, making it a suitable choice for this project.

Training

The model is trained on the Malaria Cell Images Dataset using PyTorch. The training process involves:

Data Preprocessing: Images are resized, normalized, and transformed to tensors for input into the model.
Model Definition: The LeNet-5 architecture is implemented using PyTorch layers.
Loss Function: Cross-entropy loss is used to measure the difference between predicted and actual labels.
Optimizer: The Adam optimizer is employed to update model parameters during training.
Training Loop: The model is trained for multiple epochs, with batches of images fed into the network.
Evaluation

The performance of the trained model is evaluated on a validation set. The key metric used for evaluation is validation accuracy, which measures the percentage of correctly classified images.

Results

The project achieved a validation accuracy of 95% using the LeNet-5 architecture. This indicates that the model performs well in distinguishing between parasitized and uninfected Malaria cells.

How to Use

Clone this repository.
Install the required dependencies (PyTorch, etc.).
Download the Malaria Cell Images Dataset from Kaggle.
Adjust the file paths in the code to match your dataset location.
Run the training script to train the model.
Use the trained model to classify new Malaria cell images.
Future Work

Potential improvements for this project include:

Exploring alternative model architectures (e.g., ResNet, VGG).
Experimenting with different data augmentation techniques.
Fine-tuning hyperparameters for better performance.
Deploying the model as a web application or mobile app.
Acknowledgments

The creators of the Malaria Cell Images Dataset.
The PyTorch community.
The authors of the LeNet-5 architecture.
Feel free to modify and expand upon this README file to include more specific details about your project, such as the hyperparameters used, training settings, and any additional insights or observations.
