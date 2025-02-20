# NFL Prediction Model  

This repository contains a machine learning model designed to predict NFL game outcomes using historical data from the 2023/2024 season.

---

## Project Overview  
- Uses Python for data processing and predictive modeling.  
- Implements feature engineering based on team performance metrics.  
- Designed to analyze trends in NFL games and predict results.  

---

## Project Structure  
The project is organized as follows:

- **NFL Project/** → Contains the main notebook and generated output files
  
  - `NFL-Prediction-Model_JohnReed.ipynb` → Jupyter Notebook with full code  
  - **CSV output files** → Generated while running the notebook, used for model predictions and analysis
  
- **resources/** → Data folder  
  - `NFLNFL.xlsx` → Raw data source (2023/2024 NFL Season)
    
- `requirements.txt` → Dependencies

- `README.md` → Project documentation  

---

## Quick Access to Code & Results  
The Jupyter Notebook (`NFL-Prediction-Model_JohnReed.ipynb`) has already been executed, meaning **all code cells have been run, and outputs are visible immediately**.  

 - **If you just want to browse the results**, you can view the `.ipynb` file directly in this GitHub repository without setting up anything.  
 - **If you want to run the code yourself**, follow the setup instructions below to create a virtual environment and execute the notebook.

---

## Installation & Setup  

```bash 
Run the following commands in your terminal:

### 1. Clone the Repository  
git clone https://github.com/jrnumber10/NFL-Prediction-Model.git
cd NFL-Prediction-Model

### 2. Set up virtual environment
python3 -m venv venv
source venv/bin/activate

### 3. Install dependencies
pip install -r requirements.txt

### 4. Run the Jupyter Notebook
jupyter notebook
```

Then open NFL-Prediction-Model_JohnReed.ipynb in Jupyter.

---

## Technologies & Libraries Used

This project utilizes the following libraries:

```bash
# Core Libraries  
python (3.x)  
numpy  # Numerical operations  
pandas  # Data manipulation  

# Machine Learning & Statistical Modeling  
scikit-learn  # Model evaluation  
statsmodels  # Statistical modeling  

# Visualization  
matplotlib  # Plots and graphs  
seaborn  # Statistical visualization  

# Utilities  
pickle  # Saving/loading models  
tabulate  # Formatting tables in outputs
```
For all dependencies, see requirements.txt

---

## Dataset & Features

- **Input Data**: Historical NFL team statistics from the **2023/2024 season**, compiled from [ESPN](https://www.espn.com/nfl/stats) and [Pro-Football-Reference](https://www.pro-football-reference.com/). The combined dataset is stored in [`NFLNFL.xlsx`](resources/NFLNFL.xlsx).
- **Output**: Predictions of upcoming game scores.
- **Processing**: Data is cleaned, transformed, and used in regression models to generate predictions.

---

## Notes  
- Ensure the virtual environment is activated before running the notebook.  
- The dataset (`NFLNFL.xlsx`) can be updated if you want to test new data.  
- The model may require updates as NFL trends evolve over time.  

---

## Author  
John Reed  
📧 Contact: Johnreedkeenagh@gmail.com  
🔗 GitHub: Jrnumber10  



