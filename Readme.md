# Algerian Forest Fires Regression Project

This project analyzes and models the Algerian Forest Fires dataset using regression techniques.

## Structure

- `Algerian Forest Fires/`
  - `Algerian_forest_fires.ipynb`: Data cleaning and exploratory data analysis (EDA).
  - `Model_Training.ipynb`: Regression model training and evaluation.
  - `data/`
    - `Algerian_forest_fires_cleaned_dataset.csv`: Cleaned dataset used for modeling.
    - `Algerian_forest_fires_dataset_UPDATE.csv`: Original/updated raw dataset.

## Workflow

1. **Data Cleaning & EDA**  
   Conducted in [`Algerian_forest_fires.ipynb`](Algerian Forest Fires/Algerian_forest_fires.ipynb), including:
   - Handling missing values
   - Feature engineering (e.g., region column)
   - Data type conversions
   - Exploratory visualizations

2. **Model Training**  
   Performed in [`Model_Training.ipynb`](Algerian Forest Fires/Model_Training.ipynb), including:
   - Feature selection and scaling
   - Training regression models (Linear, Ridge, Lasso, ElasticNet)
   - Model evaluation (MAE, R², plots)

## Usage

1. Place the raw dataset in `Algerian Forest Fires/data/`.
2. Run the notebooks in order:
   - Start with `Algerian_forest_fires.ipynb` for data preparation.
   - Proceed to `Model_Training.ipynb` for modeling and results.

## Requirements

- Python 3.12+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, scikit-learn

Install dependencies:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn