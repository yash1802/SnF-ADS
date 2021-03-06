# SnF-ADS

Final project for Prof. Julia Stoyanovich's Responsible Data Science (DSGA 1017) class at NYU Center for Data Science. 

Problem statement: Analyze an existing Automated Decision System (ADS) with particular emphasis on its fairness. 

Utilizes various metrics and tools (AIF360, SHAP) to analyze data and classifiers for issues related to ethics, algorithmic fairness, transparency, privacy, and data protection. 

Dataset (NYPD Stop and Frisk, only the data for the year 2011 is used): https://www1.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page
Original ADS: NYPD Stop and Frisk - https://github.com/VeeLeeKoh/Stop-and-Frisk-Data-Analysis

Installations: 
!pip install aif360==0.3.0

!pip install BlackBoxAuditing

!pip install tensorflow==1.12.0

!pip install shap

!pip install -U -q PyDrive==1.3.1

from sklearn.model_selection import GridSearchCV 
