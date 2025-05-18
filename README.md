# Weather-Based Disease Outbreak Prediction

## 📌 Project Overview

This is the term project for **COSE471: Data Science** at Korea University (Spring 2025).  
The goal is to predict disease outbreaks using historical weather data and uncover frequent weather patterns that contribute to such events.

We apply concepts from the course such as:

- **Classification** (Logistic Regression, Decision Trees, SVM, etc.)
- **Pattern Mining** (FP-Growth, Association Rules)
- *(Optional)* Outlier Detection and Clustering

---

## 📂 Project Structure

```
weather-disease-prediction/
├── data/
│   ├── raw/                 # Original dataset (CSV from Kaggle)
│   └── processed/           # Cleaned/engineered dataset
├── notebooks/               # Jupyter Notebooks (EDA, modeling, etc.)
├── src/                     # Python scripts for modular code
├── results/                 # Output plots and result summaries
├── report/                  # Final report and presentation
├── requirements.txt         # Python dependencies
└── README.md                # Project overview and instructions
```

---

## 🧪 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/weather-disease-prediction.git
cd weather-disease-prediction
```

### 2. Set Up Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Jupyter

```bash
jupyter lab
```

---

## 📊 Dataset

Download from Kaggle:  
[https://www.kaggle.com/datasets/orvile/weather-related-disease-prediction-dataset](https://www.kaggle.com/datasets/orvile/weather-related-disease-prediction-dataset)

Place the CSV file in: `data/raw/`

