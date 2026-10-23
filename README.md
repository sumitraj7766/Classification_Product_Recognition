# Product Recognition and Classification Using CNN

A deep learning project that explores automated product recognition for a quick-commerce grocery catalog using Convolutional Neural Networks (CNNs) and PyTorch.

## Project Overview

The project simulates a quick-commerce catalog workflow in which incoming grocery product photographs need to be categorized automatically.

It explores image preprocessing, dataset analysis, neural network training, model evaluation, confidence-based classification, and transfer learning.

## Key Features

- Grocery product image classification
- Image preprocessing and resizing
- Data augmentation
- Fully connected neural network baseline
- Convolutional Neural Network (CNN)
- Training and validation workflow
- Test accuracy and classification metrics
- Confusion matrix analysis
- Confidence-threshold-based classification policy
- Optional ResNet-18 transfer learning
- Model saving and reloading

## Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib
- Pillow
- scikit-learn
- torchvision
- Google Colab

## Dataset

The notebook uses a dataset file named `catalog_products.npz`, containing encoded product photographs, labels, category names, and predefined dataset splits.

The dataset is based on the Grocery Store Dataset. Obtain the dataset separately and place `catalog_products.npz` in the notebook's working directory before running the data-loading cells.

## Model Architecture

The project compares different approaches to image classification, including a fully connected baseline and a CNN. It also explores transfer learning with a pretrained ResNet-18 model when pretrained weights are available.

## Model Output

The notebook saves the trained CNN checkpoint as `product_cnn.pt`. It includes the model state, category names, confidence threshold, test accuracy, and training-set size.

## How to Run

1. Open `Classification_Product_Recognition.ipynb` in Google Colab.
2. Install dependencies using `requirements.txt`.
3. Place `catalog_products.npz` in the working directory.
4. Run the notebook cells in order.
5. Review the visualizations, evaluation metrics, and saved model.

## Important Notes

- The notebook depends on the external dataset file.
- ResNet-18 transfer learning may require internet access to obtain pretrained weights.
- Actual performance depends on the dataset split, training configuration, and model results.

## Author

Sumit Kumar
