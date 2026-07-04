# Data Analysis With Python

A data analysis project built around the **Adult (Census Income)** dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/2/adult). The project explores the dataset using Python in a Jupyter Notebook.

## About the Dataset

The Adult dataset contains U.S. Census data and is commonly used for classification tasks that predict whether a person's income exceeds $50K/year based on demographic and employment attributes such as:

- Age, sex, and race
- Workclass and occupation
- Education level
- Marital status and relationship
- Hours worked per week
- Native country
- Income (target: `<=50K` or `>50K`)

## Repository Contents

| File | Description |
|---|---|
| `Data Analysis Project.ipynb` | Jupyter Notebook containing the data loading, cleaning, exploration, and analysis |
| `adult.csv.zip` | Compressed CSV file with the raw Adult dataset |

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- Common data analysis libraries, e.g.:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn jupyter
  ```

### Running the Project

1. Clone the repository
   ```bash
   git clone https://github.com/algovista-collab/Data-Analysis-With-Python.git
   cd Data-Analysis-With-Python
   ```
2. Unzip the dataset
   ```bash
   unzip adult.csv.zip
   ```
3. Launch Jupyter Notebook
   ```bash
   jupyter notebook "Data Analysis Project.ipynb"
   ```
4. Run the cells in order to reproduce the analysis.
