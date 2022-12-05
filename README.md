# TDI_Capstone: Childcare and Work in America
## Requirements:
### 1. Clear Business objective
Clear business objective and project results outlined in report file. 
### 2. Data Ingestion: 
Requirements met through harmonizing data from multiple sources and non-trivial processing of existing data sets. \
Data on daycare closures comes from US Database of Child Care Closures during COVID-19 paper https://osf.io/k3t98/?view_only \
Data on childcare costs and childcare's effects on the workforce from the Census Bureau Survey of Income and Program Participation (SIPP) \
SIPP data processing in notebook SIPP_Data_Processing.ipynb. \
I have included a csv of processed data. The original (unprocessed) data files are too large to include here but can be downloaded from the census bureau at https://www.census.gov/programs-surveys/sipp.html
### 3. Visualizations:
 Project includes chloropleth maps showing childcare closure data by state and zip code. \
 Project also includes line graphs showing closure information over time. \
 Project includes histogram of feature importance generated in ML_Model.ipynb to visualize which features the logistic regression model deteremined were most important.
### 4. Demonstration of Machine Learning
Project includes a machine learning model which uses the processed SIPP data to predict whether a person will have conflicts between work hours and childcare needs. \
Machine learning model is in the file ML_Model.ipynb


