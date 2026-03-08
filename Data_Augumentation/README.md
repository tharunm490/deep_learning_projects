# Data Augmentation with Keras

A demonstration of image data augmentation techniques using Keras `ImageDataGenerator`.

## Overview

Data augmentation artificially expands a training dataset by applying random transformations to existing images, helping reduce overfitting in deep learning models.

## Augmentation Techniques Applied

| Technique       | Value   |
| --------------- | ------- |
| Rotation        | ±30°    |
| Width Shift     | 20%     |
| Height Shift    | 20%     |
| Shear           | 20%     |
| Zoom            | 20%     |
| Horizontal Flip | Enabled |
| Fill Mode       | Nearest |

## How It Works

1. Load an image (`cat.png`) from Google Drive.
2. Convert the PIL image to a NumPy array and reshape it into a batch.
3. Create an `ImageDataGenerator` with the augmentation parameters above.
4. Generate 20 augmented versions of the image and save them to `augmented_images/` in Google Drive.

## How to Run

1. Upload your image (e.g., `cat.png`) to Google Drive.
2. Open the notebook in Google Colab.
3. Run all cells in order.
4. Find the 20 augmented images in `My Drive → augmented_images/`.

## Requirements

- TensorFlow / Keras
- Matplotlib
- NumPy
