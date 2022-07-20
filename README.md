# Project Name; Airline-Delay
This is an Analytic project that is aimed at looking into Flight Delay in the past ,providing actionable insights to the cause and recommending effective solutions.

#Introduction :
Flight Delay is one of the ugly occurences that one could face, especially during emergencies.The cause of this could range from technical or mechanical faults to Natural causes, such as climate change,Typhoons, earthquakes and volcano eruptions to name a few.
# Project statement:
History of flight experiences in the past.

How bad the delay has been.

Identified pattern with delayed flights.

And possible recommendations.

 # Data Sourcing: 
 ZionDoz, [20/07/2022 14:45]
The dataset used was gotten from
https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay
With the original dataset, the aim was to predict the possibility of a flight being delayed.
However, the task is to analyze this data and tell a story about the entire flight experience.
The Airlines dataset has 539,383 rows and 9 different featured column,as seen below.
![image](https://user-images.githubusercontent.com/106164032/179999111-6edf17e5-4807-45a6-b8f0-94be749a4150.png)
The row headers are :
Id

Airline

Flight

Airport 

DayOfWeek

Lenght

Time

Delay

# Data Cleaning and Transformation:
I made use of PowerQuery editor to clean and transform the Data.

The Data  was as good as clean before transformation so I only had to do few cleaning steps such as:
Promoting the first column as headers

Ensuring the right data types by formating date as date,texts as texts,I also Formatted the Dayofweek column to data so a to extract the Week Days using DAX.
![image](https://user-images.githubusercontent.com/106164032/180005960-e10c0682-6374-4d76-8fa6-4c398da8f52c.png)


![image](https://user-images.githubusercontent.com/106164032/180005159-6f272be7-f1c0-4f79-bb9e-b69c65dc3db0.png)

Created new measures (Total flights, Delay index, , count of delayed and non-delayed flights) The Delayed and flights on time, etc.

![image](https://user-images.githubusercontent.com/106164032/180004918-045f729d-8637-48e8-b6a5-466f59c42dd7.png)

writing syntax for the delayed column to 1: Delayed, 0: Not Delayed
![image](https://user-images.githubusercontent.com/106164032/180005655-d66adaef-8f7f-4286-8c6c-a6b18eeeb41d.png)
![image](https://user-images.githubusercontent.com/106164032/180005756-9c58a033-2cb3-4ab9-be78-d0038f875689.png)


# Data Visualization;
This is a 3 section 4 pages report ,in which the report could be navigated from all pages especially the first page to any other.
![image](https://user-images.githubusercontent.com/106164032/180007705-8ee7d540-bddf-4ee8-9680-6a065671ce2c.png)
The Visualization 
![image](https://user-images.githubusercontent.com/106164032/180007951-236d4a7e-8a8d-485c-b83b-0a6e9af9d258.png)
Countinuation;
![image](https://user-images.githubusercontent.com/106164032/180010972-8d2fc59e-ca21-4224-adb8-96515a4e9ba5.png)


This is the Abbreviation and the Insight page 
![image](https://user-images.githubusercontent.com/106164032/180011137-d823cc34-e6dd-482a-aca9-44e21aca7056.png)


It was really fun working with this data .

 # Findings: 
 
 -44.5%  Of Flights were Delayed Considering 18 Airlines.

-WN had the highest number of flights Delay.

-Wednesday recorded the highest number of Flight and Flights Delay while Friday recorded the least .

-Flights are more during during the week especially on Tuesday and Wednesday.

-WN didn't just lead in the numbers of flight but also in Delays.

# Recommendation:

-Airlines should device a proper flights scheduling system to avoid delay.

-Traveling on Friday reduces the chances of getting into a flight Delay.

-HA airline has the least Delay so considering HA wont be a bad decision to avoid delay.

# THANK YOU FOR READING THROUGH
