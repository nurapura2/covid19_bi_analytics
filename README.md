---

# 🦠 COVID-19 Risk Prediction & Country Similarity Analysis

---

## 📌 Project Overview

This repository contains a final team project focused on analyzing the *COVID-19 Worldwide Dataset* using machine learning, statistical analysis, and similarity-based recommendation techniques.

The goal of the project is to build a **Risk Prediction Application** and a **Content-based Recommendation System** that identifies countries with similar pandemic profiles and suggests proportional resource allocation strategies based on correlation insights.

---

## 📂 Project Structure

```text
final_project/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── final_notebook.ipynb
├── powerbi/
│   └── dashboard.pbix
├── report/
│   └── final_report.pdf
├── requirements.txt
└── README.md

```

---

## 🧹 Data Preprocessing & Statistics

The data cleaning and preprocessing stage included:

* Handling missing values and removing unnecessary columns
* Feature selection and data normalization
* Encoding categorical variables and outlier inspection
* Time-series aggregation by country

### Dataset Statistics

| Metric | Value |
| --- | --- |
| **Original Rows** | 166,326 |
| **Original Columns** | 67 |
| **Processed Rows** | 88,415 |
| **Processed Columns** | 38 |

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to identify key insights and patterns across the global dataset:

* Infection trends over time and regional differences
* Country-level pandemic dynamics and patterns
* Mortality and vaccination relationships
* Feature correlations for resource allocation

*Visualizations were built collaboratively using Python (`matplotlib`, `seaborn`) and Power BI.*

---

## 🤖 Machine Learning & Risk Prediction

We built regression and classification models to analyze statistical relationships and predict COVID-19 risk levels using pandemic-related indicators.

### Models Used

* **Linear Regression** (for statistical analysis & baseline prediction)
* **Random Forest Regression / Classifier** (for robust risk estimation)

### Evaluation Metrics

#### Regression Models

* **MAE** (Mean Absolute Error)
* **MSE** (Mean Squared Error)
* **RMSE** (Root Mean Squared Error)
* **R² Score** (Coefficient of Determination)

#### Classification Metrics (Risk Levels)

| Metric | Description | Performance (Random Forest) |
| --- | --- | --- |
| **Accuracy** | Overall classification accuracy | **~92.3%** |
| **Precision** | Prediction precision per risk class | *Calculated in notebook* |
| **Recall** | Sensitivity of risk detection | *Calculated in notebook* |
| **F1 Score** | Weighted harmonic mean | *Calculated in notebook* |

---

## 🌍 Country Similarity Recommendation System

A content-based recommendation utility implemented to identify countries with similar pandemic dynamics.

### Techniques Used

* **Cosine Similarity** (to calculate similarity scores between country feature vectors)
* **Correlation Analysis** (to drive resource allocation insights)

### Example Use Cases

* Identifying countries with similar outbreak curves and healthcare workloads.
* Comparing defensive response patterns between regions.
* Suggesting proportional resource allocation rates based on similar country profiles.

---

## 📈 Dashboard & Visualization

Interactive dashboards were created in **Power BI** to support data-driven decisions:

* Global COVID-19 trends map
* Country-by-country dynamic comparison
* Vaccination progress vs. Infection rates analysis
* Risk distribution maps and statistical summaries

---

## 🛠️ Technologies Used

| Category | Tools / Libraries |
| --- | --- |
| **Programming** | Python |
| **Data Analysis** | pandas, numpy |
| **Machine Learning** | scikit-learn |
| **Visualization** | matplotlib, seaborn |
| **Dashboarding** | Power BI |

---

## 🚀 How to Run

### 1. Install Dependencies

Ensure you have Python installed, then run:

```bash
pip install -r requirements.txt

```

### 2. Launch the Notebook

To view preprocessing, EDA, statistical analysis, and ML models:

```bash
jupyter notebook notebooks/final_notebook.ipynb

```

### 3. Open Power BI Dashboard

* **File:** `powerbi/dashboard.pbix`
* **Software required:** Power BI Desktop

---

## 📌 Notes

* All datasets are securely located inside the `data/` directory.
* The final Jupyter Notebook contains the complete end-to-end codebase (preprocessing, models, and inline plots).
* The comprehensive analytical summaries can be found in `report/final_report.pdf`.

---

## 👥 Team & Roles

| Name | Role | Email |
| --- | --- | --- |
| **Nurassyl Dyuisenov** | Data Preprocessing & Machine Learning | 240107081@sdu.edu.kz |
| **Kenzhaly Gaziz** | Statistical Analysis & Research | 240107045@sdu.edu.kz |
| **Turgunbay Meiirbek** | Dashboard & Visualization | 240107022@sdu.edu.kz |
