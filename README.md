# Housing and Neighborhood Analysis

Exploratory data analysis of residential-property data, with a focus on housing characteristics, sale prices, and neighborhood patterns. The project uses the Ames Housing dataset and presents its analysis in a Jupyter notebook and a companion PDF report.

## Highlights

- Profiles a dataset of 1,460 homes and 81 variables.
- Examines data types, descriptive statistics, distributions, and missing values.
- Cleans missing numeric and categorical values using median and mode imputation.
- Standardizes numeric features and applies Principal Component Analysis (PCA).
- Explores relationships among living area, lot area, overall quality, and sale price.
- Normalizes neighborhood labels and groups less common neighborhoods.
- Uses the elbow method and K-means clustering to identify property segments.

## Project structure

```text
.
|-- Data/
|   `-- housing_data.csv                       # Input housing dataset
|-- src/
|   `-- HousingData_Neighborhood_analysis.ipynb # Analysis notebook
|-- Out/
|   `-- HousingData_Neighborhood_analysis.pdf   # Exported analysis report
`-- README.md
```

## Requirements

- Python 3.10 or later
- Jupyter Notebook or JupyterLab
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install the Python dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Run the analysis

From the project root, start Jupyter:

```bash
jupyter notebook
```

Then open `src/HousingData_Neighborhood_analysis.ipynb` and run the cells in order. The notebook reads the dataset from `../Data/housing_data.csv`, so keep the existing folder structure intact.

## Output

The exported report is available at [Out/HousingData_Neighborhood_analysis.pdf](Out/HousingData_Neighborhood_analysis.pdf). It contains the visualizations and results produced during the exploratory analysis.

## Post Script

This is a sample exploratory data analysis project. The clusters are intended for descriptive segmentation and should be validated before being used for pricing or business decisions.
