# Bank-Performance-Dashboard
A Power BI dashboard for visualizing bank performance metrics, including loans data, and key performance trends.

### Dashboard Link : https://app.powerbi.com/links/qieZqSFZz8?ctid=755de9ae-86f9-4909-b1a5-f092c48533f1&pbi_source=linkShare

## Problem Statement

The dashboard shows whether the bank has achieved its targets regarding the types of loans targeted and granted by regions, provinces, and branches. Thanks to the dashboard, the most profitable branch, region and province can be monitored, while the least profitable branch, region, and province can also be monitored. Monthly data for 2019 can be analyzed in detail through KPIs. 

The data belongs to a small-scale bank in Turkey in 2019.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a CSV file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Created a new measurements table to save further measurements on this table.
- Step 5 : Measures were created for each loan type as target and sales, a measure was created as total target and total sales, and a cumulative measure was created to see the cumulative results. 
- Step 6 : In the report view, I have created my own canvas.
- Step 7 : To facilitate the use of the dashboard, three different pages were created and they are; Bank-wide (bank-wide summary information and visuals), Regions (bank's information based on regions), and Branches (bank's information based on branches).
- Step 8 : Added visual filters (Slicers) named 'Months', 'Regions', and 'Branches'.
- Step 9 : A bar chart showing targets and realizations by loan type as bad, medium, good, and very good has been added to the report design area. A trend graph showing the cumulative total loan sales for a year by month and a map of Turkey showing total sales as a bubble over provinces and regions have been added. In addition, gauge indicators were added and visualization was made based on branches and regions. Finally, all necessary information is presented in a matrix table. 
       
# Snaps of Dashboard

![Snap_1](images/Screenshot (1148).png)

![Snap_2](images/Screenshot (1155).png)

![Snap_3](images/Screenshot (1149).png)

![Snap_4](images/Screenshot (1154).png)

![Snap_5](images/Screenshot (1150).png)

![Snap_6](images/Screenshot (1151).png)

![Snap_7](images/Screenshot (1152).png)

![Snap_8](images/Screenshot (1153).png)
