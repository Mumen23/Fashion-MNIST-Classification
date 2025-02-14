# Fashion MNIST CNN

This project trains a Convolutional Neural Network (CNN) on the Fashion MNIST dataset using both Python (TensorFlow/Keras) and R (Keras in R). The trained model classifies images into one of 10 fashion categories.

## Dataset
The dataset used is the **Fashion MNIST dataset**, which consists of 70,000 grayscale images of 28x28 pixels, categorized into 10 classes:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## Technologies Used
- Python
  - TensorFlow
  - Keras
  - NumPy
  - Matplotlib
- R
  - Keras

## Installation
### Python Dependencies
Ensure you have Python installed (preferably 3.x). Install required libraries:
```sh
pip install tensorflow numpy matplotlib
```

### R Dependencies
Ensure you have R and Keras installed:
```r
install.packages("keras")
library(keras)
```

## Model Architecture
The CNN consists of:
1. Three convolutional layers with ReLU activation.
2. Max pooling layers after each convolutional layer.
3. A fully connected dense layer with ReLU activation.
4. A final softmax layer for classification.

## Running the Scripts
### Python
Run the Python script:
```sh
python fashion_mnist_cnn.py
```

### R
Run the R script:
```r
source("fashion_mnist_cnn.r")
```

## Output
- The model is trained and evaluated on test data.
- Accuracy of the model is displayed.
- Sample predictions are visualized.
- The trained model is saved as `fashion_mnist_cnn.h5` (Python) and `fashion_mnist_cnn_r.h5` (R).



