# 📊 Marketing Mix Modeling with Mediation Analysis

This project implements a **Marketing Mix Model (MMM)** using mediation analysis to explore how Google Ads spend acts as a mediator between social media channels and revenue.

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure Python 3.8+ is installed along with these libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib jupyter
# Clone the repository
git clone <repository-url>

# Navigate to the project folder
cd <project-folder>

# Install dependencies
pip install -r requirements.txt

# Add your dataset
# Place your dataset as data/dataset.csv
1. Data Preparation (1_data_preparation.ipynb)
   - Clean and preprocess data
   - Feature engineering (lags, scaling)
   - Adjust for seasonality

2. Modeling (2_modeling.ipynb)
   - Train mediator model (Google Ads spend)
   - Train revenue model using Google Ads as mediator
   - Evaluate using RMSE, R²
   - Analyze feature importance and elasticity
├── data/
│   └── dataset.csv           # Marketing dataset file
├── notebooks/
│   ├── 1_data_preparation.ipynb  # Data preprocessing notebook
│   └── 2_modeling.ipynb          # Model training and evaluation notebook
├── models/                   # Saved models directory
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies


- Performance Metrics: RMSE, R², residual analysis
- Model Insights: Coefficients, feature importance, elasticity
- Visualizations: Actual vs predicted revenue
- Business Insights: Pricing effects, promotion lift, channel effectiveness

