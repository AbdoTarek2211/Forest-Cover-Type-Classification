# Forest Cover Type Classification 🌲

A machine learning project that classifies forest cover types using the UCI Covertype dataset, achieving high accuracy with XGBoost, RandomForest, and HistGradientBoosting models.

## 📋 Project Overview

This project implements and compares three machine learning models for forest cover type classification:
- **RandomForestClassifier**: Ensemble decision tree model
- **HistGradientBoostingClassifier**: Gradient boosting with histogram-based splits
- **XGBClassifier**: Optimized gradient boosting with hyperparameter tuning

## 🎯 Key Results

| Model | Test Accuracy |
|-------|---------------|
| RandomForestClassifier | ~95%* |
| HistGradientBoostingClassifier | ~96%* |
| XGBClassifier | ~97%* |

*Note: Exact accuracies may vary based on hyperparameter tuning and random seed.

## 🗂️ Dataset

- **Dataset**: UCI Covertype Dataset (ID: 31)
- **Classes**: 7 forest cover type categories
- **Features**: 54 features (10 numerical, 44 categorical)
- **Split**: 70% Training, 15% Validation, 15% Test

## 🔧 Features

### Core Implementation
- ✅ Data preprocessing (scaling numerical features, encoding categorical variables)
- ✅ Model training with RandomForest, HistGradientBoosting, and XGBoost
- ✅ Hyperparameter tuning using RandomizedSearchCV
- ✅ Comprehensive model evaluation

### Advanced Features
- 🚀 **Feature Importance Analysis**: Identifies key features like `Soil_Type37` and `Elevation`
- 📊 **Performance Visualization**: Box plots, feature importance bar plots, confusion matrices
- 🔄 **Model Comparison**: Side-by-side performance analysis
- 💾 **Reproducible Workflow**: Fully documented Jupyter notebook

## 🏗️ Architecture

### RandomForestClassifier
- Ensemble of decision trees
- Tuned parameters: `n_estimators`, `max_depth`, `min_samples_split`

### HistGradientBoostingClassifier
- Histogram-based gradient boosting
- Tuned parameters: `max_iter`, `learning_rate`, `max_depth`

### XGBClassifier
- Optimized gradient boosting
- Tuned parameters: `n_estimators`, `learning_rate`, `max_depth`, `subsample`

## 🛠️ Technologies Used

- **Python 3.x**
- **Scikit-learn** - Machine learning framework
- **XGBoost** - Gradient boosting library
- **Pandas & NumPy** - Data manipulation
- **Matplotlib & Seaborn** - Visualization
- **ucimlrepo** - Dataset fetching

## 📈 Performance Metrics

### RandomForestClassifier
- **Test Accuracy**: ~95%
- **Training Time**: Moderate
- **Model Size**: Moderate memory footprint

### HistGradientBoostingClassifier
- **Test Accuracy**: ~96%
- **Training Time**: Faster due to histogram-based splits
- **Scalability**: Efficient for large datasets

### XGBClassifier
- **Test Accuracy**: ~97%
- **Training Time**: Optimized with early stopping
- **Feature Importance**: Detailed analysis provided

## 📊 Visualizations

The project generates:
- Box plots for numerical features
- Feature importance bar plots (XGBoost)
- Confusion matrices for model evaluation
- Classification reports with precision, recall, and F1-scores

## 🎓 Key Learnings

- **Feature Importance** reveals critical environmental factors for classification
- **Hyperparameter Tuning** significantly improves model performance
- **Ensemble Methods** like XGBoost excel in handling complex datasets
- **Data Preprocessing** is key to achieving high accuracy

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

## 🙏 Acknowledgments

- UCI Machine Learning Repository for the Covertype dataset
- Scikit-learn and XGBoost communities
- Elevvo Pathways internship program

---

**Built with ❤️ for environmental data science and machine learning**
