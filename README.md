# Life Expectancy — Linear Regression

A Jupyter Notebook project that explores and models global life expectancy using linear regression. The model achieves an R² score of approximately 0.85, demonstrating strong predictive performance.

## Key Highlights
- **Task:** Predict life expectancy using country-level features
- **Model:** Linear Regression (scikit-learn)
- **Achieved Score:** R² ≈ 0.85 (see notebook for details)

## Contents
- **Notebook:** [Life_Expectancy_Linear_Regression.ipynb](Life_Expectancy_Linear_Regression.ipynb)
- **Data:** Included in the repository ([Kaggle source](https://www.kaggle.com/))
- **Requirements:** Python 3.8+, pandas, numpy, scikit-learn, matplotlib, seaborn, notebook

## Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/PatelG108/Life-Expectancy-Linear-Regression-85-score-.git
cd Life-Expectancy-Linear-Regression-85-score-
```

**2. Install dependencies**
```bash
python -m venv .venv
source .venv/bin/activate   # macOS / Linux
.venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

**3. Run the notebook**
- Open `Life_Expectancy_Linear_Regression.ipynb` in Jupyter or [Google Colab](https://colab.research.google.com/github/PatelG108/Life-Expectancy-Linear-Regression-85-score-/blob/main/Life_Expectancy_Linear_Regression.ipynb).

## Project Overview
- **Data preprocessing:** Handle missing values, encode categorical variables, normalize features.
- **Exploratory analysis:** Distributions, pairplots, correlations, and feature importance.
- **Modeling:** Train/test split, fit linear regression, evaluate using R² and residual analysis.
- **Results:** Visualizations of predicted vs. actual values and residuals.

## How to Reproduce Results
- Open the notebook in Jupyter or Colab.
- Ensure the dataset is available in the expected path (see notebook instructions).
- Run all cells to reproduce analysis and plots.

## Recommended Dependencies (`requirements.txt`)
```
numpy
pandas
scikit-learn
matplotlib
seaborn
notebook
scipy
```

## License
This project is licensed under the MIT License.

## Author
**Amit Kumar**  
- [Kaggle](https://www.kaggle.com/)  
- [LinkedIn](https://www.linkedin.com/)