Deep Learning Fashion Image Classification
Overview

This project demonstrates a simple Deep Learning image classification system using TensorFlow/Keras and the Fashion MNIST dataset.

The project is designed as a practical for BBA AI/ML students and connects a Deep Learning model with a real-world e-commerce business use case.

The model takes a fashion product image as input and predicts its category, such as T-shirt/Top, Trouser, Dress, Sneaker, Bag, or Ankle Boot.

Business Problem

In a fashion e-commerce company, thousands of product images may need to be categorized before products are added to a website.

Traditional Process

Product Image → Manual Category Selection → Product Added to Website

AI-Assisted Process

Product Image → Deep Learning Model → Predicted Category → Human Review if Required → Product Added

This can help reduce repetitive manual work and make product categorization more consistent.

Dataset

The project uses the Fashion MNIST dataset, which contains images of common fashion products.

The 10 categories are:

T-shirt/Top
Trouser
Pullover
Dress
Coat
Sandal
Shirt
Sneaker
Bag
Ankle Boot
Technologies Used
Python
TensorFlow / Keras
NumPy
Matplotlib
Google Colab
Fashion MNIST
Model Architecture

The project uses a simple Artificial Neural Network (ANN):

Input Image → Flatten → Dense Hidden Layer → Output Layer

Components
Flatten: Prepares the 28×28 image for the neural network.
Dense(64): Hidden layer with 64 neurons.
ReLU: Activation function used in the hidden layer.
Dense(10): Output layer with 10 outputs.
Softmax: Produces probabilities for the 10 product categories.
Workflow
Import required libraries
Load the Fashion MNIST dataset
Define product categories
Visualize product images
Normalize image pixels
Create the neural network
Compile the model
Train the model
Test model accuracy
Predict product categories
Compare predicted and actual categories
Connect the model to the e-commerce business use case

The images are normalized from 0–255 to 0–1 before training.

Training

The model is trained for 3 epochs with a validation split of 10%, keeping the practical suitable for a classroom demonstration.

Business Benefits

Possible benefits for an e-commerce company include:

Faster product listing
Reduced repetitive manual work
More consistent product categorization
Better product-search experience
Ability to process larger numbers of images
Model Evaluation

The model is tested on images that were not used during training. Test accuracy is calculated to measure classification performance. The exact result may vary when the notebook is executed.

Accuracy should not be the only consideration before deployment. Factors such as incorrect classification costs, customer experience, training-data quality, and human review should also be considered.

Limitations
The model can make incorrect predictions.
Fashion MNIST images are simpler than real-world e-commerce product photographs.
The project uses a basic neural network for demonstration.
Only 3 training epochs are used.
Human review may still be required.

The practical specifically highlights that model predictions are not always correct and that businesses should consider accuracy, risk, and human oversight.

Future Scope

The project can be extended by:

Using real-world fashion images
Implementing Convolutional Neural Networks (CNNs)
Using data augmentation
Improving model accuracy
Adding confidence thresholds
Integrating the model with an e-commerce platform
Using human review for low-confidence predictions
Repository Structure
Deep-Learning-Fashion-Classification/
│
├── Deep_Learning_Fashion_Image_Classification_BBA.ipynb
├── README.md
│
└── screenshots/
    └── prediction.png

The practical recommends including a screenshot showing the product image, predicted category, and actual category along with the notebook.

Learning Outcomes

This project demonstrates:

Basic Deep Learning concepts
Artificial Neural Networks
Image classification
Model training and testing
Accuracy evaluation
AI-based business problem solving
Business applications of Deep Learning
Importance of human oversight
Author

Arush doomra
BBA FinTech
Chitkara University
