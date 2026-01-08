## Description

This repository contains a neural network project built with TensorFlow Keras, focused on classifying clothing items from the Fashion-MNIST dataset.

The goal of the assignment was to design a custom MLP architecture and achieve at least 91% validation accuracy.
To reach this target, multiple experiments were conducted, testing different hyperparameters and regularization techniques such as varying the number of layers, activation functions, dropout, L2 regularization, batch size, etc.

## Technologies

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Pandas**
- **scikit-learn (classification report)**
- **Jupyter Notebook**

## Functionality

The project includes:
- **Data loading & preprocessing**
   - Load Fashion-MNIST dataset
   - Visualization of sample images
   - Normalization of pixel values
- **Custom MLP builder**
   - A function that dynamically creates MLP architectures with configurable:
     - number of units per layer
     - dropout rate
     - L2 regularization
     - activation functions (ReLU, Softmax)
- **Experiment configuration**
   - Multiple experiments tested different hyperparameters
   - Each experiment:
     - builds its own model
     - trains with validation split
     - stores history, model, and best validation accuracy
- **Training & evaluation**
   - Automatic early stopping
   - Tracking accuracy/loss
   - Best model selection per experiment
   - Collection of validation accuracy scores

## Links

- **GitHub Repository:**
  
https://github.com/OAtamanchuk/goit-ds-hw-12
