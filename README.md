# Wine Quality Analysis

This repository contains a comprehensive analysis of red wine quality using data science and machine learning techniques. The main analysis is performed in the Jupyter notebook `Wine_Quality_Analysis_py.ipynb`.

## Dataset

The dataset used for this project is the [Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality) from the UCI Machine Learning Repository, specifically focusing on red wine variants. It contains physicochemical properties and quality ratings for different wine samples.

## Project Steps

The analysis covers the following steps:

1. **Data Loading and Exploration**
    - Load the dataset and display the first few rows.
    - Explore column types and data distributions.
    - Check for missing values and duplicates.

2. **Data Cleaning**
    - Remove duplicate rows from the dataset.
    - Verify there are no missing values.

3. **Feature Engineering**
    - Create a new categorical column `quality_label` based on the original `quality` score:
        - `low` for scores ≤ 4
        - `medium` for scores 5–6
        - `high` for scores ≥ 7
    - Drop the original `quality` column after label creation.

4. **Data Visualization**
    - Use boxplots and other visualizations to understand the distribution of features and labels.

5. **Further Analysis**
    - Statistical summaries
    - Correlation analysis
    - (Optional) Model building for wine quality prediction

## Requirements

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib

You can install the dependencies using:

```bash
pip install pandas numpy seaborn matplotlib
```

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/fayezmuhammed/Wine-Quality-Analysis.git
    cd Wine-Quality-Analysis
    ```

2. Download the `winequality-red.csv` dataset from [UCI ML Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/) and place it in your working directory (or update the notebook path as needed).

3. Open and run the Jupyter notebook:

    ```bash
    jupyter notebook Wine_Quality_Analysis_py.ipynb
    ```

   or open it in [Google Colab](https://colab.research.google.com/github/fayezmuhammed/Wine-Quality-Analysis/blob/main/Wine_Quality_Analysis_py.ipynb).
