# Forest Cover Type Classification

## Overview
This repository contains a Jupyter notebook (`forest-cover-type-classification.ipynb`) for classifying forest cover types using the UCI Covertype dataset. The project leverages machine learning techniques to predict forest cover types based on environmental features like elevation, aspect, and soil type. It includes data preprocessing, model training, hyperparameter tuning, and feature importance analysis.

## Dataset
The dataset is sourced from the UCI Machine Learning Repository (ID: 31) and includes 54 features and 7 cover type classes. Features include numerical attributes (e.g., elevation, slope) and categorical attributes (e.g., soil type, wilderness area).

## Notebook Structure
1. **Data Loading**: Fetches the Covertype dataset using `ucimlrepo`.
2. **Data Preprocessing**: Scales numerical features and encodes categorical variables.
3. **Model Training**: Implements RandomForestClassifier, HistGradientBoostingClassifier, and XGBClassifier.
4. **Hyperparameter Tuning**: Uses RandomizedSearchCV for optimizing model parameters.
5. **Evaluation**: Generates confusion matrices, classification reports, and accuracy scores.
6. **Feature Importance**: Visualizes the top 15 most important features using XGBoost.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/forest-cover-type-classification.git
   ```
2. Navigate to the project directory and open the notebook:
   ```bash
   cd forest-cover-type-classification
   jupyter notebook forest-cover-type-classification.ipynb
   ```
3. Run the cells sequentially to reproduce the analysis.

## Results
- Visualizations include box plots of features and a bar plot of feature importances.
- The best-performing model (XGBoost) achieves high accuracy, with detailed metrics provided in the notebook.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
