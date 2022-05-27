# Bad driver file

Problem statement:
Traffic in the U.S. has always been a problem that is influenced by many factors. Many influential factors such as higher insurance cost, injury/death are the result of this problem but also traffic is influenced by certain factors such as overpopulation and weather. I wish to seek how these factors influence and are influenced by traffic. To accomplish this, I will need to pull multiple data sets: (Traffic, Weather, insurance cost) to see if I can form a geographical correlation between these factors.
Research Questions:
What regions are more prone to more accidents? What is the relationship between bad weather (ie frequent rain, snow) to accidents and death? What regions have higher insurance rates? Is there a correlation to weather, higher accidents per mile driven, traffic deaths? Which areas have more bad drivers? Is there a correlation of # of accidents to bad weather by region?
Prep the data:
The approach will be to load the data, then munging the data: isolate the needed data (dependent, independent variable). Once variables are loaded into a dataset, then cleansing and standardizing units of measure, and determining appropriate data types.
the Data:
The data is obtained is from 2 key sources:
Data set: https://www.kaggle.com/biphili/road-accidents-in-us/data
1.	Accident Date/Time:
a.	Cleansing- need to separate date/time fields
2.	Accident GPS Coordinates:
a.	Need to convert the City, State for each given GPS coordinates
3.	Severity: (0 to 4)
a.	Determine the weight each accident carries, equate to amount damage
4.	Precipitation
a.	In inches
b.	Clean n/a
c.	Convert binary attribute for rain/no rain
Data set: https://datahub.io/five-thirty-eight/bad-drivers#r
1.	Car insurance Premiums:
a.	Determine by state
2.	Losses incurred by insurance companies for collisions per insured driver:
a.	Determine by state
3.	% of drivers involved in fatal collisions per billion miles:
a.	Determine how this number affects insurance rates
4.	% of drivers involved in fatal collisions who were alcholo-impaired
a.	Determine correlation to insurance premiums

 

