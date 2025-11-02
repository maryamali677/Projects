
Arabic Handwritten Classification
Overview
This project aims to classify handwritten Arabic characters using a wide dataset. The dataset contains 16,800 images of handwritten Arabic characters, making it an excellent resource for developing and testing deep learning models in handwriting recognition.

Dataset
The dataset utilized in this project was obtained from  https://www.kaggle.com/datasets/mloey1/ahcd1
Database that contains 16800 handwritten Arabic characters

Methodology/techniques
Data Visualization: to understand data 
Data Cleaning: identifying missing values.
One-Hot Encoding: to convert categorical variables into a numerical format
Model Training
Cross-validation

The model used the Convolutional Neural Network (CNN), which consists of:
Convolutional Layer 1:
32 filters
Kernel size: (3, 3)
Activation: ReLU
Convolutional Layer 2:
64 filters
Kernel size: (3, 3)
Activation: ReLU
Convolutional Layer 3:
64 filters
Kernel size: (3, 3)
Activation: ReLU
Additional Layers

Max Pooling Layers after each convolutional layer to reduce dimensionality.
Flatten Layer to convert 3D outputs to 1D.
Fully Connected Layer with 128 units and ReLU activation.
Dropout Layer with a rate of 0.5 to prevent overfitting.
Output Layer with softmax activation for multi-class classification.

After training the Convolutional Neural Network (CNN) for 10 epochs, the model achieved a training accuracy of 82.45% and a loss of 0.5388. The validation accuracy was 85.97% with a validation loss of 0.4634. Most notably, the test accuracy reached 85.51%, indicating that the model generalizes well to unseen data and effectively classifies handwritten Arabic characters.
After using 5-fold cross-validation, the model achieved an average accuracy of 76.3%
