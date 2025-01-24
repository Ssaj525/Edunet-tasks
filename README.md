# Edunet-tasks

# Waste Classification Project

This project focuses on classifying different types of waste (organic and recyclable) using image classification techniques. The model is trained on a dataset containing images of waste items, and the goal is to classify these images into appropriate categories. This notebook uses TensorFlow/Keras and OpenCV to process images and build a classification model.

## Dataset

The dataset used in this project is **Waste Classification Data**, which contains images divided into categories like Organic and Recyclable.

You can find the dataset here: [Waste Classification Dataset](https://www.kaggle.com/datasets/techsash/waste-classification-data)

## Project Structure

- **train_path**: The path to the training data (images of different types of waste).
- **test_path**: The path to the test data (images used to evaluate the model).

The dataset is stored in two main directories:

1. **TRAIN**: Contains images for training the model.
2. **TEST**: Contains images used for testing and validation.

## Requirements

- Python 3.x
- TensorFlow 2.x
- OpenCV
- Pandas
- Matplotlib
- tqdm
## Steps to run
- Import Libraries: The following libraries are used for image processing, model building, and visualization.
- Load Dataset: The dataset is loaded from the Kaggle environment, using paths like **dataset/DATA/TRAIN**
- Data Preprocessing: Images are loaded using OpenCV, resized, and converted to RGB format.
- Data Visualization: The distribution of waste categories (Organic, Recyclable) is visualized using a pie chart.

You can install the required packages using:

````bash
pip install tensorflow opencv-python pandas matplotlib tqdm



