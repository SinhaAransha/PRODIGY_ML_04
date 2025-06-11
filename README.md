# Hand Gesture Recognition Using CNN

This project implements a Convolutional Neural Network (CNN) for real-time hand gesture recognition using image classification. The model is trained on a labeled dataset of hand gesture images and is capable of predicting the class of new input images. This system can be used for gesture-based control interfaces and intuitive human-computer interaction systems.

## Dataset

The dataset used for training and validation is publicly available on GitHub:

- Repository: [Youlenda/HandDataset](https://github.com/Youlenda/HandDataset)
- Dataset link: https://github.com/Youlenda/HandDataset
- The dataset includes two ZIP files: `trainingset.zip` and `validationset.zip`, which contain gesture images organized by class folders.

## Features

- Data preprocessing with image augmentation using `ImageDataGenerator`
- CNN model with multiple convolution and pooling layers
- Real-time prediction on custom input images
- Accuracy and validation accuracy visualization using Matplotlib

## How to Run

### 1. Open in Google Colab

This project is designed to run directly in [Google Colab](https://colab.research.google.com/), which comes preinstalled with required packages.

### 2. Steps

1. Copy and paste the full Python code from this repository into a Colab notebook.
2. Run all cells in order.
3. The dataset is cloned and extracted automatically within the notebook.
4. After training, a sample image will be downloaded, and the model will predict its gesture class.

## Dependencies

This project requires the following Python libraries (pre-installed in Colab):

- `tensorflow`
- `matplotlib`

If running locally, install the dependencies using pip:

```bash
pip install tensorflow matplotlib
