[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alwinmillil/titanic-classification/blob/main/titanic_classification.ipynb)
# Titanic - Survival Prediction (Beginner Data Science Project)

**Author:** Alwin (MSc Data Science)

## Project summary
Predict whether a passenger survived the Titanic disaster using basic passenger features (class, sex, age, fare, family size, and port of embarkation). This notebook demonstrates a complete workflow: EDA → data cleaning → modeling → evaluation → saving model.

## Files in this repository
- `titanic_classification.ipynb` — the Jupyter/Colab notebook with step-by-step code.
- `titanic_rf_model.joblib` — saved Random Forest model (optional / after training).
- `requirements.txt` — Python packages required to run the notebook locally.
- `README.md` — this file (you are reading it).
- `.gitignore` — recommended files to ignore (virtualenv, cache, etc.).

## How to run (Easiest - Google Colab)
1. Open https://colab.research.google.com/.
2. Click **File → Upload notebook** and upload `titanic_classification.ipynb` from your computer.
3. Run the cells in order (select a cell and press **Shift + Enter**).

## How to run (Locally on your PC)
1. Install Python 3.8+.
2. Download or clone this repository to a local folder.
3. Open a terminal (PowerShell on Windows) and run:
```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```
4. Launch Jupyter Notebook and open `titanic_classification.ipynb`:
```bash
jupyter notebook
# then in your browser open the notebook file
```

## Quick notes
- If you train the model in Colab, you can download `titanic_rf_model.joblib` (File → Download) and upload it to the repository if you want to store it.
- Do not upload very large model files (>50–100 MB) to GitHub. Use cloud storage for large files (Google Drive, AWS S3).

## Example results (your run may vary)
- Logistic Regression accuracy (example): 0.78
- Random Forest accuracy (example): 0.82

## Next steps / improvements
- Feature engineering: extract titles from `Name` (Mr, Mrs), create family-size features.
- Hyperparameter tuning (GridSearchCV or RandomizedSearchCV).
- Deploy as a Streamlit app for interactive use.
- Add a short report or presentation slides in `/docs`.

## Contact
If you need help running the notebook or uploading files, message me (or contact the person who created the repo).
Added Colab button
---
