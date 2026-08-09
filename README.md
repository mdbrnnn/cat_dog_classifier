# Cat vs Dog Image Classifier

The model learns to classify images as either cats or dogs using a
convolutional neural network with residual connections, built with TensorFlow and Keras.

## Features

- Image dataset loading with Keras
- Training/validation split
- Data augmentation
- Pixel-value normalization
- Separable convolutions
- Batch normalization
- Residual connections
- Global average pooling
- Binary classification
- Model checkpointing
- Prediction on new images

## Model Architecture

The model consists of:

Input
- Rescaling
- Convolutional block
- Residual blocks
- Separable convolutions
- Global Average Pooling
- Dropout
- Dense classification layer

## Dataset

The project uses the Cats and Dogs dataset.
The dataset is not included in this repository.

## Training

The model was trained for 25 epochs using the Adam optimizer.
(Batch size: 32 , Image size: 180 × 180)
output result: 
at epoch 25/25
 - acc: 0.9663 - loss: 0.0852 - val_acc: 0.9272 - val_loss: 0.2166


## Technologies

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab