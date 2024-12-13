# Breast Cancer Prediction Using Machine Learning

## Project Overview
This project aims to predict whether a breast tumor is malignant (cancerous) or benign (non-cancerous) using diagnostic features. The prediction is made using machine learning algorithms such as Logistic Regression, Decision Tree, and Random Forest. By analyzing patterns in the data, this project provides an efficient and reliable tool for early breast cancer diagnosis.

## Features
- **Data Visualization:** Visualize the dataset using seaborn and matplotlib for better understanding.
- **Feature Correlation Analysis:** Identify relationships between features through correlation heatmaps.
- **Model Implementation:** Train and evaluate multiple machine learning models (Logistic Regression, Decision Tree, Random Forest).
- **Accuracy Comparison:** Compare the performance of models to select the best one.
- **Saved Model:** Export the trained model for future use.

## Dataset
The dataset used contains diagnostic information about breast tumors, including features such as:
- Mean radius
- Texture
- Perimeter
- Area
- Smoothness

The target variable is the diagnosis, which can either be:
- **M**: Malignant (cancerous)
- **B**: Benign (non-cancerous)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Place the dataset file (`data.csv`) in the project directory.
2. Run the script:
   ```bash
   python breast_cancer_prediction.py
   ```
3. View the results, including model accuracies and predictions.

## Code Structure
- **Data Preprocessing:**
  - Load and clean the dataset.
  - Encode categorical values.
  - Scale the features for better model performance.

- **Visualization:**
  - Count plots for diagnosis distribution.
  - Pair plots and heatmaps for feature analysis.

- **Model Training:**
  - Logistic Regression
  - Decision Tree
  - Random Forest

- **Evaluation:**
  - Accuracy of each model.
  - Comparison of predicted vs actual values.

## Example Results
- **Logistic Regression Accuracy:** 95%
- **Decision Tree Accuracy:** 93%
- **Random Forest Accuracy:** 97%

## Dependencies
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- joblib

## Future Enhancements
- Add more advanced models like Support Vector Machines (SVM) or Neural Networks.
- Implement hyperparameter tuning for improved model performance.
- Create a web interface for user interaction with the model.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any changes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments
- Special thanks to the creators of the dataset used in this project.
- Inspiration from various machine learning tutorials and documentation.

