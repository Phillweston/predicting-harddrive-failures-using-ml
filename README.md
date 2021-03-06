# Predicting Hard Drive Failures Using ML 
Using Backblaze dataset on Kaggle.

## About this project: 
This was a Data Science Case Study. Dataset used for this project is private but a similar dataset and project can also be found on Kaggle.com

Disclaimer: 
This case study is based on a sample subset of a larger dataset and does not accurately solve the problem. Case study is done to demonstrate the use of different tools and libraries in ML, how to present your reports, use python for ML. 

### Sample Dataset: 
A sample of SMART hard drives dataset can be found and downloaded at: https://www.kaggle.com/backblaze/hard-drive-test-data

#### What are SMART systems ?
SMART features or *S.M.A.R.T. (Self-Monitoring, Analysis and Reporting Technology)* is a software monitoring system for hard drives. SMART generates a collection different metrics related to help evaluate the overall health of a Hard Drive. 

A single metrics may not always determine the exact failure prediction but are commonly accepted to help identify any imminent failure and help handle the backup and restore, in time. 


### About this case study :
This case study relies on a given data stream provided for this purpose. The goal of this case study is to try and analyze given data and find out meaningful information that can help determine drives failure trends and different factors that may idicate if a drive would fail, and attempt to propose a more data driven answer to future failures based on SMART metrics.

The study concludes with discussing possible opportunities and challenges with existing model and features that can help design a better predictive model for future. 


--------

## Solution: 

### Full Analysis in Jupyter Notebook
To access the entire analysis code in Jupyeter notebook, go to: 
[Predicting Hard drive failure](https://github.com/geekidharsh/predicting-harddrive-failures-using-ml/blob/master/Predicting%20Hard%20Drive%20Failure%20-%20%20A%20Data%20Science%20Case%20Study.ipynb)



### Overview of the approach

Here's a quick overview of how this problem has been approached: 

#### Extraction and Load
1. Connect to the postgres server.
2. Download the dataset offline

#### Transform
3. Wrangle and explore
4. Change Dimentions, clean and slice and dice

#### Analyze
5. Analyze dataset, plot most significant trends

#### Predict:
6. Feature Selection
7. Model and predict

#### Sample report overview: 
(This is Optional)

<table>
<tr>
<td> 1. Number Hard Drives per model
<img src="graphs/hard-drives-per-model.png" width="600"> </td>
    <td>2. Number of positive failures by model
        <img src="graphs/failures-by-model.png" width="600"> </td></tr></table>
        
        
<table>
    <tr>
        <td>3. Failure Trend over time
            <img src="graphs/failure-trend-timeseries.png" width="600"></td>
<td>4. Daily Failure Trend to determine missing failure data pattern
    <img src="graphs/daily-trend-of-fails.png" width="600"></td></tr></table>

and more...

----
### Conclusion and Improvement Ideas:
8. Conclusion
9. Challenges with the current dataset and ways to improve it

#### Tech stack:
`python, sql, pandas, scikit and other machine learning libaries, postgres`

#### @ author:
[@geekidharsh](https://github.com/geekidharsh) : I am Data Engineer with 4+ years of experience in E-commercal and Digital Acquisition. Analyzing swiftly changing user behaviors to make data driven decisions, at scale. Currently, I work at at [Merck KGaA](https://www.merckgroup.com/en)
