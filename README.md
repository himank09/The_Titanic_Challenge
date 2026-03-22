# Titanic - Machine Learning from Disaster

My first Kaggle competition. Predicting passenger survival on the Titanic.

## Score
- Baseline (Random Forest): 0.77511
- Improved (Feature Engineering + Tuning): TBD

## Approach
- Feature engineering: extracted Title from Name, Age bands, Fare bands, Family size groups
- Model: Random Forest + Gradient Boosting with GridSearchCV tuning
- Cross-validation: 5-fold CV

## How to run
1. Clone the repo
2. Create a virtual environment: `python -m venv venv`
3. Activate it and install packages: `pip install -r requirements.txt`
4. Open `titanic1.ipynb` and run all cells

## Files
- `titanic1.ipynb` — main notebook
- `train.csv` / `test.csv` — Kaggle competition data
- `submission.csv` — final predictions