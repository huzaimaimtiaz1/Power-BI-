# Power-BI-
Power BI projects and dashboards showcasing data visualization and analysis
# Power BI Project: Flight Tracking

##  Project Overview
This project is a Flight Radar – Airport Departure Report built in Power BI.

The dashboard provides real-time insights into flight departures from different airports around the world, with details on:

 Flight Route Information – Departure and arrival airports with scheduled departure/arrival times.
	
 Airline & Aircraft Details – Airline selection filter, aircraft type, and airline branding.
	
 Weather Insights – Temperature at both departure and arrival airports for flight planning considerations.
	
 Geographical Mapping – Interactive map showing the departure and arrival airport locations.
	
 Flight Activity Status – A breakdown of active flights, landed flights, and scheduled flights.
	
 Aircraft details page - details about the aircraft being used in that specific flight (aircraft's name, use, type, range, seating capacity, aircraft image, airlines that are using this airplane, aircrafts most recent arrival) 
 
 
## Purpose
The purpose of this dashboard is to simulate a flight-tracking and departure monitoring system, enabling users to quickly check flight schedules, aircraft types, and weather conditions, aircraft details at connected airports.


##  Dashboard Features
Interactive Airline Search → Dropdown slicer to filter flights by airline.

Flight Information Cards → Departure & arrival airports, date & time, and live arrival time.

Aircraft Details Page → Aircraft type, seating capacity, range, engine configuration, and airlines using the aircraft.

Weather API Integration 

Real-time temperature for departure and arrival airports fetched via OpenWeather API
Image/API Integration 

Airline logos, aircraft images, and related visuals dynamically pulled from external APIs and curated image endpoints.

Live Location Maps → Interactive maps (Bing Maps) to display both departure/arrival airports and recent arrivals.

Flight Status Analytics → Donut chart showing Active, Landed, and Scheduled Flights.

Theming System (Light/Night Mode) 

Built using Power BI bookmarks + buttons for seamless dashboard theme switching.

Not only background changes, images & charts adapt to night mode for immersive UX.

Navigation System
Page-to-page navigation (airport departure → aircraft details).

Intuitive back buttons and theme toggles included

Real-Time Clock (PST)  → Automatically updates with the user’s system time.


APIs Used
OpenWeather API → Fetch live temperatures for airports.

Flight/Airline APIs → Retrieve logos, aircraft images, and airline metadata.

Data Sources → Real-world flight datasets + API-enhanced contextual data.



## Data Sources
the csv files are uploaded seperately. you can download them from there.
.pbix file is also provided for download 



##  How to Use
1. Download the `.pbix` file from this repo.  
2. Open it in **Power BI Desktop** (free to install).  
3. Interact with the dashboard using slicers and filters.  

##  Screenshots

<img width="1144" height="640" alt="image" src="https://github.com/user-attachments/assets/670a26ab-dfb3-47e5-8540-948de0a6cfad" />

<img width="1162" height="651" alt="image" src="https://github.com/user-attachments/assets/ad0240b6-b5d5-4f92-a6fb-45bc69ca39ad" />

<img width="1165" height="647" alt="image" src="https://github.com/user-attachments/assets/2fe22581-2dde-4276-ba0d-46430dd4ddc6" />

<img width="1164" height="645" alt="image" src="https://github.com/user-attachments/assets/02df3c84-1e03-440b-b439-75db383a4771" />



##  Key Insights
End-to-End Flight View

The dashboard doesn’t just show schedules — it connects departure & arrival airports, flight timings, aircraft type, weather conditions, and live maps.

This gives users a complete situational awareness of flights in one glance.

Real-Time + Contextual Data

Integration of live weather APIs adds more than just static flight data → it shows conditions passengers will face at departure and arrival.

The live clock & maps reinforce that this is an operational monitoring tool, not a static report.

Operational Efficiency Tracking

With the Active vs. Landed vs. Scheduled breakdown, stakeholders can monitor traffic flow and identify if flights are on time, delayed, or still in air.

This is valuable for airline operations or airport control rooms.

Aircraft-Level Insights

The second page zooms into aircraft details — capacity, range, engine type, and airline usage.

This connects operational scheduling (page 1) with fleet management (page 2) → a powerful link for aviation analytics.

User Experience Enhancements

Features like night mode toggle, airline search dropdown, and navigation buttons show strong focus on interactivity and UX — making the dashboard feel like a real app, not just a report.

Scalability of Approach

The same design pattern (departure/arrival, weather, maps, aircraft details) can scale to multiple airlines, airports, or even global air traffic monitoring.



##  Tools Used
- Power BI Desktop  
- Power Query (ETL)  
- DAX (Data Analysis Expressions)
  

## Author
- **Huzaima Imtiaz**  
  


