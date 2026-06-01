

**Data Science Project**  
Artificial Intel Concepts  
Sanchit Bhadani, Aarnav Ravi  
12/5/2025  
**Table of Contents**  
Introduction……………………………………………………………………………………3  
Methodology…………………………………………………………………………………..4  
Findings………………………………………………………………………………..………5  
Limitations…………………………………………………………………………………….6  
Conclusions…………………………………………………………………………………....7

**Introduction**  
Our data science project was conducted based on the research question: How have greenhouse emissions from different sources changed in different countries around the world across time. Our project was oriented towards determining greenhouse emission trends across time in different countries. Using this data, we can conclude what industrial sectors show the most emissions and are the most damaging to the environment, as well as what countries emit the most greenhouse gasses. Using a given dataset, we excluded missing information and calculated statistical data that could be used to help answer the previously stated research question.

**Methodology**  
The dataset used in the project was retrieved from Ourworldindata.org. We downloaded the dataset into a CSV (comma separated values) format, where we then used Python and the Python libraries Pandas and Matplotlib to further visualize and conceptualize the data. We filtered and cleaned the dataset by filling in all missing values with values behind it using df.fillna(method="bfill"). After that, the dataset was checked for duplicated rows using df.duplicated().sum(). This returned the number of duplicated rows throughout the dataset. The returned value was 0, meaning that the dataset had not duplicated rows, meaning a filter for removing duplicates was not needed. To analyze the data, the means of each column were calculated, as well as the means of each column for each country throughout the years. This way, we could analyze trends on greenhouse gas emissions between each country separately rather than all the countries combined. This helped identify which countries produced the most gasses, and which countries produced the least. 

**Findings**  
Global greenhouse gas emissions have risen significantly since 1990, with electricity and heat consistently being the largest contributor, followed by transport, industry, and agriculture. Electricity and heat emissions grew sharply due to fossil-based power generation, while transport nearly doubled, driven by increased motorization and freight. Industry emissions rose moderately, reflecting hard-to-abate processes like cement and steel, and agriculture remained relatively stable, dominated by methane and nitrous oxide. Comparative analysis across milestone years (1990, 2000, 2010, 2022\) confirms these trends, highlighting the urgent need for clean energy transitions, transport electrification, industrial process innovation, and targeted agricultural practices to curb non-CO₂ gases.

**Limitations**  
The dataset used had multiple missing entries. Using the methods df.isnull().sum() and df.fillna(method="bfill") the missing entries were filled in by using values that were directly below the missing value in the same column. The dataset did not have duplicated entries, which was checked for using the method df.duplicated().sum(). This checked and returned the number of duplicated entries in each column of the data set. After using this method, it was found that the dataset did not contain any duplicates. The dataset included minimal bias, since the dataset had little missing values. Data quality was high and had no issues other than the occasional missing value in certain columns.

**Conclusion**  
Analyzation of the dataset highlighted key findings and observations. After plotting the data points, it can be seen that during the period 1990 \- 2022, overall CO₂ emissions have increased significantly across different countries throughout the world. Certain countries have seen decreases in greenhouse gas emissions in certain sectors but increases in others. For example, throughout this period, Afghanistan saw a gradual decrease in emissions in their transport sector, but a drastic increase in their waste and agricultural sectors. Missing values in the data set were filled in with similar data from the same column, improving the reliability and credibility of the results. These results were then used to answer the initial research question, showing how greenhouse gas emissions have increased gradually across time in countries throughout the world. This gradual increase was most likely due to advances in industrial machinery and technology, producing more CO₂ (the primary and most emissioned greenhouse gas). 

