# Tableau_Challenge


# Introduction

This is an analysis of the largest bike-sharing program in the United States:  New York Citi Bike.

This program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike Data webpage --> https://citibikenyc.com/system-data

The data for the last 13 months by now, is being used to generate graphs to describe special features about this program in NYC.

In the next image, see the months included in this report. As you can see, 
1,150,000 rows are being collected in this work.

 <p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/Period%20of%20Data.png" /></p>


# Data complemented by Python Script

In order to complement the data, the coordenates of each end-point trip was used to get the complete address for the bike station in witch the trips ended; 
so we are allowed to use the geografic information such as district, state, count to create maps.

The next image shows the data obtained by geoapify API, to get the fields described above.

<p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/Complete%20direction%20of%20each%20bike%20station%20obtained%20using%20the%20API%20geoapify.png
" /></p>

The script with this functionality is in folder "jupyter_scripts". For more details, open the jupyter file named: preparation_station_info_citi_bike_geoapify.ipynb 
Note: you will need an api_key from the website geoapify to run the script.


# Tableau for the analysis


Tableau desktop has being used to create usedful dashBoards to get full understanding of data. 
The file created is Bycle_Analysis_DashBoards_Stories.twb

This file designed in tableau, upload 13 cvs files that must be readed to get the data. Those are found in "trips_data - copia" folder. Each of the cvs file corresponds to one month of data.

Besides all that, the file catalog_end_stations_complete_direction.csv is used to get geographic information of the bike stations. This data was used to create a choropleth map. (for more details of the creation of this data, see below the  python script's paragraph.) 

In the next section is explained all the graphics included in this tableau file.

# Dashboards made in Tableau

See the first dasboard in the next picture.

<p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/DashBoard%201.png" /></p>


See the second dasboard in the next picture.


<p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/DashBoard%202.png" /></p>


# History implemented in Tableau

The next pictures shows the special features found analyzing the data mencioned. To know the conclusion obtained in each graph, please read the message you can find in the title of each one.

To know more details, use the Tableau desktop file named: Bycle_Analysis_DashBoards_Stories.twb


Image 1

<p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/History%201.png" /></p>

Image 2

 <p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/History%202.png" /></p>

Image 3

 <p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/History%203.png" /></p>

Image 4

 <p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/History%204.png" /></p>

Image 5

 <p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/History%205.png" /></p>

Image 6

 <p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/History%206.png" /></p>

Image 7

 <p align="center"><img src="https://github.com/zuntaalejandra/Tableau_Challenge/blob/main/Images/History%207.png" /></p>
