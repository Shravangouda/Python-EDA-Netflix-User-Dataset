# Python-EDA--Netflix-User-Dataset
# Netflix User Database Analysis 📊

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Netflix User Database using Python. The analysis focuses on understanding user demographics, subscription patterns, device usage, countries, and monthly revenue.

The project is implemented in a Jupyter Notebook using **Pandas, NumPy, Matplotlib, and Seaborn**.

## Dataset

**Dataset:** `Netflix Userbase Dataset.xlsm`

The notebook analyzes a dataset containing **2,500 rows and 10 columns**.

Key fields used in the analysis include:

- User ID
- Age
- Gender
- Country
- Subscription Type
- Monthly Revenue
- Device
- Plan Duration

> Place `Netflix Userbase Dataset.xlsm` in the same directory as the notebook before running the project.

## Objectives

- Understand the overall Netflix user base
- Analyze user demographics
- Calculate important business KPIs
- Compare subscription types
- Analyze monthly revenue
- Study country-wise users and revenue
- Understand device usage
- Explore revenue by gender and age
- Visualize subscription patterns

## Key KPIs

The notebook calculates the following KPIs:

- Total Users
- Total Monthly Revenue
- Average Monthly Revenue
- Total Countries
- Number of Device Types
- Average/Most Common Plan Duration
- Male Users
- Female Users

## Visualizations

The project includes visualizations such as:

1. Subscription Type Distribution
2. Revenue by Subscription Type
3. Gender Distribution
4. Age Distribution
5. Monthly Revenue Distribution
6. Revenue by Country
7. Users by Country
8. Device Usage
9. Revenue by Device
10. Revenue vs Age
11. Revenue by Gender
12. Country-wise Subscription Type
13. Gender vs Subscription Type


## 📸 Project Visualizations

### Gender Distribution
<img width="481" height="502" alt="Image" src="https://github.com/user-attachments/assets/5f883979-537e-4e3d-9e08-d7061ec5d077" />

### Age Distribution
<img width="571" height="453" alt="Image" src="https://github.com/user-attachments/assets/ae910d91-c86f-4102-ae8e-88753b0663bd" />

### Monthly Revenue Distribution
<img width="704" height="468" alt="Image" src="https://github.com/user-attachments/assets/fa08eba6-0b8f-42b7-b089-3f276ff93520" />

### Revenue by Country
<img width="1648" height="847" alt="Image" src="https://github.com/user-attachments/assets/bbf631c2-d82b-4f6e-85bd-559801bf9bef" />

### Revenue by Device
<img width="704" height="1218" alt="Image" src="https://github.com/user-attachments/assets/54a38aff-8104-462c-935e-550ae5643951" />

### Subscription Type by Country
<img width="850" height="543" alt="Image" src="https://github.com/user-attachments/assets/32b2f1b3-4cce-4fa9-898b-b6aaf0f78e2c" />

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel (`.xlsm`) dataset

## Project Structure

```text
Netflix-User-Database-Analysis/
│
├── Netflix_User_Database_Analysis.ipynb
├── Netflix Userbase Dataset.xlsm
├── README.md
├── requirements.txt
└── images/
    ├── gender_distribution.png
    ├── age_distribution.png
    ├── monthly_revenue_distribution.png
    ├── revenue_by_country.png
    ├── revenue_by_device.png
    └── subscription_by_country.png
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Rahulnaik1817/Python-EDA--Netflix-User-Dataset.git
cd netflix-user-database-analysis
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells.

## How to Run

1. Download or clone this repository.
2. Keep `Netflix Userbase Dataset.xlsm` in the project folder.
3. Install the dependencies from `requirements.txt`.
4. Open the `.ipynb` file in Jupyter Notebook or JupyterLab.
5. Run the notebook cells from top to bottom.

## Skills Demonstrated

- Data loading and inspection
- Data cleaning validation
- Descriptive statistics
- KPI calculation
- GroupBy analysis
- Aggregation
- Categorical analysis
- Data visualization
- Business-oriented data interpretation
- Python-based Exploratory Data Analysis

## Project Outcome

This project demonstrates how Python can be used to transform a raw user dataset into meaningful business insights through **KPI analysis, aggregation, and visualization**.

## Author

**Shravangouda Patil**

Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization

## License

This project is intended for educational and portfolio purposes.
