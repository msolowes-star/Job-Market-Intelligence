# Job Market Intelligence

## Project Overview
This data analytics hackathon explores job market trends, in-demand technical skills, remote work opportunities, and salary patterns. It also uses machine learning to predict salaries for data-related roles.

## Data Sources
- Hugging Face: Historical job postings from the `lukebarousse/data_jobs` dataset (10,000 sampled records).
- Remotive API: Remote job postings and extracted technical skills.
- Kaggle: Data Science Salaries 2023 dataset (3,755 records before deduplication).

## Tools and Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Hugging Face Datasets, Google Colab, and Excel.

## Project Workflow
1. Collect job-market data from three sources.
2. Clean and prepare datasets, including missing values and duplicates.
3. Analyze job categories, technical skills, remote opportunities, and salaries.
4. Visualize important trends.
5. Train and evaluate a Random Forest salary prediction model.
6. Export analysis results to Excel and CSV.

## Machine Learning Results
After removing duplicate records before splitting the data:
- Model: Random Forest Regressor
- R²: approximately 0.36
- Mean Absolute Error: approximately $39,733
- Improvement in MAE compared with median baseline: approximately 25.8%

These results describe predictive performance on the held-out test set, not causal relationships.

## Limitations
The historical job-posting sample is not representative of the entire current job market, many historical salary values are missing, and the datasets cover different populations and time periods.

## How to Run
1. Open `Hackathon2_Job_Market_Intelligence.ipynb` in Google Colab.
2. Install dependencies as indicated in the notebook.
3. Upload `ds_salaries.csv` when prompted.
4. Run the notebook cells in order.

## Project Deliverables
- Executable Jupyter notebook
- Job market visualizations and analysis
- Random Forest salary prediction model
- Excel and CSV exports
