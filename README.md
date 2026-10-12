# MNIST Dataset Fetching and Preprocessing

## About the Project

This is a basic Big Data assignment in which I fetched the MNIST dataset using Python in Google Colab and performed some basic data preprocessing.

The MNIST dataset contains images of handwritten digits from 0 to 9. Each image is 28 × 28 pixels.

## Dataset

The dataset was downloaded from the following link:

https://storage.googleapis.com/tensorflow/tf-keras-datasets/mnist.npz

It contains four arrays:

- `x_train`: 60,000 training images
- `y_train`: Labels for the training images
- `x_test`: 10,000 test images
- `y_test`: Labels for the test images

## Tools and Libraries Used

- **Google Colab:** To write and run Python code.
- **Python:** To fetch and process the dataset.
- **NumPy:** To load the dataset and work with numerical arrays.
- **Matplotlib:** To display handwritten digit images.

## Work Done

The following steps were completed in this project:

1. Fetched the MNIST dataset from the provided URL.
2. Loaded the dataset and accessed its four arrays.
3. Checked the shape and data types of the arrays.
4. Checked the minimum and maximum pixel values.
5. Displayed sample images along with their labels.
6. Checked for missing values.
7. Normalized the training and test images by dividing pixel values by 255.

After normalization, the pixel values range from 0 to 1 instead of 0 to 255.

## What I Learned

Through this assignment, I learned how to fetch a dataset from a URL, load data using NumPy, inspect its structure, display images using Matplotlib, and normalize image pixel values.

I also learned how preprocessing helps prepare data for further analysis and machine learning tasks.

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells in order.
3. The dataset will be fetched from the provided URL.
4. Run the remaining cells to inspect and preprocess the data.

## Note

This project focuses on basic data fetching and preprocessing. No machine learning model was trained as part of this assignment.
