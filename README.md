# COMP90072 Complex Systems Project

## Project Overview

This project is for the Complex Systems. The project studies the Bak–Tang–Wiesenfeld (BTW) sandpile model, by analyzing self-organized criticality (SOC) and avalanche statistics.

This repository includes the code file and all LaTeX files needed to generate the final report. All project code is included in `Final_Code.ipynb`. This notebook contains the model code, tests, simulations, and outputs used in the report. The final report is included as `FinalReport.pdf`.

---

## File Description

### `Final_Code.ipynb`

The notebook contains: **Sandpile Model Definition**, **Simulation Wrapper**, **Model Tests**, **Project Question Simulations**. The detailed code structure can be found in Section **3.1** of the report. 

### `FinalReport.pdf`

This is the final report PDF.

The report includes:

- Introduction of the project
- BTW sandpile model definition and Abelian property discussion
- Model implementation
- Model extension

---

### LaTeX Files

The repository also includes the LaTeX files used to generate `FinalReport.pdf`, such as:

- main `.tex` file
- bibliography file
- figures folder
- other files needed for Overleaf compilation

These files can be used to reproduce or edit the final report.

---

## How to Run the Code

Use Jupyter Notebook to open the code file: Final_Code.ipynb. 

The notebook has already been organized in a clear order. To reproduce the results, just need to run the cells from top to bottom. 

The main Python packages used are:

- numpy
- matplotlib
- scipy
- tqdm

If any package is missing, install it with: pip install numpy matplotlib scipy tqdm. 