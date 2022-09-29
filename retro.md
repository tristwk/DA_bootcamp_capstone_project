
### Takeaways 

#### Data Cleaning
1. Set up a flow/SOP for Data cleaning process:   
     [ ] import pandas or other packages  
     [ ] import data  
     [ ] Check info on the whole dataframe: `df.info()`, `df.shape`, `df.describe()`, `df.head()`  
     [ ] Check columns: `df.columns` modify columns' names into **lower case, _ instead of other signs**  
     [ ] if too many columns, select needed columns and store them into a new dataframe: `df = df[['column_name xxxxx']]`  
     [ ] Check and change data type: `.astype(datatype)`, `pd.to_datetime()`, `.dt.year`  
     [ ] Check null values: `df.insa.sum()`: investigate if its reasonable and should be kept or not. **take notes on the findings!**)   
     [ ] Check duplicates: `df.duplicated(subset 'column_name')`   
     [ ] Check outliers: `.describe()`: investigate if its reasonable and should be kept or not. **take notes on the findings!**  
     [ ] Check values for each columns:`df['column_name'].value_counts()`   
     [ ] Drop null values or fillna()  
     [ ] Data Aggregation or create variables: extract a string, split columns, into booleans etc.   
     
     
2. .query() or filtering with `df[df[_condition_]]`: ????confirm with silke  

3. Deal with null values before data aggregation or CASE(): if null values are included, the returned values could be incorrect  
4.  
