# Data-Cleaning-with-SQLServer
These are projects i analysed and wrangled starting as a data analyst with AlexTheAnalyst tutorial video.

# Project-1 CovidDeath EDA
* Obtained CovidDeath Dataset.
* Prepared Dataset using Microsoft Excel i.e converting csv file to an Excel workbook file.
* Import dataset into SQLServer.
* Dataset did not require cleaning so i did my Exploratory Data Analysis(EDA).
*  Discovered where #INT needs to be converted to #BIGINT.


# Project-2 NashvilleHousing cleaning
* Obtained NashvilleHousing Dataset.
* Prepared Dataset using Microsoft Excel i.e converting csv file to an Excel workbook file.
* Import Dataset into SQLServer.
* Explored the dataset so as to understand and clean it better.
* Converted the datatypes into their appropriate format e.g datetime format to date format.
* Adjusting property address by populating the null values and updating it to the table.
* Splitting owner and property address into state,city and address using PARSENAME, SUBSTRING CHARINDEX functions.
* Changed some column values using the CASE function.
* Removed duplicate values using Common Tble Expression (CTE) and ROW NUMBER.
