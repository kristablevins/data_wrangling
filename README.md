# Cardiovascular and Stroke Risk Data Wrangling

## Project Overview
This project focuses on gathering, assessing, and cleaning real-world healthcare data to analyze patterns in cardiovascular disease and stroke occurrence across different demographics.

The analysis investigates how **age and gender influence the likelihood of cardiovascular disease and stroke**, using patient datasets containing demographic, clinical, and lifestyle variables.

This project demonstrates the full **data wrangling process** including data gathering, quality assessment, and data cleaning before analysis.

---

## Research Question

**How do age and gender influence the occurrence of cardiovascular disease and stroke?**

The goal is to identify patterns that may highlight differences in disease occurrence across demographic groups.

---

## Datasets

### Dataset 1 – Cardiovascular Disease Dataset

**Source:** Kaggle  
**Type:** CSV file  
**Collection Method:** Retrieved programmatically using the Kaggle API.

#### Variables

| Variable | Description |
|--------|-------------|
| id | Unique patient identifier |
| age | Age in days |
| gender | Patient gender |
| height | Height (cm) |
| weight | Weight (kg) |
| ap_hi | Systolic blood pressure |
| ap_lo | Diastolic blood pressure |
| cholesterol | Cholesterol level |
| gluc | Glucose level |
| smoke | Smoking status |
| alco | Alcohol intake |
| active | Physical activity |
| cardio | Presence of cardiovascular disease |

---

### Dataset 2 – Stroke Dataset

**Type:** CSV file  
**Collection Method:** Imported from a local file and loaded into Python using Pandas.

#### Variables

| Variable | Description |
|--------|-------------|
| gender | Patient gender |
| age | Age in years |
| hypertension | Hypertension indicator |
| heart_disease | Heart disease indicator |
| ever_married | Marital status |
| work_type | Type of employment |
| Residence_type | Urban or rural residence |
| avg_glucose_level | Average glucose level |
| bmi | Body Mass Index |
| smoking_status | Smoking behavior |
| stroke | Stroke occurrence |

---

## Data Wrangling Process

The project follows the standard **data wrangling workflow**:

### 1. Data Gathering
Data was obtained from multiple sources including:

- Kaggle API download
- Local CSV files

The datasets were imported into Python using **Pandas DataFrames**.

---

### 2. Data Assessment

Both **visual and programmatic inspection** were used to identify data quality issues such as:

- Missing values
- Inconsistent data types
- Duplicate records
- Outliers
- Non-standard variable formats

---

### 3. Data Cleaning

Cleaning steps included:

- Removing unnecessary columns
- Converting incorrect data types
- Handling missing values
- Standardizing variable formats
- Improving dataset structure for analysis

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Kaggle API

---

## Key Skills Demonstrated

- Data gathering from multiple sources
- Programmatic dataset retrieval
- Data quality assessment
- Data cleaning and preprocessing
- Working with healthcare datasets
- Preparing data for analysis

---

## How to Run the Project

Clone the repository:
git clone https://github.com/kristablevins/data_wrangling.git

Launch the notebook:
jupyter notebook Data_Wrangling_Project.ipynb

## Author

Krista Blevins

---

## License

This project was completed for educational purposes.
