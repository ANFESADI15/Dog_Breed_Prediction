# Dog Breed Prediction

Build, train, and test a convolutional neural network to identify the breed of a dog in a supplied image. This is a supervised machine learning problem involving multi-class classification. The model can be used by NGOs working on animal welfare and for educational purposes.

## Project Overview

1. **Purpose**: Identify dog breeds in images.
2. **Steps**:
   - Load data from Kaggle.
   - Load labels CSV containing image IDs and breeds.
   - Check breed count.
   - One-hot encode label data.
   - Load and normalize images.
   - Build the neural network model.
   - Split data and fit it into the model, creating an accuracy plot.
   - Evaluate the model for accuracy.
   - Use the model for predictions.

## Required Packages

- `numpy`
- `pandas`
- `matplotlib`
- `tqdm`
- `keras`
- `sklearn`

## Dataset Download

To download the dataset, you need to install the Kaggle API and authenticate it using your Kaggle configuration file. The dataset is downloaded from Kaggle.

## Data Preprocessing

- Load labels data from a CSV file.
- Limit the dataset to a specific set of dog breeds.
- One-hot encode target labels.
- Load, convert, and normalize images.
- Create the dataset for training.

## Result Interpretation

The project involves building a convolutional neural network (CNN) to classify dog breeds based on input images. The dataset is preprocessed, including label encoding and image normalization. The CNN model is trained and evaluated for accuracy. The final model can be used for making predictions on new dog images to determine their breed.

This is a summarized overview of the Dog Breed Prediction project. You can refer to the detailed code and explanations for each step in the actual project code.
