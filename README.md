# MISSING DATA
I always dread opening a dataset because it will almost always have null values.These gaps in data, seemingly innocuous at first glance,
hold the potential to unravel the most meticulously crafted analyses, casting shadows of doubt on our conclusions and decisions.
Missing values are the silent saboteurs of data analysis, lurking in datasets with the power to distort our understanding and hinder our progress.

## Types and Causes of Missing Data:
Missing data can be classified into different types based on patterns and causes. Understanding these types and their underlying causes is fundamental to effectively address them in the data analysis process.

### Types of Missing Data:

#### Missing Completely at Random (MCAR):
In the MCAR pattern, the missingness of data points is entirely random and unrelated to any observed or unobserved variables.
This type of missing data implies that there is no systematic reason for data points to be missing.
An example could be survey data where participants fail to respond to questions due to factors like momentarily distracted survey takers or technical glitches.

#### Missing at Random (MAR):
MAR refers to missing data where the probability of data being missing depends on observed variables but not on unobserved or missing data.
In other words, the missingness is related to the available information in the dataset.
An example might be a survey where some demographic information is missing for participants who chose not to answer certain sensitive questions.

#### Missing Not at Random (MNAR):
MNAR occurs when the probability of data being missing depends on both observed and unobserved variables.
This is the most challenging type of missing data to handle because the missingness itself can carry valuable information.
An example could be a clinical trial where patients with more severe side effects may be less likely to return for follow-up assessments.

### Common Causes of Missing Data:

#### Data Entry Errors:
Data entry errors can lead to missing values when data is not recorded correctly during data collection or input.
These errors might include typos, misinterpretation of data, or technical issues during data entry.

#### Non-Response:
Non-response occurs when individuals or entities in a study do not provide answers to specific questions or fail to participate in data collection.
It can happen due to various reasons, including unwillingness to respond, survey fatigue, or sensitive or intrusive questions.

#### Data Corruption:
Data corruption refers to instances where data is altered or damaged, leading to missing or incorrect values.
Corruption can occur due to hardware or software failures, file format issues, or transmission errors.

#### Data Collection Limitations:
Sometimes, data cannot be collected for certain variables due to logistical or ethical constraints.
For example, in a medical study, certain medical tests may not be administered to all patients for safety or cost reasons, leading to missing medical data.
