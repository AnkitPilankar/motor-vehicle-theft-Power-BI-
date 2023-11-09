# motor-vehicle-theft-Power-BI-

Hello everyone here i created a motor-vehicle-theft-Power-BI-dashboard to get analysis of stolen vehicle in new-zealand country.

# the dataset is taken from maven analytics https://www.mavenanalytics.io/data-playground?datasetId=25S4VOgB1WMVMAUo90JzSv

here we answer all the question asked for analysis by creating dashboard
# total vehicle stolen 
#unique vehicle stolen
#average age of vehicle stolen in particular year or month
#car is most highest vehicle has been stolen
#auckland region from highest vehicle stolen
#standard type of vehicle is stolen more.


#behind scenes
use kpi , slicer ,column chart,bar graph,line chart,pie chart,tooltip,button 

#date format is wrong in data so we convert date from text to date datatype for that we use power query editor use local and use date format as english united states then it will convert from mm/dd/yy to  dd/mm/yy
then make new table and get year,month,date all date format

#to calulate avg age extract year from date column we ceated in new table then using power query do date(year)-model_year we get age value then use mean to get avg date

# we combine all vehicle type in some common vehicle type using group by in power query like light car,heavy car,electric car in one vehicle type 'car' and rest on we use tooltip to get vehicle type get by pointing vehictype_group by  
