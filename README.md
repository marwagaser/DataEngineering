# DataEngineering
In this repository, we will try to clean the data for the Nobel Prize Winners found on Kaggle:  https://www.datacamp.com/projects/441. Next, analysis is done along with visualization. Finally, a GitHub page which gathers all the work can be found in this repo

# Introduction

### _Overview and Motivation_

In this notebook 3 main stages of data preprocessing are applied. However, before discussing the stages, a clarification of the used data set will be made.  

To begin with, the Nobel prize dataset is obtained from Kaggle: [Nobel Prize Data Set](https://www.datacamp.com/projects/441). The data set is mainly concerened with the Nobel Prize Laureates (from 1901 until 2016)and some information about them, and the organizations they belong to.  

1\. The first data preprocessing step to be done in this notebook is _Data Cleaning_ where the null values are imputed, or dropped. Furthermore, unwanted characters are removed from the dataset using _regex_.  
2\. The second stage is _Data Integration_. This is were external data sets are fetched and are merged with the exitsing one to fill in missing values, in our case in this notebook.  
3\. Finally, _Data Reduction_ is to be done to remove unnecessary columns which aren't needed in our analysis.

### _Data Exploration Questions_

The columns to be reduced or dropped are based on our target analysis of this data set.  
Primarily, we wanted our analysis to be focused on female winners, however, through our initial phase of exploratory analysis, we discovered that a big percentage of the records are males, so we decided to modify our analysis to be slightly more general. Hence, our target for analyzing this data set is to answer some important questions under several themes. Those questions are: <span style="color:red">a. What is the most repeated word in the motivation of the category that interests women the most?</span>  
<span style="color:red">b. How has the number of female winners changed over the years, in the organization country where most female winners come from?</span>  
<span style="color:red">c. Which fields are most prevalent in each organization country?</span>  
<span style="color:red">d. Most productive organization countries over the decades?</span>  
<span style="color:red">e. Most productive organization, in the most productive country, throughout the decades?</span>  
<span style="color:red">f. Which fields interests which age groups?</span>  

### _Related Work_

1\. The following [datacamp project questions](https://www.datacamp.com/projects/309 ) inspired us to explore certain attributes of the dataset.  
2\. The following [GitHub repository](https://github.com/Oysiyl/DataCamp_Solutions_Python/tree/master/A%20Visual%20History%20of%20Nobel%20Prize%20Winners) helped us in data visualization related to the Nobel Prize dataset.  
3\. In addition, the following [dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/6NJ5RN) was used in an attempt to find missing values  
4\. The following dataset was retrieved from the following [GitHub repository](https://github.com/Oysiyl/DataCamp_Solutions_Python/tree/master/A%20Visual%20History%20of%20Nobel%20Prize%20Winners/datasets?fbclid=IwAR1mcQVYCAtV9kuvMTuYFZn57RIp349HtELfGQTuUYRzw00zGPY-WE8J-4A)  
5\. The lecture slides of Dr. Mervat AbuElKheir helped us in understanding the stages of data preprocessing