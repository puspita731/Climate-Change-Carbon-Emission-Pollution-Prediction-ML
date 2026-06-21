# ClimateCast-ML
### Prediction Model for Climate Change, Carbon Emission, and Pollution Using Machine Learning

## Overview

Climate change, carbon emissions, and environmental pollution are among the most pressing global challenges. This project presents a machine learning and deep learning framework for forecasting climate change indicators, carbon emissions, and pollution levels using historical environmental, economic, and energy-related data.

The study evaluates and compares the performance of Random Forest, XGBoost, Bidirectional LSTM (Bi-LSTM), and a Hybrid Ensemble Model for environmental forecasting.

---

## Objectives

- Forecast future carbon emission trends.
- Predict environmental pollution indicators.
- Compare machine learning and deep learning approaches.
- Identify influential environmental and socio-economic factors.
- Support data-driven environmental decision-making.

---

## Dataset

The dataset contains approximately 43,746 observations and 80 environmental, economic, and energy-related features collected across multiple countries and years.

### Features Include:
- CO₂ Emissions
- CO₂ per Capita
- GDP
- Population
- Energy Consumption
- Methane Emissions
- Nitrous Oxide Emissions
- Industrial Indicators
- Environmental Indicators

---

## Methodology

### Data Preprocessing
- Missing Value Handling
- Linear Interpolation
- Feature Engineering
- Correlation-Based Feature Selection
- One-Hot Encoding
- Feature Scaling
- SMOTE for Class Balancing

### Models Used
1. Random Forest
2. XGBoost
3. Bidirectional LSTM (Bi-LSTM)
4. Hybrid Ensemble Model

---

## Evaluation Metrics

### Regression Metrics
- R² Score
- RMSE
- MAE

### Classification Metrics
- Accuracy
- Precision
- Recall
- F1 Score

---

## Results

### Regression Performance

| Model | R² Score | RMSE | MAE |
|---------|---------|---------|---------|
| Random Forest | 0.999447 | 0.060779 | 0.034608 |
| XGBoost | 0.999320 | 0.067422 | 0.040537 |
| Bi-LSTM | 0.527499 | 1.777312 | 1.079637 |
| Hybrid Ensemble | 0.988974 | 0.271505 | 0.168079 |

### Classification Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---------|---------|---------|---------|---------|
| Random Forest | 0.589802 | 0.584746 | 0.746753 | 0.655894 |
| XGBoost | 0.614164 | 0.625907 | 0.653680 | 0.639492 |
| Bi-LSTM | 0.461756 | 0.485261 | 0.463203 | 0.473976 |
| Hybrid Ensemble | 0.478754 | 0.502268 | 0.479437 | 0.490587 |

---

## Key Findings

- Random Forest achieved the highest regression performance.
- XGBoost produced the best classification accuracy.
- Temporal feature engineering significantly improved forecasting performance.
- Tree-based ensemble models outperformed Bi-LSTM on structured environmental datasets.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- TensorFlow
- Keras
- Matplotlib
- Seaborn
- Imbalanced-Learn (SMOTE)

---

## Repository Structure

ClimateCast-ML/
│
├── data/
├── notebooks/
├── src/
├── models/
├── results/
├── report/
├── README.md
└── requirements.txt

---

## Future Work

- Real-time environmental monitoring
- Explainable AI (SHAP, LIME)
- Multi-pollutant forecasting
- CNN-LSTM and GRU architectures
- Renewable energy optimization integration

---

## Academic Context

Developed as part of the CSE427 Machine Learning course at BRAC University.

Authors:
- Puspita Biswas Oishee
- S.M. Adib-Ul-Islam
- Md. Ahanaf Hasan Rivan

---

## License

MIT License
