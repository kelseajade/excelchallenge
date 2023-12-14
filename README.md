This excel sheet had data from a crowdsourcing site and 1000 campaigns were selected. The following changes were done in the workbook.
Conditional Formatting
Conditional formatting is applied to the outcome column. If the campaign was canceled it is yellow, if the campagin failed it is red, if the campaigh was live it was blue, and if it successful it is green. This was done by using 

Conditional formatting is applied to the percent funded column with a three-color scale. The scale is a dark red for 0 going to green at 100 and blue at 200. 

Column Creation 
Six new columns were created

percent funded was calculated by using =Round((E2/D2)*100,0)

average donation was calculated by using =(AVERAGE(E2/H2)

category AND sub-category was created using the formula =TEXTSPLIT(R2,/)

Date Created Conversion and Date Ended Conversion was converted by =(((L2/60)/60)/24)+DATE(1970,1,1) which I found in the EXCEL help section.


Pivot Tables and Stacked Column Charts 
I created a pivot table that counts how many campaigns were "successful," "failed," "canceled," or are currently "live" per category.

I created a stacked column pivot chart that can be filtered by country as well.

![image](https://github.com/kelseajade/excelchallenge/assets/152021966/261757ae-91a2-4729-9cd7-82c72e9438a8)
![image](https://github.com/kelseajade/excelchallenge/assets/152021966/66a2d8f2-4536-4ff4-89a3-f1f123d1abdc)


Pivot Tables and Line Graphs 
I created a pivot table with a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.

I created apivot chart line graph using the data above.

I created a line chart showing the relationship between the goal’s amount and its chances at success, failure, or cancellation.

![image](https://github.com/kelseajade/excelchallenge/assets/152021966/6bf0d109-4fa1-4b97-a921-e380b947ab63)

Statistical Analysis 
Successful campaigns 
mean 851
median 201
minimum 16
maximum 7295
Variance 1606217
Standard deviation 1267.366

Failed Campaigns
mean 585
median 114
minimum 0
maximum 6080
variance 924113
Standard Deviation 961

![image](https://github.com/kelseajade/excelchallenge/assets/152021966/2e29816e-f6b9-4db8-b8c7-8e18b0df26ce)

