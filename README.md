# Disease Prediction System using Machine Learning

This repository contains a disease prediction system developed using machine learning techniques. The system aims to predict the likelihood of a person having a particular disease based on input features such as age, gender, symptoms, and medical history.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
  

## Introduction

The Disease Prediction System is a machine learning-based application that assists in predicting the probability of a person having a specific disease. The system utilizes a trained model to make predictions based on input data provided by the user. It can be used by healthcare professionals, researchers, or individuals interested in gaining insights about potential diseases based on their symptoms and medical history.

## Installation

To run the Disease Prediction System locally, follow these steps:

1. Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/Mohit-Wankhade/Disease-Prediction-System-using-ML.git
   ```
2. Install the required dependencies using `pip`:
   ```
   pip install -r requirements.txt
   ```
3. Run the application:
   ```
   python app.py
   ```
   This will start the application, and you can access it by navigating to `http://localhost:5000` in your web browser.

## Usage

Once the application is running, you can access it through your web browser. The main interface allows you to enter the required information, such as age, gender, symptoms, and medical history. After providing the necessary details, click on the "Predict" button to generate the disease prediction.

## Dataset

The dataset used for training and testing the machine learning model can be found in the `data` directory. It contains anonymized patient records with various attributes such as age, gender, symptoms, and diagnosed diseases.

## Model Training

The machine learning model was trained using the dataset mentioned above. The preprocessing steps, feature engineering, and model selection can be found in the `train_model.ipynb` notebook. We used a supervised learning approach and various classification algorithms to train the model.

## Results

The performance of the trained model is evaluated using different metrics such as accuracy, precision, recall, and F1-score. The results are documented in the `results.md` file.

## Contributing

Contributions are welcome to enhance the Disease Prediction System. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your fork.
5. Submit a pull request explaining your changes.

## Contact

If you have any questions or suggestions regarding the Disease Prediction System, please feel free to contact us at wmohit301@gmail.com.
