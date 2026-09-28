# Healthcare Analytics for Doctor Visits

## 📌 Project Overview

This project performs **exploratory data analysis (EDA)** on a healthcare dataset containing information about doctor visits and patient-related factors.

The analysis focuses on understanding patterns in doctor visits and examining their relationship with variables such as **age, income, illness, health condition, gender, insurance coverage, and chronic conditions**.

The project uses Python-based data analysis and visualization techniques to generate meaningful insights from the dataset.

---

## 🎯 Problem Statement

To analyze doctor visit data and identify patterns and relationships between doctor visits and patient-related factors such as age, income, illness, health condition, gender, insurance coverage, and chronic conditions.

---

## 📝 Problem Description

Healthcare organizations collect large amounts of patient and doctor-visit data. Analyzing this data can help identify patterns in healthcare utilization.

This project analyzes a **Doctor Visits dataset** using Python. The dataset contains information about:

* Age
* Income
* Number of illnesses
* Health condition
* Number of doctor visits
* Gender
* Private insurance
* Free/poor medical coverage
* Free repatriation
* Number of chronic conditions
* Long-term chronic condition

The project follows a data-analysis workflow consisting of:

1. Data loading
2. Data quality checking
3. Data cleaning
4. Exploratory data analysis
5. Statistical analysis
6. Data visualization
7. Relationship and correlation analysis
8. Insight generation

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data cleaning and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook / Google Colab** – Development environment

---

## 📂 Dataset

The project uses the following dataset:

**P2-Healthcare Analytics for Doctor Visits.csv**

The dataset contains records related to doctor visits and several demographic, health, income, insurance, and chronic-condition variables.

### Main Variables

| Variable    | Description                         |
| ----------- | ----------------------------------- |
| `age`       | Age of the individual               |
| `income`    | Income level                        |
| `illness`   | Number of illnesses                 |
| `health`    | Health condition/health score       |
| `visits`    | Number of doctor visits             |
| `gender`    | Gender                              |
| `private`   | Private insurance status            |
| `freepoor`  | Free/poor medical coverage status   |
| `freerepat` | Free repatriation status            |
| `nchronic`  | Number/status of chronic conditions |
| `lchronic`  | Long-term chronic condition status  |

---

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

* Checked for missing values.
* Checked for duplicate records.
* Checked data types.
* Removed the unnecessary `Unnamed: 0` CSV index column.
* Removed duplicate records where applicable.
* Checked categorical variables for consistency.

No unnecessary categories or analytical columns were added to the original dataset.

---

## 📊 Exploratory Data Analysis

The project analyzes:

### Doctor Visits

* Distribution of the number of doctor visits.
* Average number of visits.
* Minimum and maximum visits.

### Gender

* Number of records by gender.
* Average doctor visits by gender.
* Total doctor visits by gender.

### Age

* Average doctor visits across age values.
* Relationship between age and doctor visits.

### Illness

* Average doctor visits according to number of illnesses.
* Distribution of visits across illness levels.

### Health

* Average visits for different health values.
* Distribution of doctor visits according to health condition.

### Chronic Conditions

* Relationship between chronic conditions and doctor visits.
* Comparison of `nchronic` and `lchronic`.

### Insurance and Support

* Doctor visits based on private insurance.
* Doctor visits based on free/poor medical coverage.
* Free repatriation status and healthcare utilization.

### Income

* Relationship between income and doctor visits.

### Correlation

Correlation analysis is performed among the numerical variables:

* Age
* Income
* Illness
* Health
* Visits

---

## 📈 Visualizations

Different visualization techniques are used to understand the data:

* Count Plot
* Bar Plot
* Line Plot
* Box Plot
* Violin Plot
* Scatter Plot
* Pie Chart
* Heatmap

These visualizations help identify patterns and relationships within the healthcare dataset.

---

## 🔍 Key Analysis Areas

Some of the important questions explored in this project are:

* How are doctor visits distributed?
* How do doctor visits vary across gender?
* Is there a relationship between age and doctor visits?
* How does the number of illnesses relate to doctor visits?
* How does health condition relate to doctor visits?
* Are doctor visits different based on insurance status?
* How does income relate to doctor visits?
* What relationships exist between the numerical healthcare variables?
* How are chronic conditions associated with doctor visits?

---

## 👥 End Users

This project can be useful for:

* Healthcare organizations
* Hospitals and clinics
* Healthcare analysts
* Healthcare researchers
* Healthcare administrators
* Data analysts
* Students learning healthcare analytics

---

## 📁 Project Structure

```text
Healthcare-Analytics-Doctor-Visits/
│
├── P2-Healthcare Analytics for Doctor Visits.csv
├── Healthcare_Analytics_Doctor_Visits.ipynb
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the project

Open the `.ipynb` file using:

* Jupyter Notebook
* JupyterLab
* Google Colab
* VS Code

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 4. Run the notebook

Execute the notebook cells sequentially to perform data cleaning, analysis, and visualization.

---

## 📌 Conclusion

This project demonstrates how Python-based data analysis can be used to explore healthcare utilization patterns. By analyzing doctor visits alongside demographic, health, income, insurance, and chronic-condition variables, the project provides a structured view of factors associated with healthcare usage.

The project primarily focuses on **exploratory data analysis and visualization** rather than predictive modeling.

---

## 👩‍💻 Author

**Ankita Thapa**

B.Tech Computer Science & Engineering – Data Science

**Skills Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Data Analysis
