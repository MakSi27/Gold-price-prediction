# Gold Price Prediction Model

An AI-driven project focused on analyzing and predicting gold price fluctuations using historical financial data. This repository serves as the central hub for our team's data engineering, exploratory analysis, and predictive modeling.

## 🎯 Project Goals
* **Data Integrity:** Perform a deep-clean of 10 years of historical gold price data to handle volatility and missing values.
* **Feature Discovery:** Identify high-correlation factors (Volume, Open, High, Low) that influence market trends using Pearson Correlation.
* **Predictive Modeling:** Develop a Machine Learning model (Phase 2) capable of forecasting future prices with high accuracy.
* **Research Quality:** Document the entire EDA (Exploratory Data Analysis) process to support a structured research paper.

---

## 📁 Repository Structure

```
Gold-price-prediction/
├── data/
│   ├── raw/                # Original, unmodified 10-year dataset
│   └── processed/          # Cleaned data (nulls handled, features scaled)
├── notebooks/
│   ├── 01_EDA_Cleaning/    # Initial audit and data stabilization
│   └── 02_Feature_Eng/     # Technical indicators and scaling
├── reports/
│   └── figures/            # Correlation Heatmaps and Price Trend plots
├── models/                 # Storage for trained model files (.pkl, .h5)
└── README.md               # Project documentation and structure
```

## 🛠️ Tech Stack
* **Runtime:** Google Colab (Cloud GPU/CPU)
* **IDE:** VS Code (Remote Tunneling)
* **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib
* **Version Control:** Git & GitHub (Branch-based workflow
