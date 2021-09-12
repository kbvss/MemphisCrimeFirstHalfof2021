![CityofMmephisLogo](https://github.com/kbvss/MemphisCrimeFirstHalfof2021/blob/main/Images/CityofMemphislogo.png?raw=true)

# Memphis Crime during the First Half of 2021
A deep drive into Memphis's crime for the first 6 months of 2021.

# Data source
https://data.memphistn.gov/Public-Safety/Memphis-Police-Department-Public-Safety-Incidents/ybsi-jur4

# About this data set

This data set includes crime data for the City of Memphis from January - June, 2021. 
Before analyzing this data, I first used 4 excel formulas to extract the time, hour, day of the week and month from the combined offense date/time column.

    Separating the time from the date: =TEXT(B2,"hh:mm")

    Extracting the hour: =HOUR(C2)

    Extracting the day of the week from the date: =TEXT(B2,"dddd")

    Extracting the month from the date: =TEXT(B2,"mmmm")

# Tables

There were **38,299** crimes during the first 6 months of 2021.

Below are the Top 3 highest categories 

![Top3](https://github.com/kbvss/MemphisCrimeFirstHalfof2021/blob/main/Images/TOP3.png?raw=true)

All tables are shown below

![CrimeTables](https://github.com/kbvss/MemphisCrimeFirstHalfof2021/blob/main/Images/CrimeBreakdownTables.png?raw=true)


# Graphs

Pie Chart showing a breakdown of each offense catergory

![PieChart](https://github.com/kbvss/MemphisCrimeFirstHalfof2021/blob/main/Images/OffeneseCatPieChart.png?raw=true)


Line graphs showing crimes by day of the week and month

![DayLineGraph](https://github.com/kbvss/MemphisCrimeFirstHalfof2021/blob/main/Images/OffensebyDay.png?raw=true)

![MonthLineGraph](https://github.com/kbvss/MemphisCrimeFirstHalfof2021/blob/main/Images/OffensebyMonth.png?raw=true)



