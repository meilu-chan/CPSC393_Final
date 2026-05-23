PROJECT TITLE
Online Apparel Retail Shopping Analysis

PROJECT DESCRIPTION
This project applies machine learning techniques to a synthetic online apparel retail dataset to analyze customer behavior, predict promotional usage, and identify customer segments. The goal is to support more personalized marketing strategies in an oversaturated digital retail environment. The project implements K-Means clustering, Random Forest classification, and K-Nearest Neighbors (KNN) classification using Python and Google Colab.

SETUP INSTRUCTIONS
This project was developed and executed in Google Colab.  
If running locally, ensure Python 3.x is installed along with the following libraries:
    - pandas
    - numpy
    - scikit-learn
    - matplotlib
    - seaborn
    - plotnine
    - scipy

To install dependencies locally:
    pip install pandas numpy scikit-learn matplotlib seaborn plotnine scipy

DATASET INFORMATION
Dataset: Customer Shopping Trends Dataset (Kaggle, 2023)  
Rows: 3,900  
Features: 18 (demographic, behavioral, transactional)  
Download link:
https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset

Upload the CSV file into the Google Colab notebook or place it in the same directory if running locally.

HOW TO RUN THE CODE
Option 1: Google Colab 
    1. Open the provided .ipynb notebook in Google Colab.
    2. Upload the dataset when prompted.
    3. Run all cells in order:
        - Data Understanding
        - Preprocessing
        - Model Development
        - Hyperparameter Tuning
        - Evaluation and Visualization

Option 2: Local Execution
    1. Clone the repository:
        git clone https://github.com/<your-username>/<repo-name>.git
    2. Install dependencies (see above).
    3. Open the notebook in Jupyter Notebook or VS Code.
    4. Ensure the dataset is in the same directory.
    5. Run all cells sequentially.

RESULTS SUMMARY
K-Means Clustering:
    - Identified 4 distinct customer personas for targeted marketing
    - Useful for identifying characteristics of current audiences 

Random Forest Classification:
    - Strongest predictive performance for promo-use behavior
    - Useful for targeted promotional strategies

KNN Classification:
    - High recall for identifying promo-responsive customers
    - Complements Random Forest for refining promotional targeting

LIMITATIONS
    - The dataset is synthetic and may not fully reflect real-world behavior
    - No temporal or browsing-level features included
    - K-Means cluster separation can be improved with additional variables

CONTRIBUTORS
    - Chantelle Chan
    - Kyle Cadigal
    - Emmitt Sherer

CODING REFERENCES
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.select_dtypes.html
- https://www.w3schools.com/python/python_ml_knn.asp
- https://www.geeksforgeeks.org/machine-learning/hyperparameter-tuning/
- https://www.kaggle.com/code/melihkanbay/knn-best-parameters-gridsearchcv

