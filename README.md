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

The project uses [(https://download.microsoft.com/download/3/E/1/3E1C3F21-ECDB-4869-8368-6DEBA77B919F/kagglecatsanddogs_5340.zip)].
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

## Trained Model

The trained model is available in the
(https://github.com/mdbrnnn/cat_dog_classifier/releases/download/v1.0/best_model.keras)

u can download `best_model.keras` and place it in the project directory.
