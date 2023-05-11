---
layout: post
title: "The Surprising Effect of Covid Lockdown on Vehicle Crashes in New York"
subtitle: "Exploring the Data and Uncovering the Unexpected Benefits of a Pandemic-Induced Slowdown"
date: 2023-05-11 12:00:00 -0400
background: '/img/posts/42&5nyc.png'
---

# The Surprising Effect of Covid Lockdown on Vehicle Crashes in New York
## Exploring the Data and Uncovering the Unexpected Benefits of a Pandemic-Induced Slowdown


The Covid-19 pandemic has had a profound impact on society, including changes in daily routines and a significant reduction in travel. One area of interest is the effect of lockdown measures on traffic accidents. The potential benefits of reduced traffic congestion and decreased number of drivers on the road could lead to fewer accidents. This story explores the data and investigates if New York experienced a positive impact on vehicle crashes during the pandemic lockdown and after the lifting of the restrictions , shedding light on an unexpected silver lining to a difficult situation. This analysis could potentially inform future policy decisions and urban planning strategies aimed at improving traffic safety in big cities.

The first significant date was March 1, 2020, when the city reported its first confirmed case of COVID-19. On March 22, 2020, the city entered a lockdown, with non-essential businesses and schools closed, and residents instructed to stay at home. April 6, 2020, marked the peak of the pandemic in New York City, with over 10,000 new cases and over 700 deaths reported that day. Finally, on June 8, 2020, the city began reopening with the start of phase one, allowing construction, manufacturing, and retail businesses to reopen with restrictions.

After the initial lockdown phase in New York City, there were several subsequent dates marking the gradual relaxation of restrictions. On June 22, 2020, the city entered phase two, allowing outdoor dining, hair salons, and real estate services to resume, among other businesses. On July 6, 2020, the city began phase three, permitting indoor dining and opening up personal care services like nail salons and spas. September 30, 2020, marked the start of phase four, which included the reopening of cultural institutions like museums and zoos, and the resumption of low-risk indoor activities like movie theaters at limited capacity. Finally, on May 19, 2021, the city announced that most capacity restrictions would be lifted starting May 19, 2021, with businesses and venues allowed to operate at 100% capacity as long as all individuals were fully vaccinated.

<div style="text-align:center;">
    <iframe title="Timeline: New York City Coronavirus" aria-label="chart" id="datawrapper-chart-moIfo" src="https://datawrapper.dwcdn.net/moIfo/13/" width="750" height="400" frameborder="0"></iframe>
    <p style="text-align:center; font-style:italic; color:grey; font-size:12px;">Timeline: New York City Coronavirus (Source:datawrapper.dwcdn.net) </p>
</div>

The COVID-19 lockdown had a significant impact on transit in New York City. With the closure of non-essential businesses and the implementation of work-from-home policies, ridership on the city's subway system, buses, and commuter rails declined dramatically. According to the Metropolitan Transportation Authority (MTA), subway ridership fell by over 90% during the height of the pandemic in April 2020, while bus ridership declined by around 60%. The MTA also implemented a series of measures to protect the health and safety of riders and employees, including increased cleaning and disinfecting of vehicles and stations, the distribution of masks and hand sanitizer, and the installation of plexiglass barriers to protect bus drivers. Despite these measures, concerns about the risk of transmission on public transit led to a prolonged decline in ridership, with many commuters opting for alternative modes of transportation like biking or driving. However, as the city began to reopen, transit ridership gradually rebounded, with subway ridership reaching around 70% of pre-pandemic levels by the end of 2021.

<div style="text-align:center;">
  <iframe src="/assets/accidents.html" width="100%" height="530" frameborder="0"></iframe>
  <p style="text-align:center; font-style:italic; color:grey; font-size:12px;">Total Car Accidents in NYC from July 2012 to May 2023 (Source:NYC Open Data)</p>
</div>

According to a recent analysis of a timeseries tracking the total number of car accidents, it appears that the COVID-19 pandemic had a significant impact on driving behavior. As expected, there was a sharp drop in the number of car accidents immediately after the lockdown measures were put in place. However, as the restrictions were gradually lifted, there was a small positive slope in the number of car accidents after each phase of flexibilization. Despite these slight increases, the total number of car accidents never returned to pre-COVID levels.

Further analysis was conducted by comparing a geospatial heatmap of total crashes on a given day before and during the COVID-19 pandemic. The heatmap on the left showed a much higher concentration of crashes in densely populated areas, such as urban centers and major highways. In contrast, the heatmap on the right revealed a more even distribution of crashes across a wider area, likely due to reduced traffic volume and changes in driving patterns. While there were still hotspots of crashes in certain areas, the overall picture was one of a decrease in the frequency and severity of accidents during the pandemic. This finding reinforces the notion that changes in driving behavior during the pandemic have had a measurable impact on road safety.

<div style="text-align:center;">
  <img src="/img/posts/foliumb&a.png" alt="Folium Before and During Covid" width="100%" height="300" >
  <p style="text-align:center; font-style:italic; color:grey; font-size:12px;"> Folium Visualization with Total Collisions per Month in NYC Before and During Covid  (Source:NYC Open Data)</p>
</div>

To further understand the impact of the pandemic on car accidents, a heatmap of the average crashes per day in each borough was generated. This third visualization highlights the changes in crash patterns over time, with maps for the periods before COVID, during COVID, and after COVID. The heatmap for the period before COVID showed a high concentration of crashes in densely populated areas with heavy traffic, such as the city center. The heatmap for the period during COVID showed a significant decrease in the number of crashes, with a more even distribution of incidents across the boroughs. However, as seen in the timeseries, the heatmap for the period after COVID showed a slight increase in the number of crashes compared to the period during COVID. This increase suggests that some drivers may have returned to pre-pandemic driving habits. Despite this increase, the number of crashes remained lower than pre-COVID levels.

<div style="text-align:center;">
  <img src="/img/posts/cloropeth.png" alt="Average Collisions per Day and Boroughs" width="100%" height="300" >
  <p style="text-align:center; font-style:italic; color:grey; font-size:12px;"> Plotly Cloropeth Map with the Average Collisions per Day per NYC’s Boroughs Before, During & After Covid (Source:NYC Open Data)</p>
</div>

One interesting question that arises from these findings is why we did not see a reactivation of crashes after the lockdown ended and everything returned to normal. Despite the gradual lifting of restrictions, the number of car accidents did not reach pre-COVID levels, indicating a sustained shift in driving behavior. What factors may have contributed to this trend? Did drivers become more cautious and safety-conscious as a result of the pandemic, or did they continue to avoid non-essential travel even after restrictions were lifted? Did governments implement new traffic rules or laws to help reduce accidents during the pandemic? Did the pandemic lead to a re-evaluation of road safety policies and practices? 

New York City made several changes to its streets and transportation infrastructure that had an impact on vehicular traffic. One such change was the implementation of the [Open Streets program](https://www.nyc.gov/html/dot/html/pedestrians/openstreets.shtml#locations), which closed some streets to vehicle traffic and opened them up to pedestrians and cyclists to encourage outdoor activity and social distancing. Another program, known as Open Restaurants, allowed restaurants to use street space for outdoor dining, reducing the number of available parking spaces in some areas. These programs were initially intended as temporary measures to support public health and the local economy during the pandemic, but they have been extended and made permanent in some cases. For example, the Open Streets program was extended through December 2021, and the Open Restaurants program was made permanent with the passage of the NYC Alfresco Dining Program in March 2021. These changes may have had some impact on vehicular traffic and parking availability in certain areas of the city.

Furthermore, the New York City government implemented several new rules and policies regarding traffic and car use after 2020. One notable example is the expansion of the city's speed camera program, which began in 2019 but was significantly expanded in 2020. The program now includes over 1,000 cameras in school zones and other high-risk areas, with the aim of reducing speeding and improving safety for pedestrians and cyclists. Additionally, the city implemented several initiatives to encourage alternative modes of transportation and reduce reliance on cars. These include the expansion of bike lanes and the introduction of new protected bike lanes, the launch of the [Citi Bike e-bike program](https://www.trafficlaw411.com/blog/2020/july/e-bikes-e-scooters-now-legal-in-nyc/), and the establishment of car-free zones in certain areas of the city. The city also implemented new regulations for delivery vehicles to reduce congestion and improve safety. These include restrictions on the hours during which commercial trucks are allowed to make deliveries in certain areas, as well as new safety requirements for large trucks, such as the installation of side guards and convex mirrors. The impact of changes in road safety during the pandemic can be observed in the following two plots. The first plot shows a reduction in the number of pedestrians, cyclists, and motorists who were injured during the analyzed timeframe. The second plot shows a decrease in the number of cyclists and motorists who were killed, but no changes in the number of pedestrian fatalities. 

<div style="text-align:center;">
  <iframe src="/assets/views_inj2.html" width="100%" height="350" frameborder="0"></iframe>
  <p style="text-align:center; font-style:italic; color:grey; font-size:12px;">Distribution of Injured by Year and Category (Source: NYC Open Data)</p>
</div>

<div style="text-align:center;">
  <iframe src="/assets/views_kill2.html" width="100%" height="350" frameborder="0"></iframe>
  <p style="text-align:center; font-style:italic; color:grey; font-size:12px;">Distribution of Killed by Year and Category (Source: NYC Open Data)</p>
</div>


Finally, the city has also introduced new policies to address equity and environmental concerns related to transportation. For example, the city's [Congestion Pricing program](https://www.silive.com/news/2023/03/nyc-congestion-pricing-heres-what-we-know-amid-the-controversial-programs-latest-delay), which is set to launch in 2023, will charge drivers a fee to enter certain areas of Manhattan, with the aim of reducing congestion and raising funds for public transportation improvements. The city has also implemented new regulations for ride-hailing services like Uber and Lyft, requiring them to pay a minimum wage to drivers and reducing the number of new licenses issued to these services.

In conclusion, the COVID-19 pandemic has had a significant impact on road safety, with a sharp decrease in the number of car accidents during lockdown periods. As the pandemic recedes and normal life resumes, it is important to reflect on the lessons learned and the opportunities for continued improvement. The sustained shift in driving behavior during the pandemic highlights the potential for safer and more sustainable transportation systems in the future. However, maintaining these gains will require ongoing efforts to promote safe driving practices, invest in public transportation, and implement effective policies and regulations. The questions raised by this analysis, such as how to maintain reduced traffic volume and promote safer driving habits, are important ones to consider as we work towards a safer and more sustainable post-pandemic world.

> About the dataset: For this analysis, I utilized the Motor Vehicle Collision – Crashes Dataset available on NYC Open Data. This dataset comprises data on all motor vehicle collisions reported to the police in New York City. The dataset was created in 2014 and is updated on a daily basis, containing 1.98 million rows or records and 29 columns. The columns include various data types such as datetime, plain text, numerical, and location informationt. The total dataset size is 422,6 MB (Megabytes).

---
Facundo Castellá - 11/05/2023