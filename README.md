# <a href = 'https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use' target='_blank'>Kaggle CMI </a> (Child Mind Institute — Problematic Internet Use)

## Project Overview
This repository contains our solution for the Kaggle CMI Competition 2024. The goal of the competition was to predict the Severity Impairment Index (SII) for children using their physical activity data and internet usage patterns. Machine learning and deep learning techniques were applied to achieve optimal predictive performance. 

## Competition Task
Predict the Severity Impairment Index (SII) using:
- Physical activity data (accelerometer data, physical fitness assessments, and questionnaires)
- Internet usage data

## Technologies and Tools
- **Programming Language & Libraries**: Python (pandas, numpy, matplotlib)
- **Machine Learning**: scikit-learn
- **Deep Learning**: TensorFlow, PyTorch

## Data Description
- Data provided in CSV and Parquet formats
- Training data consists of 3960 samples with 80 features (excluding id and target variable)
- Time series data requiring aggregated statistical analysis (mean, median, max, std)

## Evaluation Metrics
- **Quadratic Weighted Kappa**: Measures agreement between predicted and actual outcomes, ranging from -1 to 1.
- **Confusion Matrix**: Evaluates classification model performance.

## Project Steps
1. **Data Exploration and Analysis**
   - Analyzed feature distributions and correlations
   - Handled missing values
   - Conducted Exploratory Data Analysis (EDA)

2. **Feature Engineering**
   - Developed basic statistical features
   - Extracted and aggregated time series features

3. **Model Training and Optimization**
   - Employed ensemble methods (LightGBM, CatBoost, XGBoost)
   - Model tuning, including threshold optimization

## Final Results
- Achieved a silver medal, ranking highly among 3650 participating teams after effective feature engineering and model optimization.

## Contact
For questions or discussions, feel free to reach out via GitHub issues.

