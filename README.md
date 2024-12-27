# Car and Plane Detection Project

## Project Description

This project implements a Convolutional Neural Network (CNN) model to detect and classify images of cars and planes. The model is trained on a dataset of car and plane images to distinguish between the two classes.

## Key Features

- Uses a CNN architecture for image classification
- Trained on a dataset of car and plane images
- Implements data augmentation techniques to improve model performance
- Utilizes Keras and TensorFlow for model development and training
- Achieves high accuracy in distinguishing between cars and planes

## Dataset

The dataset consists of:
- 400 training images
- 100 validation images

Images are resized to 224x224 pixels for consistency.

## Model Architecture

The CNN model architecture includes:
- Convolutional layers
- Max pooling layers
- Flatten layer
- Dense layers
- Dropout for regularization

## Data Augmentation

To improve model generalization, the following data augmentation techniques are applied:
- Random rotation
- Width and height shifts
- Shear transformation
- Zoom
- Horizontal flip

## Usage

1. Install required dependencies:
   ```
   pip install tensorflow keras matplotlib
   ```

2. Run the Jupyter notebook to train and evaluate the model.

3. Use the trained model to make predictions on new images.

## Results

The model achieves high accuracy in distinguishing between cars and planes. Detailed performance metrics and visualizations are available in the notebook.

## Future Improvements

- Expand the dataset to include more diverse images
- Experiment with transfer learning using pre-trained models
- Implement object detection to locate cars and planes within images
