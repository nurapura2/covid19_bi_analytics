# COVID-19 — Risk Prediction & Recommendation System

**Description**  
This final project was completed as part of a **team**, analyzing the *COVID-19 Worldwide Dataset*.  
The goal of the project is to build a **Risk Prediction Application** and a **Content-based Recommendation System** that identifies countries with similar pandemic profiles and suggests proportional resource allocation.

## Project Structure
```
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

## Work Completed
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Linear Regression model  
- Random Forest Regression model  
- Content-based Recommendation System to identify similar countries  
- Correlation-based resource allocation insights  
- Visualizations (Python + Power BI)

## Task Description
- **Risk Prediction Application**  
- **Recommendation System Utility** — identifies countries with similar pandemic dynamics  
- **Correlation-Based Resource Allocation** — suggested proportional resource allocation rate

## Evaluation Metrics
**Regression Models:**  
- MAE  
- MSE  
- RMSE  
- R² Score  

**Recommendation System:**  
- Similarity Score (cosine similarity)  
- Correlation analysis  

## How to Run
1. Install dependencies:
```
pip install -r requirements.txt
```

2. Launch the notebook:
```
jupyter notebook notebooks/final_notebook.ipynb
```

3. Open Power BI dashboard:
- File: `powerbi/dashboard.pbix`  
- Software: Power BI Desktop

## Technologies Used
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  
- Power BI  

## Notes
- All datasets are located in the `data/` directory.  
- Notebook contains all visualizations and models.  
- The project was completed collaboratively as part of a team.

## Authors
- Kenzhaly Gaziz (240107045@sdu.edu.kz)
- Dyuisenov Nurassyl (240107081@sdu.edu.kz)
- Turgunbay Meiirbek (240107022@sdu.edu.kz)
