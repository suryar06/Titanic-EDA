Titanic Exploratory Data Analysis (EDA)

Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The objective is to analyze passenger data, identify patterns, and gain insights into factors affecting survival.

Dataset
The dataset contains information about Titanic passengers, including:

- Passenger ID
- Age
- Gender
- Passenger Class
- Fare
- Embarkation Port
- Family Size
- Survival Status

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

Data Cleaning

The following preprocessing steps were performed:

- Filled missing values in the Age column using mean values.
- Filled missing values in the Embarked column using mode values.
- Removed the Cabin column due to excessive missing values.

Analysis Performed

1. Survival Rate by Age Group
Passengers were categorized into:
- Child
- Teen
- Young Adult
- Adult
- Senior

The survival rate of each group was analyzed.
2. Survival Rate by Embarkation Port
Analyzed how survival rates varied across different ports:
- C
- Q
- S

3. Survival Rate by Family Size
Created a new feature called FamilySize and examined its impact on survival.

Visualizations

- Age Distribution Histogram
- Survival Rate by Age Group
- Survival Rate by Embarkation Port
- Survival Rate by Family Size
- Correlation Heatmap

Key Insights

- Children had the highest survival rate.
- Senior passengers had the lowest survival rate.
- Survival rates varied based on embarkation port.
- Family size influenced survival probability.
- Passenger characteristics played an important role in survival outcomes.

Project Structure

```
Titanic-Exploratory-Data-Analysis/
│
├── Titanic_Dataset.csv
├── Task3_Titanic_EDA.ipynb
├── README.md
└── images/
```

How to Run

1. Clone the repository

```bash
git clone <repository-link>
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells in `Task3_Titanic_EDA.ipynb`

