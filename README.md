# MGT 4250 Spring 2024 Course Project

## Section 1: Project Description
This repository is for the course project of MGT 4250 at Elon University.

 <p align="center">
  <img width="465" height="400" src=https://github.com/TCoulter2/MGT4250_AirPorts/assets/168772702/99a3c6d7-8bda-4e73-bc21-c49e5c1d2eaa>
</p>
 [Air Travel Vizualizations](https://public.tableau.com/views/AirTravelVisuals/Story1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link) 

Our question is “When are the busiest and least busiest times to travel on the top three airlines in the top 10 major domestic airports?” This is an important question because it is crucial for customers to understand when it may be more challenging to get a seat on a flight or for different airlines and airports to know when they may need to hire more temporary workers to handle the increased demand for people taking flights. To understand which months to quantify as “busy times" and “least busiest times” we collected information from a [USA Today article](https://www.usatoday.com/story/travel/flights/2017/02/28/busiest-times-of-year-to-fly/98484452/#:~:text=Answer%3A%20There%20are%20several%20times%20a%20year%20when,holiday%20season%2C%20from%20mid-December%20into%20the%20new%20year.), as well as an [AFAR article](https://www.afar.com/magazine/tsa-just-had-its-busiest-week-ever#:~:text=According%20to%20the%20TSA%2C%20the%20busiest%20travel%20days,nearly%202.9%20million%20passengers%20passed%20through%20TSA%20checkpoints.). Understanding this will allow us to further analyze our data and understand different trends within our data. 

Our analysis focuses on the **top three airlines**: 
 1. American Airlines
 2. Delta Air Lines
 3. United Airlines

Our analysis also focuses on the **top 10 major domestic airports**:
 1. Hartsfield-Jackson Atlanta International
 2. Denver International
 3. Dallas/Fort Worth International
 4. Chicago O’Hare International
 5. Los Angeles International
 6. Harry Reid International
 7. Orlando International
 8. Charlotte Douglas International
 9. Phoenix Sky Harbor International
 10. Seattle/Tacoma International

## Section 2: Data Description & Upload
Our data used in our analysis was retrieved from [The Bureau of Transportation Statistics](https://www.bts.gov/topics/airlines-and-airports/quick-links-popular-air-carrier-statistics). It includes passenger and flight data from the top three airlines and is filtered to include the top 10 major domestic airports.
We first went to the "Flights" section to gather the data on the number of flights, and filtered the data set based on the above criteria. We repeated this step, going to the "Passengers" section to gather the data on the number of passengers, and filtered that data set based on the above criteria as well. After downloading the data sets for each airline and for each airport, we then uploaded our data into an Excel spreadsheet, ensuring there are no errors in the data and combined all the data sets we retrieved. 

**Data Description**                                                                                                                                                                                                  
<img width="550" alt="Data Descriptions" src="https://github.com/TCoulter2/MGT4250_AirPorts/assets/168772702/263fa359-4f71-49e9-9a5d-b348c2de17ee">

Refer to "Airline Data.xlsx" to view final data set used in creating visualizations. 


## Section 3: Interpreting Visualizations

The first dashboard, "Top 10 Aiports", includes two visualizations that creates a foundation for answering our underlying question: When are the busiest and least busiest times to travel on the top three airlines in the top 10 major domestic airports? “Top 10 Airports by Sum of Flights”, is a treemap that compares the ten most trafficked domestic airports. The visualization is marked with ten sections, with each section representing one airport, that vary in size corresponding to their ranking in terms of number of flights. For example, Atlanta is the most trafficked airport in the country and thus has the biggest plot on the graph. This visualization allows the reader to better picture the ten most popular airports, in comparison to each airport and provides a good idea of how popular each airport is. “Flights Per Month by Airport” also tracks the top ten most popular domestic airports, but compares them by total flights in thousands to a given month. This graph goes one step further than the treemap. By analyzing each airport by month, we can start to determine when the busiest and least busiest time is to travel. Generally, February and September are the least busy months and you should avoid traveling in November. The graphs indicate that the top three airports in the United States are located in Atlanta, Dallas, and Chicago.

The next dashboard, "Best Time to Fly", includes two visualizations that compare the top three airlines in the United States by month. “Flights Per Month by Airline” measures the amount of flights per month by airline, in thousands, to a given month. “Passengers Per Month by Airline” similarly compares the top three domestic airlines by month but instead of total flights, the graph depicts total passengers by millions. Across the board, airlines in order from most to least popular, include: American Airlines, Delta Airlines, and United Airlines. By targeting specific airline traffic instead of airports, these visualizations contribute to answering our research question and allow for a more direct answer to when the busiest and least busy times are for travel. If someone is looking to travel with the least amount of people, but still wants to travel with a premier airline, the individual should fly in February but specifically with United Airlines. We can most likely infer that February is the best time to travel because it is after the holiday season. Individuals and families are less inclined to fly because the chance of them flying to see family and friends is increased around this time. It would be in someone's best interest to avoid travel in June, as the passengers per month is universally much higher during this time of year. This increase in travel can be attributed to academic and work related summer vacations.

The final dashboard, "Impact of COVID-19 on Air Travel", displays two visualizations. “COVID-19 Impact on Sum of Flights” compares the sum of domestic flights, in thousands, to each month in the years 2019 to 2021. “COVID-19 Impact on Sum of Passengers” measures each month with the same timeframe but instead, tracks the sum of domestic passengers in millions. Both of these graphs include data from the three biggest airlines in the United States: American Airlines, Delta Airlines, and United Airlines. These visualizations are different from our previous dashboards because the data is being presented by year instead of by airline. By combining the three most popular domestic airlines into one line per year (2019,2020,2021), we can better understand how travel has been affected and still is being impacted by COVID. Therefore, when determining when the best and worst times are to travel, in other words our research question, we can compare the previous trends in our graphs to the COVID-19 years. In the “Best Time to Fly” dashboard, we concluded that the holiday season is the worst time to travel and thus should be avoided the most. This trend in our data was consistent in both graphs in the “Impact of COVID-19 on Air Travel" dashboard which furthers the validity of our graphs. If individuals are more inclined to travel during the holiday season in the midst of a pandemic, the same people would be even more inclined to fly without restrictions.

## Section 4: Discussion & Summary
 o Discuss whether your visualizations align well with the article and generative AI’s response. 

### Summarized Article
The article from [Upgraded Points](https://upgradedpoints.com/travel/best-and-worst-days-to-fly/) provides a look into the best and worst days to fly to help travelers better their flight schedules. Here's a summary:
- Best Days to Fly:
 - Tuesday, Wednesday: These are typically the cheapest days to fly due to lower demand. Airlines often offer discounted fares to fill seats on these less popular travel days.
 - Saturday: Similar to Tuesdays and Wednesdays, Saturdays often have lower demand, making them another cost-effective option for flying.

 - Worst Days to Fly:
  - Friday: Friday is popular for business travelers to return from the workweek
  - Sunday: While Sunday sees high volumes of leisure travelers returning home from weekend getaways.
  - Monday: Mondays tend to be busy as business travelers head out for the workweek. Additionally, flights on Monday mornings are often more expensive than later in the day.
  - Thursday: Thursday mornings can be busy with business travelers.
  - Saturday Mornings: Wile Saturday mornings can see higher fares due to leisure travelers starting their weekend trips.
  - Around major events: Major events will increase air traffic for a certain airports. Planning around them can make for better departure dates.
 
 - Additional Tips:
  - Flexibility: Being flexible with travel dates can help find better deals. Adjusting departure or return dates by a day or two can sometimes result in significant savings.
  - Book in Advance: Booking flights well in advance can often secure lower fares, especially for popular travel dates and routes.
  - Use Fare Comparison Tools: Utilize fare comparison tools and apps to compare prices across different airlines and dates to find the best deals.
  - Avoid Peak Travel Seasons: If possible, avoid traveling during peak seasons such as holidays and school breaks when demand is highest and fares are typically more expensive.

The article offers good insights for travelers looking to save money and reduce the stress of air travel by strategically planning their flight. This is very similar to what we are asking and 

### ChatGPT
We asked Chat GPT our question and it came back with this response.
 - Determining the busiest and least busy times to travel on specific airlines at the top 10 major domestic airports can vary depending on numerous factors such as time of year, day of the week, holidays, and current events. However, I can provide some general insights based on typical travel patterns and historical data.

 - Delta Airlines:
   -  Busiest Times: Delta tends to see high volumes of travelers during peak business travel hours (early morning and late afternoon/early evening) on weekdays, especially Mondays and Fridays. Additionally, holiday seasons and school breaks can significantly increase passenger numbers.
   -  Least Busy Times: Midday on weekdays and weekends, particularly outside of holiday seasons, tend to have fewer travelers.
 - United Airlines:
   -  Busiest Times: Similar to Delta, United experiences high traffic during peak business travel hours on weekdays. Mondays and Fridays are typically busiest. Holiday seasons also bring increased passenger numbers.
   -  Least Busy Times: Midday on weekdays and weekends outside of peak travel times usually have fewer passengers.
- American Airlines:
  -  Busiest Times: American Airlines sees heavy traffic during peak business hours on weekdays, with Mondays and Fridays being particularly busy. Holiday seasons can also result in higher passenger volumes.
  - Least Busy Times: Midday on weekdays and weekends, especially outside of peak travel times and holiday seasons, tend to have fewer travelers.
 - For the top 10 major domestic airports you listed, similar patterns generally apply. However, specific busy and quiet times can vary depending on factors like regional events and local travel patterns. It's always a good idea to check with the airlines directly or utilize travel apps that provide real-time updates on flight schedules and passenger loads for more accurate information.

### Alignment
