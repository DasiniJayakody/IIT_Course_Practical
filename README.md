# IIT Course Practical — Python Basics & Titanic Notebooks

Overview

- Collection of educational Jupyter notebooks for Python basics and Titanic analysis (EDA + simple ML).
- Notebooks included:
  - Python Basics.ipynb — introductory Python examples (printing, lists, dictionaries, simple I/O).
  - Titanic_EDA.ipynb — exploratory data analysis using pandas, matplotlib, seaborn.
  - Titanic_ML.ipynb — simple preprocessing and a Decision Tree classifier using scikit-learn.

Requirements

- Python 3.8+ recommended.
- Install required packages:
  - pip install pandas numpy matplotlib seaborn scikit-learn jupyter

Data

- Titanic_EDA.ipynb expects a CSV file named `train.csv`.
  - Place `train.csv` in this repository root or update the read_csv path in the notebook.
  - Example placement: `c:\Users\dasin\OneDrive\Desktop\IIT\IIT_Course_Practical\train.csv`
- Titanic_ML.ipynb uses seaborn's built-in titanic dataset (no external CSV needed).

How to run

1. Create and activate a virtual environment (optional but recommended):
   - python -m venv .venv
   - .venv\Scripts\activate (Windows) or source .venv/bin/activate (macOS/Linux)
2. Install packages:
   - pip install pandas numpy matplotlib seaborn scikit-learn jupyter
3. Launch Jupyter:
   - jupyter notebook
4. Open and run the notebooks in the browser.

Notes & tips

- Titanic_EDA.ipynb uses an absolute Colab-style path (`/content/train.csv`) in the provided notebook — change it to a local relative path (`train.csv` or `data/train.csv`) before running locally.
- Save large datasets in a `data/` folder and update notebook paths accordingly.
- For reproducible environments consider adding a requirements.txt or using pip freeze.

License

- Use for learning and teaching. Add a license file if you intend to share or publish.
