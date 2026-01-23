# Data Cleaning Study Case using Python  

in this case we use Customer Satisfaction Survey as Dataset.  
The Dataset was collected by on field survey.

Data cleaning is a foundational process in the data science lifecycle, and its role cannot be overemphasized when trying to uncover insights and generate reliable answers. More often than not, data will always be dirty in the real world, and data cleaning cannot be completely avoided.  

library used:  
numpy  
pandas  
seaborn  
matplotlib  


we use 9 steps to clean the dirty dataset:  
STEP 1 : LOAD & INSPECT  
STEP 2 : CLEAN COLUMN NAMES  
STEP 3 : FIX DATA TYPES  
STEP 4: REMOVE DUPLICATES  
STEP 5: HANDLING OUTLIERS  
STEP 6: CLEAN STRINGS / TEXT DATA  
STEP 7: STANDARDIZE VALUES  
STEP 8: RENAME / DROP / REORDER COLUMNS  
STEP 9: HANDLE MISSING DATA  

The output of the file will be exported in csv or xls file

Dataset Shape:
(181756, 22)

Dataset info:
RangeIndex: 181756 entries, 0 to 181755
Data columns (total 22 columns):

### Dataset Information

| # | Column | Non-Null Count | Dtype |
|:---|:---|:---|:---|
| 0 | Phone Number | 181,756 non-null | int64 |
| 1 | Region | 180,586 non-null | object |
| 2 | area | 180,586 non-null | object |
| 3 | Sales Area | 180,586 non-null | object |
| 4 | Micro Cluster | 180,586 non-null | object |
| 5 | site_id | 83,881 non-null | object |
| 6 | Level | 181,756 non-null | int64 |
| 7 | Category | 181,756 non-null | object |
| 8 | Hal apa yang membuat kamu puas? | 99,955 non-null | object |
| 9 | Other Choice-Lainnya (Satisfaction) | 8,578 non-null | object |
| 10 | Other Group Satisfaction | 86,057 non-null | object |
| 11 | Hal apa yang membuat kamu tidak puas? | 53,705 non-null | object |
| 12 | Other Choice-Lainnya (Dissatisfaction) | 7,355 non-null | object |
| 13 | Other Group Dissatisfaction | 52,239 non-null | object |
| 14 | Data Usage | 177,308 non-null | float64 |
| 15 | Survey Status | 181,755 non-null | object |
| 16 | Week | 181,756 non-null | int64 |
| 17 | Survey Sent | 181,756 non-null | object |
| 18 | Month | 181,756 non-null | object |
| 19 | Speed | 180,676 non-null | float64 |
| 20 | Billing | 180,924 non-null | float64 |
| 21 | Wage | 181,126 non-null | float64 |

dtypes: float64(4) ,  int64(3),  object(15)











