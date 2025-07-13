# E-Commerce User Behavior Analytics System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0.2-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3.0-red)
![Flask](https://img.shields.io/badge/Flask-2.0.1-lightgrey)

## 🚀 Project Overview
This analytics system processes e-commerce website logs to:
- Identify user behavior patterns
- Visualize key sales trends
- Predict high-value customers using machine learning
- Provide actionable business insights

## ✨ Key Features
- **Data Processing Pipeline**:
  - Missing value imputation
  - Feature engineering
  - Categorical encoding
- **Advanced Analytics**:
  - User segmentation
  - Session analysis
  - Sales trend visualization
- **ML Prediction**:
  - High-spender classification (85% accuracy)
  - Feature importance analysis

## 📊 Dataset Description
The dataset (`E-commerce Website Logs.csv`) contains:

| Feature | Description | Type |
|---------|-------------|------|
| `duration_(secs)` | Session duration | Numerical |
| `sales` | Transaction amount | Numerical |
| `country` | User location | Categorical |
| `age` | User age | Numerical |
| `pay_method` | Payment type | Categorical |

**Size**: 10,000+ records with 15+ features

## 💻 Technical Implementation

### Data Flow
```mermaid
graph TD
    A[Raw Logs] --> B[Data Cleaning]
    B --> C[Feature Engineering]
    C --> D[Exploratory Analysis]
    D --> E[Model Training]
    E --> F[Prediction]
```
## Results
<img width="672" height="252" alt="image" src="https://github.com/user-attachments/assets/29bf6064-afe2-4fce-aeca-74b19e24a838" />

<img width="769" height="425" alt="image" src="https://github.com/user-attachments/assets/09b7a282-a6ed-4419-9d2a-5f54fd04e7d0" />

<img width="569" height="489" alt="image" src="https://github.com/user-attachments/assets/6328163d-75cc-4d45-b72f-7c7ac3bdbcfb" />


