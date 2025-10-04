# Tech Layoff Analysis

## 📌 Project Overview

The **Tech Layoff Analysis** project provides an in-depth exploration of layoffs in the technology sector. Using real-world datasets, this project performs **data cleaning, exploratory data analysis (EDA), feature engineering, and visualization** to identify trends, patterns, and insights into workforce reductions across tech companies.  

The analysis is implemented in Python using **Jupyter/Colab notebooks**, making it easy to reproduce and extend.

---

## 🔍 Objectives

1. Analyze layoffs across different tech companies and industries.
2. Identify trends and patterns in layoff percentages and counts.
3. Examine correlations between company size, employee count, and layoffs.
4. Visualize data to generate actionable insights.
5. Apply basic machine learning for predictive insights (optional).

   Tech-Layoff-Analysis/
│
├── data/
│ ├── raw/ # Original datasets (CSV, Excel)
│ └── processed/ # Cleaned and processed datasets
│
├── notebooks/ # Colab/Jupyter notebooks
│ ├── EDA.ipynb # Exploratory Data Analysis
│ ├── Feature_Engineering.ipynb
│ └── Visualization.ipynb
│
├── scripts/ # Optional scripts for data cleaning or automation
│
├── visualizations/ # Charts, graphs, and plots generated
│
├── requirements.txt # Required Python libraries
└── README.md # Project documentation

## 📊 Dataset

The project primarily uses publicly available layoff datasets from:


- Kaggle datasets on tech layoffs

**Sample Columns in Dataset:**

- `company_name` – Name of the tech company  
- `company_size` – Number of employees before layoffs  
- `employees_fired` – Number of employees laid off  
- `layoff_percentage` – % of employees laid off  
- `date` – Date of layoff announcement  
- `industry` – Industry segment  
- `region` – Geographical location  

> A cleaned version of the dataset is stored in `data/processed/` for reproducibility.

---

## 🛠️ Technologies Used

- **Languages:** Python 3.x  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn  
- **Tools:** Google Colab, Jupyter Notebook  
- **Visualization:** Matplotlib, Seaborn, Plotly  

---

## 🚀 Getting Started

### Prerequisites

Ensure you have **Python 3.x** installed along with `pip`.
