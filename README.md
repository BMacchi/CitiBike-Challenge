**Background for this challenge:**

Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.
_____________________________________________________

**Instructions:**

Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

The following are questions you may wish to answer. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!

- How many trips have been recorded in total during the chosen period?
- By what percentage has total ridership grown?
- How have the proportions of short-term customers and annual subscribers changed?
- What are the peak hours when bikes are used during the summer months?
- What are the peak hours when bikes are used during the winter months?
- Today, what are the top 10 stations in the city for starting a journey? Based on data, why do you hypothesize these are the top locations?
- Today, what are the top 10 stations in the city for ending a journey? Based on data, why?
- Today, what are the bottom 10 stations in the city for starting a journey? Based on data, why?
- Today, what are the bottom 10 stations in the city for ending a journey? Based on data, why?
- How does the average trip duration change by the type of user? (This may be under "User Type" or "member_casual" depending on the period the data is from).
- What is the average distance in miles for a bike trip?
- Which bikes (by ID) are most likely due for repair or inspection in the timespan?
- How variable is the utilization by bike ID?
_____________________________________________________

**Next Steps:**

Use your visualizations to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

Create one of the following visualizations for city officials:

- Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

- Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.
_____________________________________________________
**Create your final presentation:**

Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

Ensure your presentation is professional, logical, and visually appealing.

_____________________________________________________
**Finished Dashboard and Story Screenshots:**

This story is a visual representation of Citi Bike rider and station activity for the month of January 2022. Some of  data seen below includes: rider activity for casual vs members, most popular days/times to use a bike, and trip duration and distance. Continue on to get a closer look at each as well as visualizations showing which bike stations are the most popular. 

<img width="1407" alt="Screenshot 2023-10-13 at 7 45 45 PM" src="https://github.com/BMacchi/Tableau---CitiBike_Project/assets/128737150/193b0fb5-a7c8-41e6-aba5-86cb9a003d2f">
_____________________________________________________

This barchart shows most popular ride times with spikes seen around 8-9am as well as 3-6pm. Perhaps riders are using the bikes to get to and from their place of work as well as to and from dinner?

<img width="1356" alt="Screenshot 2023-10-13 at 7 52 21 PM" src="https://github.com/BMacchi/Tableau---CitiBike_Project/assets/128737150/a659995d-0b99-4021-8f8c-721ba7c3ae9c">
_____________________________________________________

Classic bikes were used more than electric during the month. 

<img width="1324" alt="Screenshot 2023-10-13 at 7 52 55 PM" src="https://github.com/BMacchi/Tableau---CitiBike_Project/assets/128737150/5dec3523-24f1-4435-a057-c87d9763f056">
_____________________________________________________

You can see below that members far outweigh casual riders in total trips taken. However, casual riders on average rode longer than members. Perhaps this is an inducation that casual riders used their bikes recreationally where as members used them to commute from point A to B?  Average distance traveled for both rider types was similar.  

<img width="1405" alt="Screenshot 2023-10-13 at 7 53 28 PM" src="https://github.com/BMacchi/Tableau---CitiBike_Project/assets/128737150/d88397be-2d07-43bd-99f1-e82caa44b451">
_____________________________________________________

This shows the top 20 most widely used stations to start a ride. Every ride started at a station which tells me bikes were redistributed frequently/daily.

<img width="1393" alt="Screenshot 2023-10-13 at 7 54 04 PM" src="https://github.com/BMacchi/Tableau---CitiBike_Project/assets/128737150/89ad0ac1-6fec-47a1-af2e-7a7f4cd2273f">
_____________________________________________________

This shows the top 20 most widely used stations to end a ride. 

***There were roughly 9,000 rides that did not end at a defined station, but at random latitude/longitude coordinates around the city. For map cleanliness, they were filtered out***

<img width="1386" alt="Screenshot 2023-10-13 at 7 54 36 PM" src="https://github.com/BMacchi/Tableau---CitiBike_Project/assets/128737150/e3b0ad28-9651-4905-97d6-90e01fe025fa">
_____________________________________________________
