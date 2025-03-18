Hello! 
This project implements a simple deep learning model using TensorFlow's Sequential API to classify breast cancer as malignant or benign. The dataset used is the breast_cancer dataset from sklearn.datasets.
The dataset contains features derived from digitized images of fine-needle aspirate (FNA) of breast masses. The goal is to classify tumors as malignant or benign based on these features.

Load Dataset: Import breast_cancer data using sklearn.datasets.

Preprocessing:
Split data into training and testing sets using train_test_split.

Normalize features using StandardScaler.

Build Model:
A Sequential model with multiple Dense layers.

Activation functions: ReLU for hidden layers, sigmoid for binary classification.

Compile Model:
Loss: binary_crossentropy (since it's a binary classification problem).

Optimizer: adam.
Metrics: accuracy.

Train Model: Train the model on training data and validate it using the test set.
Evaluate Model: Measure accuracy and loss.
