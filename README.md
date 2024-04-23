# MIST-4610-Project2
## Team Name:
Sp24_61608_Group 5
## Team Members:
1. Sydney Seid [@sydneyseid](https://www.github.com/sydneyseid)
2. Manafie Kabir [@manafiekabir](https://www.github.com/manafiekabir)
3. Avanish Thota [@avanishthota](https://www.github.com/avanish-thota27)
4. Albert Sun [@albertsun](https://www.github.com/Glockgeta)
5. Haley Ford [@haleyford](https://www.github.com/HaleyFord)
6. Nicholas Price [@nicholasprice](https://www.github.com/nickprice347)


## Dataset Description
Source: 
The dataset originates from the Shark Incident Database for California, which is maintained and published by the California Department of Fish and Wildlife.

Overview: 
The dataset comprises 12 distinct subsets: Attacks 1950_2021, WhiteSharks, Fatalities, Counties, Species, Activity, Month, TimeofDay, MoonPhase, GIS_All_Incidents, GIS_Injuries, and GIS_Fatalities. Each subset serves the purpose of organizing data in a user-friendly manner while sharing common columns across them.

Common Columns: The subsets contain a set of 16 common columns/records, providing consistent data attributes throughout. 
The columns are as follows:

1. IncidentNum (Integer): Unique numerical identifier for each incident. (Primary Key)
2. Date (Date): The date when the incident occurred.
3. Time (Time): The time of day when the incident took place.
4. County (String): Name of the county where the incident occurred.
5. Location (String): Description of the specific location within the county.
6. Mode (String): Method or activity engaged in during the incident.
7. Injury (String): Description of the injury sustained during the incident.
8. InjuryType (String): Type or severity classification of the injury.
9. Depth (String): Depth of the water at the incident location.
10. Species (String): Identification of the shark species involved, if applicable.
11. Comments (Text): Additional remarks or details regarding the incident.
12. Moon Phase(String): What phase the moon was in when an incident occurred.
13. Percent-Full(Decimal): Percentage describing how close the moon was to being full.
14. Longitude(Integer): Longitude where an incident occurred.
15. Latitude(Integer): Latitude where an incident occurred.
16. Confirmed Source(Text): News source that provided confirmation of a given incident.

## Question 1
In what month are shark attacks most prevalent in the past 10 years, and what types of injuries are most common in those months?

<img width="627" alt="Screenshot 2024-04-21 at 4 43 56 PM" src="https://github.com/manafiekabir/MIST-4610-Project-2/assets/163012589/5f0332f6-adc9-4fee-b2b7-994d7228cf99">

Importance: 

  Our client, the California Department of Fish and Wildlife, would find it useful to know peak months and injury type (non-fatal, no injury, fatal) to better understand how to keep California beachgoers safe. The dataset is filtered by the most recent decade, as this would be the most indicative timeframe for understanding monthly shark encounters. ( opposed to when the dataset began in the 1950s).
  For instance, the summer months have a higher concentration of shark encounters, which is likely caused by warmer weather and more people in the water. Therefore, our client might find it useful to increase lifeguards during these months. This data is also visually intuitive. Our client can readily intuit that fatalities make up a small percentage of all encounters, and are not correlated to months where encounters are more frequent. 

## Question 2
a. What counties have had the most instances of shark encounters?

b. What activities are most common and how are they related to the shark species that is involved?

<img width="704" alt="Screenshot 2024-04-21 at 4 56 58 PM" src="https://github.com/sydneyseid/MIST-4610-Project2/assets/163012786/35bd6866-9a7e-45ed-89f6-64a917407b8f">


<img width="704" alt="Screenshot 2024-04-21 at 4 57 13 PM" src="https://github.com/sydneyseid/MIST-4610-Project2/assets/163012786/dd5f4c19-fe56-4310-abe0-7b74b9019d6b">



Importance:

   This question is interesting because it allows us to understand what countries and activities have had the most incidents with sharks. Being able to see each of these factors, along with the type of shark that was involved, we can take it in more wholly and see some trends in our data. We can also start to see some relationships between them. For example, we can see that Surfing is the most prevalent activity and Great Whites are the species most often encountered during it. Taking a step back, we can see that Great Whites tend to be the most prevalent species for not only that but for every activity. 
   Our client, the California Department of Fish and Wildlife would find this question and our visualizations useful for determining what activities, based on # of incidents, put people most at risk for encounters with sharks. By analyzing the patterns of incidents, the department may be able to identify and put up measures to minimize shark-related catastrophes, for different counties and activities. Furthermore, with more meticulous data of other factors not currently in our possession, such as temperature, the department may be able to observe more causal relationships rather than mere correlation between shark and human encounters.

## Manipulations Applied to the Dataset as Part of Analysis
There were no manipulations or calculations that needed to be performed on the data. The data was already well-organized and had many variations to choose from. There was no need to create calculated fields because the data was mostly descriptive, and mathematics could not be done to create a beneficial analysis. All of the data is accurate, not redundant, and high-quality, making for a smooth analysis process. 

## Analysis and Results
Question 1:
The summer months have the highest concentration of shark encounters, as evidenced by the bar graph, which can be explained by more people going to the beach in warmer months. This graph is insightful in terms of injury type, as fatality is not correlated with months with the highest concentration of attacks. This is useful for clearing up misconceptions of shark attacks, by providing evidence that more encounters does NOT coincide with a higher number of fatal attacks. Thus, fatal shark attacks are harder to predict/tie to a specific month. 

Question 2:
In analyzing the number of incidents per county within California, we created a heatmap that demonstrates which counties have a higher number of incidents. Based on the data visualization we created, a greater number of incidents occurred in San Diego County whereas the least number of incidents occurred in the San Francisco area. The heatmap also indicates the counties that have more beach attractions and activities and allows for the California Department of Fish and Wildlife to handle precautions for sharks in certain counties.

In the second graph, we delve deeper into the number of incidents by correlating the activities and type of shark in the encounter from 1950 and onwards. The graph shows that surfing/boarding is an activity that has greatly led to shark incidents. Even more, the Great White shark is the dominant species in shark encounters across all modes of activities. 

## Tableau Packaged Workbook
Packaged workbook with visualizations are attached above.
