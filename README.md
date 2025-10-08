This project was developed as part of the Data and Information Quality course.
The assignment required executing a complete Data Preparation Pipeline on an assigned dataset, following these steps:
1. Data Profiling and Data Quality Assessment
2. Data Cleaning
  a. Data Transformation/Standardization (bringing everything to the same format, detecting and correcting typos, performing     wrangling operations, etc.)
  b. Error Detection and Correction (dealing with missing values and the detection and correction of potential outliers)
  c. Data Deduplication (detecting and handling non-exact duplicates)
3. Data Analysis
   a. Choose the type of analysis (classification-regression-clustering):
      i. Choose one column as the target column (categorical = classification OR numerical = regression)
            OR
      ii. Perform unsupervised clustering analysis
   b. Perform a data analysis pipeline on (1) the dirty dataset and (2) the cleaned dataset (model selection, training and testing)
   c. Compare the results using the right performance metrics (Precision, Recall, F1, etc. [Classification], MSE, RMSE, etc. [Regression], Silhouette, etc. [Clustering])

The project was mainly developed using the Python programming language and the pandas library for data manipulation and cleaning.
Pandas was used to handle data profiling, transformation, standardization, and error correction tasks efficiently within the Data Preparation Pipeline.

The dataset used in this project is: Comune-di-Milano-Attivita-commerciali-di-media-e-grande-distribuzione.csv.
It contains data about various commercial activities in the city of Milan, including the following columns:
Settore Merceologico, Insegna, Ubicazione, Tipo Via, Via, Civico, Codice Via, ZD, Superficie vendita, Superficie altri usi, Superficie totale
This dataset provides information about the different types of medium and large-scale commercial activities operating within the municipality of Milan.

Project Files:

DataQualityProject_Paoletti_Marino_Grassi.ipynb — main Jupyter Notebook containing the entire Data Preparation and Analysis pipeline.

Comune-di-Milano-Attivita-commerciali-di-media-e-grande-distribuzione.csv — source dataset.

Report/Project Report.pdf — final report describing the methodology and results.
