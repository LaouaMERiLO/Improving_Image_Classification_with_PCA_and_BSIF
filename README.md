# Improving_Image_Classification_with_PCA_and_BSIF

This repository demonstrates an image classification pipeline enhanced by combining Principal Component Analysis (PCA) and Binary Similarity-based Image Features (BSIF) techniques. The goal is to improve the classification results by reducing overfitting through PCA and enhancing the model's ability to distinguish between classes using texture information extracted by BSIF. we conducted a comparative study using two other popular classifiers: k-Nearest Neighbors (KNN) and Artificial Neural Network (ANN).


## Components

### PCA Dimensionality Reduction:

- PCA is applied to the dataset to reduce dimensionality and mitigate overfitting.
- The reduced data is used to train a neural network for image classification.

### BSIF Texture Descriptor:

- The BSIF descriptor extracts texture patterns from images.
- The extracted features are integrated into the classification pipeline for improved discrimination.

### Classifier Training:

-Neural network model is trained on PCA and BSIF-enhanced data, and KNN classifier is trained on BSIF-enhanced data for comparison.

### Classification and Evaluation:

- The trained models are used to classify images.
- Model performance and accuracy are evaluated and can be visualized.


## Dependencies

- Python 3.x
- NumPy
- OpenCV (cv2)
- TensorFlow
- Scikit-learn
