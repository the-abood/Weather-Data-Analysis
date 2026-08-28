# Weather Data Analysis — Linear Regression

A beginner-friendly notebook that explores a weather dataset and predicts
temperature using regression models.

## What's inside

- **Data cleaning** — loading the CSV, checking and removing missing values
- **Exploration** — summary statistics, a correlation heatmap, and an outlier
  boxplot
- **Feature engineering** — encoding the `Location` column and scaling
  features with `RobustScaler`
- **Modeling** — training and evaluating a Linear Regression model
- **Model comparison** — comparing Linear, Ridge, and Lasso regression using
  MSE and R² score, with a bar chart summary

Every section has a heading and the code includes short inline comments
explaining what each line does.

## Requirements

- Python 3
- pandas, numpy, matplotlib, seaborn, scikit-learn

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

Open `Weather_Data_Analysis_Linear_Regression.ipynb` in Jupyter Notebook,
JupyterLab, or VS Code and run the cells in order. You'll need to update the
CSV file path in the "Load the Dataset" section to point to your own copy of
the weather data.
