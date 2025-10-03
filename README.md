# DATA SCIENCE PHASE 1 PROJECT
## AIRCRAFT ACCIDENT ANALYSIS
## AVIATION SAFETY INSIGHTS from U.S Aviation Accident Data

*INTRODUCTION*

This project provides analysis on the Aviation Accident data as provided by the U.S National Transportation Safety Board(NTSB). The project aims to give recommendation to a client seeking to expand into the aviation Industry with no knowledge of risks involved in aviation.

The project relies of data from [kaggle](https://www.kaggle.com/datasets/drealbash/aviation-accident-from-1919-2023?select=aviation-accident-data-2023-05-16.csv) 

BUSINESS UNDERSTANDING

Stakeholders:
* Operations & safety team
* Executive Leadership/Investors

The project seeks to answer:
 1. Which aircrafts has the highest and lowest accidents,injuries and fatalities?

 2. Does number of engines in an aircraft impact accidents?

 3. Which aircrafts are best used for private and commercial flights?

 4. How have accident trends changed overtime?


 ## KEY STEPS IN DATA SCIENCE
 1. Data Collection from Kaggle.
 2. Data Cleaning: filter relevant columns & handling missing values.
 3. Exploratory Data Analysis: detective work that uncovers trends.
 4. Visualizations: create plots to explore key insights.
 5. Create interactive dashboard on Tableau.

 ## About the data
 * Timeframe: the data spreads across from the year 1948 to the year 2022

 * Files Included:
   `[DATA](./Data/AviationData.csv)` -raw Aviation  data
   `[Cleaned_Data](./Data/Cleaned_Accident_Data.csv)` -Cleaned Aviation data

 * Key columns used:

   *`Total fatal injuries`-to show extreme risks of the accidents
   
   *`Total Injuries`-to show impact of the  accidents
   
   *`Weather condition`-to show impact of environment on accident
   
   *`Event date`-useful for overal trends
   
   *`Aircrafttype`,`Make` &`model`-to identify the aircraft types
   
   *`Number of Engines`-to identify its impact on accidents


 * Visualizations:
 1. Aircraft type with most injuries-
<img width="1000" height="600" alt="Aircraft Injuries" src="https://github.com/user-attachments/assets/d6350774-fd6e-47a5-acc9-053ea6e6f987" />


 2. Accident trends overtime by `make`- <img width="1000" height="600" alt="Aircraft Accident_trends" src="https://github.com/user-attachments/assets/013fc62c-2237-4b77-a6a0-73665a2ef95a" />


 3. fatalities across aircraft- 
<img width="1000" height="600" alt="Aircraft fatalities_trends" src="https://github.com/user-attachments/assets/a6baeb92-bede-490f-aaed-1200dc4e43c7" />

 4. Number of Engines vs Accidents-<img width="1000" height="600" alt="engines Accidents_trends" src="https://github.com/user-attachments/assets/51a224aa-205b-4021-9d0e-7244ade0a21d" />


 5. Purpose of flight vs Aircraft- 
<img width="1000" height="600" alt="Aircraft Purpose_trends" src="https://github.com/user-attachments/assets/4e092639-633e-4516-8a7a-86dcd5df2b2a" />


 # Aviation Accident dashboard
 
 Then I proceeded to make an interactive dashboard in tableau, 
 to view: [AVIATION ACCIDENT DASHBOARD](https://public.tableau.com/app/profile/sharon.kipruto/viz/AVIATIONACCIDENTDASHBOARD/AVIATIONACCIDENTDASHBOARD)
 
  [IMAGE](./Images/AVIATION%20ACCIDENT%20DASHBOARD.png)
<img width="999" height="799" alt="AVIATION ACCIDENT DASHBOARD" src="https://github.com/user-attachments/assets/fa805268-0ac6-4598-a7d0-1e0475fd44aa" />




## Recomendations & Conclusion

In the visualizations above we were able to visualize the different aircrafts and their occurences on accident data.

1. Which aircrafts has the highest and lowest accidents,injuries and fatalities?
 * Cessna type aircrafts have dominated in Accidents and non-fatal injuries  especially Cessna 152 & 172
 * Boieng 737 and 737-200 have dominated in highest total fatalities
 * Boieng aircraft family showed high counts of uninjured


2. Does number of engines in an aircraft impact accidents?

 *single engine aircrafts account for the most accidents,while aircrafts with more than 2 engines have proved to be safer and have close to no accidents

3. Which aircrafts are best used for private and commercial flights?

 * Cessna 172&152 are top on personal and instructional flights accidents 
 * Beech A36 dominated in accidents for the Business flights
 * Cessna 421C dominated in accidents for the Executive/corporate flights

4. How have accident trends changed overtime?
 * Although, focusing on trends overtime the accidents incidents reported/observed have reduced greatly suggesting safety measures were re-enforced and  are working.

### Recommendations for Client

1. Prioritize aircrafts with multiple engines as they have proven to have lower risks for both private ad commercial operations
2. For **Commercial flights** , prioritize larger Boieng Models with strong safety and survival outcomes.
3. For **Private Flights**, steer clear from high incident Makes like Cessna & Beech.
4. for **Instructional Flights** ,intensify pilot training and scenario based safety drills before proceeding.

