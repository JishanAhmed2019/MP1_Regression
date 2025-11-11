# MATH 3310 – MP1 Regression Project  
Instructor: Dr. Jishan Ahmed  
Weber State University  

This repository contains the notebook(s), data, and dependencies for the **MP1 Regression** project.

---

## 🧩 1. Clone this repository

Open **VS Code**, then in the built-in terminal run:

git clone https://github.com/JishanAhmed2019/MP1_Regression.git

cd MP1_Regression

---

## 🧠 2. Create and activate a virtual environment

### On macOS / Linux
source .venv/bin/activate

### On Windows (PowerShell)
. .\.venv\Scripts\Activate.ps1

---

## 📦 3. Install required packages

Make sure the environment is active (you should see (.venv) in your prompt), then run:

pip install -r requirements.txt

This installs numpy, pandas, matplotlib, statsmodels, scikit-learn, and other needed libraries.

---

## 💻 4. Open and run notebooks in VS Code

1. In VS Code, choose “File → Open Folder → MP1_Regression”.  
2. Open the notebook (for example, Regression_Analysis.ipynb).  
3. When prompted, select the Python kernel from .venv.  
4. Run each cell with **Shift + Enter** or use the “Run All” button.

---

## 📁 5. Data folder

- Small example data files (for example, .csv, .txt, .xlsx) are included in the data/ folder.  
- If any dataset is missing, see data/README.md for download instructions.

---

## 🧹 6. Common issues

| Problem | Fix |
|----------|-----|
| Command not found: python3 | Use `python` instead. |
| pip not recognized | Re-install Python and check “Add to PATH” during setup. |
| ModuleNotFoundError | Activate the environment before installing requirements. |
| Kernel not showing in VS Code | Run `python -m ipykernel install --user --name=.venv --display-name "MP1 (Python)"` |

---

## 📚 7. Getting help

If you encounter issues:
- Re-activate your environment and rerun `pip install -r requirements.txt`.
- Verify you’re inside the correct folder (MP1_Regression).
- Contact **Dr. Jishan Ahmed** via Canvas or email with a screenshot of the error.

---

**Happy analyzing! 📊**
