# Pharmaceutical Sales Analysis

This project contains a Jupyter notebook that solves the [Pharmaceutical Sales Data](https://roadmap.sh/projects/pharmaceutical-sales-data) activity from roadmap.sh using Python, Pandas, and Matplotlib.

## Activity Summary

The goal of the activity is to analyze a pharmaceutical sales dataset and answer business questions about medication categories, best-selling products, selected monthly top sellers, daily averages, and seasonality.

Questions covered in the notebook:

1. What are the total sales quantities for each medication category (ATC code)?
2. Which individual medication brands have the highest total sales volume?
3. What were the top 3 medications with the highest sales volume in January 2015, July 2016, and September 2017?
4. What was the best-selling medication in 2017?
5. Which medication category has the highest average daily sales?
6. Are respiratory medications (R03) sold more in specific months?

## Project Files

- `pharma_analysis.ipynb`: main notebook with the full analysis, charts, and conclusions
- `Data/salesdaily.csv`: dataset used in the activity
- `requirements.txt`: Python dependencies

## Requirements

- Python 3
- Jupyter Notebook or JupyterLab
- A virtual environment is recommended

## How To Run

### 1. Open a terminal in the project folder

```powershell
cd C:\Users\Gabriel\Documents\GitHub\Pharma-DataAnaly-Test
```

### 2. Create a virtual environment

```powershell
python -m venv .venv
```

### 3. Activate the virtual environment

PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

If PowerShell blocks script execution, run:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```powershell
pip install -r requirements.txt
python -m pip install notebook ipykernel
```

### 5. Start Jupyter

```powershell
python -m notebook
```

### 6. Open the notebook

In the browser, open:

- `pharma_analysis.ipynb`

### 7. Run the analysis

Use `Run All` in Jupyter, or execute the cells one by one from top to bottom.

## Notes

- The notebook uses the `salesdaily.csv` file inside the `Data` folder.
- The analysis works with ATC categories available in the dataset: `M01AB`, `M01AE`, `N02BA`, `N02BE`, `N05B`, `N05C`, `R03`, and `R06`.
- Some questions in the activity mention individual drug brands, but this dataset is structured by ATC category, so the answers are based on the available category-level data.

## Technologies Used

- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook
