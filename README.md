# Decision Trees, Bagging and Boosting on Olivetti Faces

**Name:** Ashwani Sah  **Roll number:** M26MAC007

All code is in `assignment.ipynb`. Bagging and SAMME boosting are implemented
from scratch; only `DecisionTreeClassifier` comes from scikit-learn.
Raw flattened pixels only (no PCA).

## Reproduce

```bash
git clone https://github.com/Ashwanishah/olivetti-ensembles.git
cd olivetti-ensembles
pip install -r requirements.txt
jupyter nbconvert --to notebook --execute assignment.ipynb --output assignment_rerun.ipynb
```

Or open `assignment.ipynb` and run **Kernel → Restart & Run All**.

## Files
- `split.json`: saved 6/2/2 split per identity (seed = digits of roll number)
- `q3_resamples.npy`: the 30 resampled training sets for Q3
- `configs/config.json`: all grids and selected settings
- `figures/`: every figure in the report
- `logs/final_run.html`: outputs of the final run
- `requirements.txt`: environment
