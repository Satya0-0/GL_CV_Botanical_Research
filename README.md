# GL_CV_Botanical_Research

This project uses computer vision techniques to classify plant species from images.  It's part of a Great Learning assignment.

## ** Owning to properitary issues, the problem statement of the project cannot be shared **

## Project Tasks

**Part A: Plant Seedling Classification**

1.  **Data Import and Understanding:** The dataset was extracted, and images and labels were loaded into a structured DataFrame. A function was implemented to display random images for exploration.
2.  **Data Preprocessing:** Images were resized, normalized, and labels were encoded for model training. The data was split into training and testing sets.
3.  **Model Development and Training:** A Convolutional Neural Network (CNN) model was designed, trained, and evaluated on the test data.

**Part B: Flower Species Classification**

1.  **Data Import and Understanding:** The oxflower17 dataset was imported, and its properties were analyzed.
2.  **Image Exploration and Transformation:** Images were explored, and transformations like grayscale conversion, sharpening, and blurring were applied.
3.  **Model Training and Tuning:**  Models were trained and evaluated using a Supervised Learning algorithm (SVC), an Artificial Neural Network (ANN), and a Convolutional Neural Network (CNN). The best-performing model (CNN) was then used to predict the class of a new image (`Prediction.jpg`).

## Project Overview

The goal is to build a classifier that can identify the species of a plant from a photo.  The dataset used contains images of 12 different plant species.

## Getting Started

1. Clone the repository: `git clone https://github.com/Satya0-0/GL_CV_Botanical_Research.git`
2. Install the required libraries:  (List the key libraries, e.g., `pip install numpy pandas matplotlib tensorflow opencv-python Pillow`)
3. Run the notebook: `jupyter notebook GL_CV_Botanical_Research.ipynb`

## Files

*   `GL_CV_Botanical_Research.ipynb`: Jupyter Notebook containing the code.
*   `data/`: Data set used: "17 category dataset" from URL - https://www.robots.ox.ac.uk/~vgg/data/flowers/
              Other data set can be found at - https://www.kaggle.com/c/plant-seedlings-classification/data
*   `Prediction.jpg`: Sample image for prediction.

## Results

The CNN model achieved the best performance, with an accuracy of around 54% on the test set.
