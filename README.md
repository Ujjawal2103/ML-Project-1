\# Industrial Classification — Machine Learning Pipeline



\## Overview



This project explores machine learning models for an industrial classification task. It includes exploratory data analysis, baseline modeling, tree-based models, feature engineering, and an ensemble approach.



\## Project Structure



\- `src/01\_eda.py` — Exploratory data analysis

\- `src/02\_baseline\_logreg.py` — Logistic Regression baseline

\- `src/03\_random\_forest.py` — Random Forest model

\- `src/04\_xgboost.py` — XGBoost model

\- `src/05\_feature\_engineering.py` — Feature engineering experiments

\- `src/06\_xgboost\_fe.py` — XGBoost with engineered features

\- `src/07\_ensemble.py` — Ensemble modeling

\- `src/features.py` — Feature utilities

\- `submissions/` — Generated submission CSV files

\- `results.md` — Cross-validation and leaderboard results

\- `requirements.txt` — Python dependencies



\## Setup



Use Python 3.10 or newer, then install the dependencies:



```bash

pip install -r requirements.txt

```



\## Data



Place the required input files in a local `data/` directory:



\- `student\_dataset.csv`

\- `test.csv`

\- `sample\_submission.csv`



The datasets are not included in this repository. Ensure you have permission to use them.



\## Running the Pipeline



Run scripts from the repository root, in the appropriate order, after verifying their input paths and dependencies:



```bash

python src/01\_eda.py

python src/02\_baseline\_logreg.py

python src/03\_random\_forest.py

python src/04\_xgboost.py

python src/05\_feature\_engineering.py

python src/06\_xgboost\_fe.py

python src/07\_ensemble.py

```



Some steps may depend on outputs produced by earlier scripts. Check each script's configuration and expected input files before running it.



\## Results



See \[`results.md`](results.md) for recorded cross-validation results, public leaderboard scores, and feature-engineering experiments.



\## Reproducibility



Model scores may vary with data splits, random seeds, library versions, and evaluation settings. Use the recorded settings and results as a reference when reproducing experiments.

