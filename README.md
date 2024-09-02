# Predicting Bug Severity with ML

This repository contains the code, documentation, and analysis for the **"Predicting Bug Severity with Machine Learning"** project, developed as part of the **Machine Learning** course at Sabanci University. Our team participated in an in-class Kaggle competition and secured first place out of 42 teams by developing an effective machine learning model to predict the severity of software bugs based on their textual descriptions.

## Project Overview

The objective of this project was to classify bug reports into one of six severity levels: Enhancement, Minor, Normal, Major, Blocker, and Critical. We used a combination of natural language processing (NLP) techniques and ensemble machine learning models to achieve high accuracy in classification.

### Key Components

- **Data Preprocessing**: Textual data was transformed into numerical features using TF-IDF vectorization to capture the importance of words within the bug reports.
- **Model Selection**: We experimented with various machine learning models, including Logistic Regression, SVM, Neural Networks, and ensemble methods like Random Forest and AdaBoost.
- **Handling Imbalanced Data**: Techniques such as SMOTE and ensemble methods were employed to improve the model's performance on less frequent bug severity classes.
- **Final Model**: The final model was a Bagging Random Forest, which provided the best macro precision and helped us achieve the top spot in the Kaggle competition.

## Getting Started

To explore and run the project:

1. Clone the repository:
   ```
   git clone https://github.com/bkurtulmus/Predicting-Bug-Severity-with-ML.git
   ```
2. Navigate to the project directory:
   ```
   cd Predicting-Bug-Severity-with-ML
   ```
3. Review the code and run the notebooks to see the data preprocessing, model training, and evaluation processes.

## Project Structure

- **/data**: Contains the datasets used for training and testing.
- **/notebooks**: Includes Jupyter notebooks with code for data preprocessing, model training, and evaluation.
- **/models**: Stores the trained models and related files.
- **/results**: Contains the analysis reports and visualizations of the model performance.
- **README.md**: Overview of the project and instructions for running the code.

## Kaggle Competition

Our model achieved first place in the **In-class Kaggle competition**. You can view the competition leaderboard and details [here](https://www.kaggle.com/competitions/cs-412-in-class-kaggle-competition/leaderboard).

## Results

Our Bagging Random Forest model achieved the highest macro precision in the Kaggle competition, outperforming 41 other teams. The model was particularly effective in balancing bias and variance, making it robust against overfitting while maintaining strong performance across all severity classes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any questions or feedback, feel free to reach out via the repository or contact the project authors directly.
