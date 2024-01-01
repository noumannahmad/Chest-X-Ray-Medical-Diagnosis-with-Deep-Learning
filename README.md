
In this notebook we will explore medical image diagnosis by building a state-of-the-art chest X-ray classifier using Keras.

In this notebook we will walk through some of the steps of building and evaluating this deep learning classifier model. In particular, we will:

Pre-process and prepare a real-world X-ray dataset
Use transfer learning to retrain a DenseNet model for X-ray image classification
Learn a technique to handle class imbalance
Measure diagnostic performance by computing the AUC (Area Under the Curve) for the ROC (Receiver Operating Characteristic) curve
Visualize model activity using GradCAMs
Outline
Use these links to jump to specific sections !

1. Import Packages and Function
2. Load the Datasets
2.1 Preventing Data Leakage
Exercise 1 - Checking Data Leakage
2.2 Preparing Images
3. Model Development
3.1 Addressing Class Imbalance
Exercise 2 - Computing Class Frequencies
Exercise 3 - Weighted Loss
3.3 DenseNet121
4. Training [optional]
4.1 Training on the Larger Dataset
5. Prediction and Evaluation
5.1 ROC Curve and AUROC
5.2 Visualizing Learning with GradCAM
