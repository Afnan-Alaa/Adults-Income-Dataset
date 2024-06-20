The dataset shows adults' income census which includes the following features: 
Age: how old is the adult in this census
Race: The ethnicity of the adult, white, black, asian, other
Sex: Gender
Education: The highest level of education reached
Occupation: His current job
Work Class: whether he is self employed, private employee or other
Working Hours: Number of working hours
Martial Status: Whether married, single, divorced, widowed, or other
Relationship: Whether in a Family or not
First, I cleaned the data by removing duplicates, filling out missing values while dropping others. I also dropped a column that had a final weight, which didn't contribute to the analysis.
Then I showed some descriptive statistics for the variables, followed by univariate analysis in which I explored age, sex, race and income.
Finally, I did multivariate analysis, aiming to explore the factors affecting income, and which categories had high income.
The files contains code file, csv that has the original dataset, csv that has the cleaned dataset, and a powerpoint presentation that includes the insights.
Dataset source: https://www.kaggle.com/datasets/uciml/adult-census-income
Dashboard Link https://app.powerbi.com/groups/me/dashboards/ccb4ad7e-2177-4547-bd8a-808d6aeded8f?ctid=77255288-5298-4ea5-81aa-a13e604c30ac&pbi_source=linkShare
Requirments: pandas, numpy, plotly, matplotlib, seaborn, power BI
