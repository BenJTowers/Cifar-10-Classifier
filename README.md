CIFAR-10 Image Classification
A deep learning project to classify images from the CIFAR-10 dataset using PyTorch.

Project Overview
This project implements and improves a Convolutional Neural Network (CNN) to classify images into 10 categories:
✈️ Airplane, 🚗 Automobile, 🐦 Bird, 🐱 Cat, 🦁 Deer, 🐶 Dog, 🐸 Frog, 🐴 Horse, 🛳️ Ship, 🛵 Truck.

The goal is to iteratively enhance model performance, targeting 88% test accuracy.

Implemented Features
✔ Data Preprocessing & Augmentation – Normalization, random cropping, rotation, and flipping for better generalization.
✔ Deep CNN Architecture – Increasing depth with Batch Normalization and Dropout for stability and regularization.
✔ Improved Training Pipeline – Optimized training loop with a learning rate scheduler and best model checkpointing.
✔ Performance Analysis – Comparison of multiple models, analyzing overfitting and generalization trends.

Results & Performance
📈 Final Model Accuracy: 88% on the CIFAR-10 test dataset.
📊 Training Loss & Accuracy Trends: Significant improvements through deeper architectures & learning rate scheduling.

Future Improvements
🔹 Experiment with ResNet-style skip connections
🔹 Further optimize hyperparameters for faster convergence
🔹 Explore Transfer Learning for even higher accuracy
