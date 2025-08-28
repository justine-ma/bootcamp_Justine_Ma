# Data Cleaning Strategy and Assumptions
1. First we will replace the "Unknown" city with a None value. 
2. We drop rows with too much missing data, namely row index 5 with three missing values. 
3. We drop the column extra_data. We assume that this information is not critical to analysis as there is too many missing values and there is no apparent information about what specific information extra_data is referring to. 
4. We assume that numeric null values are MCAR or MAR. Hence, we fill missing values in age, income, and score with the median.
5. We observe that age, income, score all do not have extreme outliers. Hence, we assume that the minmax values are representative and use the minmax method to scale the data.  