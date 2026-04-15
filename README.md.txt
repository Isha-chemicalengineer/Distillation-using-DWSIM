# Surrogate Modeling of Binary Distillation Column using DWSIM and Machine Learning
## Overview
In this project, a surrogate model has been developed for a binary distillation column using data generated from DWSIM simulations. 
The objective is to predict key outputs such as condenser duty, reboiler duty, and product compositions based on operating conditions.
## Files Included
- Report.pdf – detailed explanation of methodology and results  
- DWSIM_ML_Dataset_Final.csv – dataset generated from simulations  
- Code.ipynb – implementation of machine learning models  
- DWSIM_flowsheet_file.dwxmz – simulation setup  
- Results_Summary.pdf – summary of model performance  
- README.md – instructions to run the project  
## Requirements
The following Python libraries are required:
- pandas  
- NumPy  
- matplotlib  
- scikit-learn  
## How to Run
1. Open the notebook (Code.ipynb) in Google Colab or Jupyter  
2. Upload the dataset file (DWSIM_ML_Dataset_Final.csv)  
3. Run all cells to train models and generate results  
## Models Used
- Random Forest  
- Support Vector Machine (SVM)  
- Neural Network  
## Results Summary
Among the models tested, the Neural Network showed the best overall performance, especially for predicting composition variables.
## Notes
- The dataset consists of converged simulation points  
- Input ranges were selected to maintain physically meaningful conditions  
## Author
ISHA JOSHI
