# NYC-CRIME-DATA
1. Data Collection
-Retrieved a publicly available dataset from NYC Open Data containing historical crime data (2000–2023) for 77 precincts.
-The dataset included columns such as borough, crime type, and year of occurrence.
2. Data Preparation
-Converted the dataset from an Excel file to a CSV format for compatibility with MySQL.
-Imported the dataset into MySQL and created a database for organization and efficient querying.
-Cleaned the dataset:
  *Ensured consistency in entries.
  *Replaced invalid data values with zeros.
  *Added a column to map precincts to boroughs.
3. Data Preprocessing
-Used Python libraries (pandas and numpy) to preprocess the data further.
-Filtered and grouped data by borough and crime type for analysis.
4. Exploratory Data Analysis (EDA)
-Analyzed the mean annual trends for each crime type across all boroughs from 2000 to 2023.
-Visualized trends using matplotlib and seaborn to identify patterns and outliers.
-Key observation: A significant rise in crime rates during the early 2020s (linked to COVID-19 resource limitations).
5. Prediction Modeling
-Created a forecasting algorithm:
   *Calculated year-over-year percentage changes for each crime type.
   *Used these averages to predict crime trends for the next 5 years.
-Evaluated predictions using:
   *Mean Absolute Error (MAE).
   *Root Mean Squared Error (RMSE).
