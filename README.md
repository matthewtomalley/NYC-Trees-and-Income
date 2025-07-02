# Trees and Income in NYC

Do income and trees correlate in NYC neighborhoods?

I initially used a dataset I accessed from a tutorial, and had some surprising findings. That work is in eda.ipynb.

To do some further analysis, I accessed the full dataset through NYC Open Data, which has 45 columns--much more information. That analysis is in eda_2.ipynb.

## Structure

The project is organized as follows:

- **`data/`** → Stores datasets at different stages:
  - **`data/raw/`** → Raw data.
  - **`data/processed/`** → Data ready for modeling
- **`models/`** → Will contain trained models
- **`src/app.py`** → Main Python script where project will run.
- ** eda.ipynb ** notebook with all EDA
- **`src/utils.py`** → Auxiliary functions, such as database connection.
- **`requirements.txt`** → List of required Python packages.



