# 🤖 Smart Manufacturing Machines Efficiency Prediction

## 📌 Overview

This project builds a machine learning system to predict the
**efficiency status** of manufacturing machines using real-time sensor
data. It helps reduce downtime, optimize production, and enable
predictive maintenance.

------------------------------------------------------------------------

## 🎯 Objectives

-   Predict machine efficiency levels: **High, Medium, Low**
-   Improve operational efficiency
-   Enable proactive maintenance decisions

------------------------------------------------------------------------

## 🚀 Key Features

-   Data preprocessing (cleaning, encoding, scaling)
-   Feature selection using Random Forest & ANOVA
-   Multiple ML models:
    -   Logistic Regression
    -   Support Vector Machine (SVM)
    -   Random Forest
-   Model evaluation:
    -   Accuracy Score
    -   Confusion Matrix
    -   ROC Curve (One-vs-Rest)
-   Interactive **Streamlit web app**
-   Model persistence using `joblib`

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   **Language**: Python
-   **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn,
    joblib
-   **Frontend**: Streamlit

------------------------------------------------------------------------

## 📊 Dataset

-   Source:
    https://www.kaggle.com/datasets/ziya07/intelligent-manufacturing-dataset
-   Size: 100,000+ rows
-   Target: `Efficiency_Status`

### Key Features Used

-   Production_Speed_units_per_hr
-   Error_Rate\_%

------------------------------------------------------------------------

## 🧠 Model Workflow

1.  Data Collection
2.  Data Cleaning & Preprocessing
3.  Feature Selection
4.  Model Training
5.  Model Evaluation
6.  Deployment via Streamlit

------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

``` bash
git clone https://github.com/kvishwa-dev/machine-efficiency-prediction.git
cd machine-efficiency-prediction
```

### 2️⃣ Create Virtual Environment

``` bash
python -m venv venv
```

Activate: - Windows:

``` bash
venv\Scripts\activate
```

-   Mac/Linux:

``` bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

``` bash
pip install -r requirements.txt
```

### 4️⃣ Run Application

``` bash
streamlit run app.py
```

### 5️⃣ Open in Browser

http://localhost:8501

------------------------------------------------------------------------

## 💻 Streamlit App Features

-   User input form for machine parameters
-   Instant efficiency prediction
-   Confusion matrix visualization
-   ROC curve visualization

------------------------------------------------------------------------

## 📁 Project Structure

    ├── models/
    ├── app.py
    ├── notebook.ipynb
    ├── smart_manufacturing_efficiency_EDA.ipynb
    ├── manufacturing_6G_dataset.csv
    ├── requirements.txt
    └── README.md

------------------------------------------------------------------------

## 📈 Future Improvements

-   Real-time IoT sensor integration
-   Time-series forecasting
-   Predictive maintenance alerts
-   Enterprise dashboard for monitoring

------------------------------------------------------------------------

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull
request.

------------------------------------------------------------------------

## 📬 Contact

For queries or collaboration: **Email**: cse.kvishwa@gmail.com