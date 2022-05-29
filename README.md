# Applied AI Challenge Hackathon
# Oil and Gas Industry Case

## Participant: Bulygin Maksim, 4th year of SPSUE (Saint-Petersburg State University of Economics)

Solving the hackathon problem from Gazpromneft. The task is to predict the timeseries of
oil flow rate for different holes around the geographic region.

## Pipeline

Pipeline of solution consists of:
- Data loading
- EDA, handling missing values
- Feature engineering, creating lags of target for each hole
- Train validation split (train size is 0.88) by time
- Fitting CatBoost and XGBoost on train, validation estimation
- SHAP and LASSO feature selection
- Final submit

Notebook with solution is presented in `solution_notebook.ipynb`.
Pitch presentation is presented in `pitch_presentation.pdf`.
