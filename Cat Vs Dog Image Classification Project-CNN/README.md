# Cat vs Dog Image Classification - CNN

A Convolutional Neural Network (CNN) model to classify images of cats and dogs.

## Dataset

- **Source**: Microsoft PetImages dataset (cats and dogs)
- **Structure**: `PetImages/train/` and `PetImages/test/` with `cat/` and `dog/` subfolders
- **Image Size**: Resized to 256×256 pixels

## Model Architecture

| Layer                        | Details                    |
| ---------------------------- | -------------------------- |
| Conv2D + BatchNorm + MaxPool | 32 filters, 3×3 kernel     |
| Conv2D + BatchNorm + MaxPool | 64 filters, 3×3 kernel     |
| Conv2D + BatchNorm + MaxPool | 128 filters, 3×3 kernel    |
| Flatten                      | —                          |
| Dense + Dropout              | 128 units, 10% dropout     |
| Dense + Dropout              | 64 units, 10% dropout      |
| Dense (Output)               | 1 unit, Sigmoid activation |

- **Loss**: Binary Crossentropy
- **Optimizer**: Adam
- **Metric**: Accuracy

## How to Run

1. Upload `PetImages.zip` to Google Drive.
2. Open the notebook in Google Colab.
3. Run all cells in order — the dataset is unzipped, cleaned, and the model is trained for 10 epochs.
4. Predict on a custom image by setting `test_image_path` to your image in Google Drive.

## Results

Training and validation accuracy/loss plots are generated after training to evaluate model performance.

## Requirements

- TensorFlow / Keras
- OpenCV (`cv2`)
- Pillow
- Matplotlib
