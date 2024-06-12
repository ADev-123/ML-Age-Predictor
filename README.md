# Age Detection

This repository contains a Python implementation of an age detection model using Convolutional Neural Networks (CNNs). The project leverages a large dataset of facial images from [https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki) to train and evaluate the model's ability to estimate an individual's age from their face. We explore both regression and classification approaches to predict age.

**Key Features:**

- **Data Preprocessing:** Includes techniques for cleaning, filtering, and balancing the dataset to enhance model accuracy.
- **CNN Model:** Employs a CNN architecture specifically designed for age detection from facial images.
- **Performance Evaluation:** Provides detailed analysis of model performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), accuracy, precision, recall, F1-score, and ROC curves.
- **Classification Approach:**  Implements an alternative model that classifies faces into distinct age categories (child, teen, young adult, adult, senior).
- **Visualization:** Includes graphs and charts to visualize age distribution, model performance, and classification results.

**How to Use:**

1. Clone the repository
2. Install the necessary dependencies
3. Download and place the dataset in the designated folder
4. Run the Python script to train and evaluate the model
5. Modify the code or dataset to experiment with different approaches or age detection tasks

**Future Improvements:**

- Incorporate additional features like ethnicity and data augmentation to enhance model accuracy and generalizability.
- Explore different CNN architectures and hyperparameter tuning techniques to optimize model performance.
- Develop a user interface for real-time age detection from images or video streams.
