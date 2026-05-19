# Customer Churn Data Preprocessing

Data preprocessing and cleaning project focused on a telecom customer churn dataset.

This project aims to identify data quality issues, handle missing values, standardize categorical variables, and prepare the dataset for future machine learning models focused on churn prediction.

---

## Project Objective

The main goal of this project is to perform data preprocessing on customer churn data, ensuring the dataset is clean, consistent, and ready for exploratory analysis or predictive modeling.

Key tasks performed:
- Missing value treatment
- Data consistency checks
- Categorical value standardization
- Column renaming and standardization
- Final dataset preparation for machine learning

---

## Dataset

The dataset contains telecom customer information, including:

- Customer demographics
- Contract information
- Payment methods
- Internet and phone services
- Churn status

Target variable:
- **Churn** → indicates whether the customer canceled the service.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```bash
CHURN-ANALYSIS-TELECON/
│
├── data/
│   └── CHURN_TELECON_MOD08_TAREFA.csv
│
├── images/
│   └── distribuicao_phoneservice.png
│
├── notebook/
│   └── churn_analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Data Preprocessing Steps

### 1. Initial Inspection
- Dataset loading
- Shape analysis
- Data types verification
- Initial preview

### 2. Missing Values Treatment
- Missing value identification
- Percentage analysis
- Row removal for low missing-rate variables
- Mode imputation for categorical variables

### 3. Data Cleaning
- Inconsistent label detection
- Standardization of categorical values
- Typo correction and capitalization normalization

Examples:
- `M`, `F`, `f` → standardized to `Male` and `Female`
- `dsl` → standardized to `DSL`

### 4. Column Standardization
Columns were renamed to English using snake_case convention.

Example:
- `Genero` → `gender`
- `Pagamento_Mensal` → `monthly_payment`

---

## Output

The final dataset is:
- cleaned
- standardized
- consistent
- ready for machine learning applications such as churn prediction.

---

## How to Run

Clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/churn-analysis-telecon.git
```

Enter the project folder:

```bash
cd churn-analysis-telecon
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## Author

**Juliane Rocha**

GitHub: https://github.com/julianperocha
LinkedIn: https://www.linkedin.com/in/julianeprocha/