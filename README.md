# 🏠 House Hunter: Regression and Stacking (Top 3%)

In this project, we'll be building different regression models to predict the house price of a residential property. The analysis can be accessed [here](analysis/house-hunter-regression-stacking-top-3.ipynb).

**Author**: Po-Hsun (Ben) Chen

## Summary

In this regression project focused on predicting house prices, a comprehensive exploration of diverse regression models, including linear regression, decision trees, and ensemble methods, was conducted. Additionally, the project delved into the application of regularization techniques to enhance model generalization, and stacking methodologies were employed to harness the collective predictive power of multiple models, resulting in a robust and accurate framework for house price prediction.

## Data Source

The dataset used in this analysis contains 80 variables, all related to features of a residential house. This target variable is `SalePrice`, which is what we're trying to predict in this project. You can access the dataset [here](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).

## Dependencies

All required dependencies are listed in this [conda environment file](environment.yaml).

## How to Reproduce the Analysis

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/phchen5/house-hunter.git
   cd house-hunter
   ```

2. **Download the Dataset from the Source:**
   You may need to register for a Kaggle account. After you've downloaded the dataset, place the `sample_submission.csv`, `test.csv` and `train.csv` file within a `data/` folder located in the root. You may also place it anywhere else in the repository as you like, just be sure to edit the data source path within the analysis.
3. **Set Up and Activate Environment:**

   ```bash
   conda env create -f environment.yaml
   conda activate house-prediction
   ```

4. **Open the Notebook:**

   ```bash
   jupyter lab analysis/house-hunter-regression-stacking-top-3.ipynb
   ```

5. **Run the Cells and Have Fun Exploring!**

## Files

- `analysis/house-hunter-regression-stacking-top-3.ipynb`: Jupyter notebook containing the EDA code.
- `environment.yaml`: Conda environment file listing required dependencies.

