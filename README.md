# Butterfly Classification with CNN

## Overview

This project focuses on classifying various species of butterflies using a Convolutional Neural Network (CNN) architecture. The dataset used for this project is sourced from Kaggle and contains images of different butterfly species. Data augmentation techniques are applied to enhance the training process and improve model accuracy.

## Dataset

The dataset is obtained from [Kaggle Butterfly Classification Dataset](https://www.kaggle.com/datasets/your-dataset-link). It includes:

- Images of various butterfly species
- Each image is labeled with the corresponding species name

## Workflow

1. **Data Collection**
   - Download the butterfly images from the Kaggle dataset.

2. **Data Preparation**
   - Organize the dataset into training, validation, and test sets.
   - Preprocess the images (e.g., resizing, normalization).

3. **Data Augmentation**
   - Apply augmentation techniques such as rotation, flipping, and zooming to artificially expand the training dataset.

4. **Model Building**
   - Construct a CNN architecture suitable for image classification.

5. **Model Training**
   - Train the model on the training dataset while validating it on the validation set.

6. **Evaluation**
   - Evaluate the model's performance on the test set to determine classification accuracy.

7. **Results Visualization**
   - Visualize the training and validation metrics (accuracy and loss) using plots.

8. **Future Improvements**
   - Identify potential areas for improvement, such as trying different architectures or fine-tuning hyperparameters.

## Usage

### Data Preparation

Before running the training, ensure the dataset is organized as specified in the workflow. You may need to download the dataset manually from Kaggle and place it in the appropriate directory.

### Training the Model

To train the model, run the following command:

```bash
python src/train.py
