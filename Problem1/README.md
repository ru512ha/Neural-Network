Objective:
To build a Convolutional Neural Network (CNN) model that classifies chest X-ray images into:

Pneumonia
Normal


Dataset:
Total images: 5,863
Categories: 2 (Pneumonia, Normal)
Data Distribution:
Training: 5,216 images
Validation: 16 images
Testing: 624 images


Approach:
A CNN-based deep learning model is used to automatically extract features from X-ray images and perform binary classification.


Methodology:
Data Preprocessing:
Images resized to 150×150 pixels
Pixel values normalized (0–1)
Data augmentation applied:Zoom
Shear
Horizontal flip


Model Architecture:
3 Convolutional Layers (ReLU activation)
3 MaxPooling Layers
Flatten Layer
Dense Layer (128 neurons)
Dropout Layer (0.5)
Output Layer (Sigmoid)

Training Configuration:
Optimizer: Adam
Loss Function: Binary Crossentropy
Epochs: 10


Results:
Final Performance:
Test Accuracy: 0.875 (87.5%)
Test Loss: 0.4015
🔹 Model Complexity:
Total Parameters: 4,828,481
Trainable Parameters: 4,828,481
Non-trainable Parameters: 0


Training Insights:
Training accuracy steadily improved:From 82% → 94%
Validation accuracy fluctuated between:62% – 93%

Findings:
The CNN successfully learned features from medical images.
Achieved strong test accuracy of 87.5%, showing good generalization.
However:Very small validation set (only 16 images) caused unstable validation results.
overfitting is observed due to gap between training and validation performance.
