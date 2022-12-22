
# Data Analysis & Visualisation Web App

**This web application will read data from a raw CSV file in a pre-defined format and will generate visualisation chart.**
1) HTML forms is used to get data from the user in CSV (comma-separated values) file that user will enter.
2) Rendering out this data to HTML page and displaying it in a tabular format.
3) Also analysing the data using Pandas and then feeding that analysed data to a Django templte.
4) Finally, displaying the data in terms of charts for data visualisation. 
5) Using library called ChartJS to display data on the webpage.

## Technologies Used
a) Python : Programming Language    
b) Django : For web based app  
c) Pandas: For data analysis  
d) ChartJS: For data visualisation  

## Installation

1) Python x.x < 3.9
2) Django 

```bash
  pip install django==3.2
```
3) Pandas 
```bash
  pip install pandas 
```
4) CharJS  
   a) Install using pip command 
   
      ```bash
        pip install chart.js
      ```  
   b) using chart.js CDN Files directly

## How to RUN the PROJECT
### Follow the following steps
1) Downnload the file and look for mysite folder  
2) run manage.py file using the command 
```bash
  python manage.py runserver 
```
3) Copy and paste the local ulr link and add '/hello' to it.  
4) Demo CSV file has been provides in the folder example (master branch). 

## SCREENSHOTS

1) Homepage  

![image](https://user-images.githubusercontent.com/107344181/209092406-4b71a44c-2ab4-458c-a951-06329f1667b2.png)


2) Selecting the demo CSV file 
 
![image](https://user-images.githubusercontent.com/107344181/209093215-c85e1612-dfc6-4bd6-b879-4d6520ec5120.png)

3) After sumbitting  

![screencapture-127-0-0-1-8000-hello-2022-12-22-14_06_01](https://user-images.githubusercontent.com/107344181/209092735-0b758a3b-01fd-49a6-884d-7fba31512311.png)


