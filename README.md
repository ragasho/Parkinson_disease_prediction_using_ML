# Parkinson Disease Prediction using Machine Learning

This repository contains a machine learning project aimed at predicting Parkinson's Disease using various classification algorithms. Parkinson's Disease is a progressive disorder that affects the nervous system and motor system, and early detection can be crucial for effective management.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The goal of this project is to build a predictive model to diagnose Parkinson's Disease based on voice measurements. The dataset used in this project includes biomedical voice measurements from patients with and without Parkinson's Disease.

## Dataset
The dataset used in this project is publicly available on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/parkinsons). It includes a range of features such as fundamental frequency, jitter, shimmer, and others.

- **Features:**
  - MDVP:Fo(Hz) - Average vocal fundamental frequency
  - MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
  - MDVP:Flo(Hz) - Minimum vocal fundamental frequency
  - MDVP:Jitter(%) - Several measures of variation in fundamental frequency
  - MDVP:Shimmer - Several measures of variation in amplitude
  - NHR, HNR - Two measures of the ratio of noise to tonal components in the voice
  - Various measures of fundamental frequency variation
  - `status` - The target variable indicating Parkinson's Disease status (1 - Parkinson's, 0 - healthy)

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/parkinsons-disease-prediction.git
   ```
2. Change into the project directory:
   ```bash
   cd parkinsons-disease-prediction
   ```
3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
5. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Ensure your virtual environment is activated.
2. To train and evaluate the model, run the following command:
   ```bash
   python main.py
   ```

This will preprocess the data, train the model, and evaluate its performance.

## Models Used
Several machine learning algorithms have been implemented and tested to find the most accurate model:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- K-Nearest Neighbors (KNN)
- Gradient Boosting

## Results
The performance of each model is evaluated based on accuracy, precision, recall, and F1-score. The results indicate that [mention the best performing model here].

## Contributing
Contributions are welcome! If you have any suggestions, find any bugs, or want to add new features, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
