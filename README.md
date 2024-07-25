# Lung Disease Detection Using Neural Networks


The aim of the project is to develop a system based on neural networks that can automatically detect abnormalities in lung X-ray (RTG) images. Such a system can significantly assist radiologists and doctors in diagnosing lung diseases.

1. Preliminary image processing.
2. Selection of an appropriate neural network architecture.
  Reference model: simple neural network, three dense layers
  Target model: convolutional network
3. Training the chosen neural network and evaluating the model's performance.
4. Results and conclusions.

Dataset: Lungs Disease Dataset (4 types)
Source: https://www.kaggle.com/datasets/omkarmanohardalvi/lungs-disease-dataset4-types


Evaluation Method: F1-score

Hyperparameter Tuning: Manual tuning (filter size)

Regularization: Early Stopping, Dropout layer

The data set for one class was increased so that the number of observations in each class is equal to 1000.

Conclusions:
The model with smaller kernels performed better. Its calculation time was lower, and it was mathematically simpler. Both models performed better than the reference model. The best model achieved 82% accuracy and performed best at classifying tuberculosis, but had the worst performance classifying viral pneumonia. 
