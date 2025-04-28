Pneumonia Detection from Chest X-rays using Deep Learning
Project Overview

This project was developed as part of the "AI in Healthcare" course at The University of Texas at Austin.
The goal is to automate pneumonia detection from chest X-ray images using a custom Convolutional Neural Network (CNN).
Dataset

    Source: Kaggle Chest X-ray Pneumonia Dataset

    Details:

        5,216 labeled images (Normal and Pneumonia cases)

        Train/Validation/Test splits provided

Methodology

    Preprocessing:

        Images resized to 150x150 pixels

        Pixel normalization

        Data augmentation (rotation, flipping)

    Model Architecture:

        3 Convolutional layers with MaxPooling

        1 Dense layer with Dropout

        Final output layer with Sigmoid activation

    Training Details:

        Loss Function: Binary Cross-Entropy

        Optimizer: Adam

        Metric: Accuracy

Results

    Training Accuracy: 94%

    Validation Accuracy: 87.5%

    Test Accuracy: 91%

    Confusion Matrix:

        True Positive: 380

        True Negative: 186

        False Positive: 48

        False Negative: 10

    Classification Report:

        Precision: 92%

        Recall: 88%

        F1 Score: 90%

How to Run

    Open the Colab notebook: Colab Link

    Follow the steps to load data, preprocess images, build the CNN, and train the model.

    Evaluate the model on the test set.

Future Work

    Fine-tuning with pre-trained models like ResNet or DenseNet

    Expand validation/testing on external datasets

    Integrate explainability tools like Grad-CAM for model interpretation

Author

Himani Bali
University of Texas at Austin | AI in Healthcare - Spring 2025
