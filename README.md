# Thai Covid19 Cases Report with Google Data Studio

This mini-project used data from https://data.go.th/dataset to provide a report that represents a number of Covid19 cases in Thailand with geo map and time series chart in Google Data Studio.

Tools: Pyspark with Google Colab, BigQuery, Google Data Studio

## Data Report:  
Go to: [report](https://datastudio.google.com/reporting/21a59607-9cae-4a3e-8ce6-b3793dd2c7cc)
![](https://github.com/ThanaVi/THCovid19_Report/blob/master/images/THCovid19_Report-1.jpg)

## Data preparation with Google Colab:  
- For geo map,  
 >1. Provinces of Thailand latitude and longtitude data  
 Go to: [source](https://data.go.th/dataset/item_c6d42e1b-3219-47e1-b6b7-dfe914f27910)  
 ![](https://github.com/ThanaVi/THCovid19_Report/blob/master/images/tambon.JPG)  
 Go to ETL: [THProvince_Lat_Long](https://colab.research.google.com/drive/1axYcf9lB90o2gogJ_jQgy7SE-0qyxS8h?usp=sharing)  
 ![Result](https://github.com/ThanaVi/THCovid19_Report/blob/master/images/province_lat_long.JPG)  
 
 >2. Covid19 cases in Thailand  
 Go to: [source](https://data.go.th/dataset/covid-19-daily)  
 ![](https://github.com/ThanaVi/THCovid19_Report/blob/master/images/data.JPG)  
 Go to ETL: [THCovid19_Data](https://colab.research.google.com/drive/145h5YYKzitwuB6uR-LcNFkiIZUGHiK_N?usp=sharing)  
 ![Result](https://github.com/ThanaVi/THCovid19_Report/blob/master/images/edited_covid19.JPG)  
 
- For time series chart,  
 >Total of Covid19 cases in Thailand  
  Source: THCovid19_Data
  ![](https://github.com/ThanaVi/THCovid19_Report/blob/master/images/data2.JPG)  
  Go to ETL: [THCovid19_Sum](https://colab.research.google.com/drive/1ypdBASkCsHhRr95qLCxP8Y_YdEyG-4JM?usp=sharing)    
  ![Result](https://github.com/ThanaVi/THCovid19_Report/blob/master/images/covid19_sum.JPG)








