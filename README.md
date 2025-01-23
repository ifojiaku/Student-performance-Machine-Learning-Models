# Student Performance Analysis using Machine Learning Models

## Overview
This project employs multiple machine learning models to analyze patterns in student performance data, focusing on how various factors affect exam scores. The analysis aims to provide practical insights for educational institutions and identify key factors influencing academic success.

## Models Implemented
- Random Forest Classifier
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree

## Dataset
The dataset contains student performance factors including:
- Demographic information
- Study habits
- Family background
- Academic history
- Extracurricular activities

Target variable: Exam scores categorized into ranges:
- Below 55
- 55-60
- 61-65
- 66-70
- 71-75
- 76-80
- 81+

## Features
- Data preprocessing with standardization and categorical encoding
- Class imbalance handling using SMOTE
- Hyperparameter tuning via GridSearchCV
- Comprehensive visualization of results:
  - Class distribution plots
  - Confusion matrices
  - Feature importance analysis
  - Decision boundaries (SVM)

## Model Performance
Each model provides:
- Classification reports
- Accuracy metrics
- Visual performance analysis
- Feature importance rankings

## Requirements
- python
- pandas>=1.3.0
- numpy>=1.20.0
- scikit-learn>=0.24.0
- imbalanced-learn>=0.8.0
- matplotlib>=3.4.0
- seaborn>=0.11.0

## Project Structure
├── student_performance/
│  └── StudentPerformanceFactorsAdjusted.csv
├── random_forest_classifier.ipynb
├── svm.ipynb
├── mlp.ipynb
└── README.md

## Usage
1. Install required packages:
```bash
pip install -r requirements.txt
```

2. Run the Jupyter notebooks:
```bash
jupyter notebook
```

3. Execute notebooks in the following order:
   - random_forest_classifier.ipynb
   - svm.ipynb
   - mlp.ipynb

## Model Comparison
- Random Forest: Best for feature importance analysis
- SVM: Effective for non-linear relationships
- MLP: Good at capturing complex patterns

## Visualization Examples
Each model provides:
- Pre/post SMOTE class distribution
- Confusion matrices
- Model-specific visualizations:
  - Feature importance (Random Forest, MLP)
  - Decision boundaries (SVM)

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to the branch
5. Create a Pull Request

## License
MIT License

## Authors
[Your Name]

## Acknowledgments
- Dataset source: [Include source if applicable]
- Inspired by educational data mining research
- Thanks to contributors and reviewers
