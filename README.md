# Student Result Analysis — Exploratory Data Analysis

Exploratory Data Analysis (EDA) on 30,641 student records to identify which factors — parental education, test preparation, sports participation, family size, and demographics — actually influence Math, Reading, and Writing scores.

## About This Project

This project explores a dataset of 30,641 students to understand which factors influence academic performance. Using Python in a Jupyter Notebook, the analysis covers data cleaning, visualization, and outlier detection across variables such as parental education, test preparation, sports participation, number of siblings, and ethnic group.

**Key findings:**
- **Parental education level** and **test preparation completion** are the strongest predictors of student scores.
- **Number of siblings** has little to no measurable effect on performance.
- **Reading and Writing scores** are highly correlated with each other (0.95), while **Math** performance is comparatively more independent.
- Regular **sports participation** is associated with a modest score improvement.

## Dataset

| Attribute | Detail |
|---|---|
| Total Records | 30,641 students |
| Total Columns | 14 |
| Score Columns | MathScore, ReadingScore, WritingScore |
| Demographic Columns | Gender, EthnicGroup, ParentEduc, ParentMaritalStatus |
| Lifestyle Columns | PracticeSport, IsFirstChild, NrSiblings, TransportMeans, WklyStudyHours |
| Academic Prep Columns | LunchType, TestPrep |

## Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook (VS Code)

## Project Structure

```
Student-Result-Analysis/
├── Edafile.ipynb                          # Main analysis notebook
├── student_score.csv                      # Dataset
├── Student_Result_Analysis_Report.pdf     # Full written report with findings
└── README.md
```

## Data Cleaning

- Removed the redundant index column carried over from the CSV export.
- Standardized inconsistent category labels in `WklyStudyHours`.
- Checked all columns for null values before grouping or visualization.

## Analysis Performed

- Gender distribution
- Parent education vs. student scores
- Sports practice vs. student scores
- Number of siblings vs. student scores
- Outlier detection (boxplots)
- Ethnic group distribution
- Correlation between Math, Reading, and Writing scores
- Test prep completion vs. student scores

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/sarthaknatekar/Student-Result-Analysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Edafile.ipynb
   ```

## Full Report

A detailed written report with all charts and findings is available here: [`Student_Result_Analysis_Report.pdf`](./Student_Result_Analysis_Report.pdf)

## Author

**Sarthak Natekar**
[LinkedIn](https://www.linkedin.com/in/sarthak-natekar-4703902b3) · [GitHub](https://github.com/sarthaknatekar)
