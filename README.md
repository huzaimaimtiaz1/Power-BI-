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
Real-Time Clock (PST) ⏰ → Automatically updates with the user’s system time.


APIs Used
OpenWeather API → Fetch live temperatures for airports.
Flight/Airline APIs → Retrieve logos, aircraft images, and airline metadata.
Data Sources → Real-world flight datasets + API-enhanced contextual data.



## 🗂️[Uploading flights_data_with_aircraft.csv…]()
 Data Sources
- Source: **[Excel, CSV, SQL, etc.]**  
- Size: **[rows/columns if relevant]**  
- Notes: **[if you cleaned/combined/created mock data]**

---

## 🚀 How to Use
1. Download the `.pbix` file from this repo.  
2. Open it in **Power BI Desktop** (free to install).  
3. Interact with the dashboard using slicers and filters.  

*(If you’ve published it to Power BI Service, you can also add a live dashboard link here.)*  

---

## 📷 Screenshots
*(Insert one or two images of your dashboard for quick preview)*  

![Dashboard Preview](screenshot.png)

---

## 📈 Key Insights
- Insight 1: e.g., *“Sales peak in Q4 driven by holiday campaigns.”*  
- Insight 2: e.g., *“Customer churn highest in Region A compared to Region B.”*  
- Insight 3: e.g., *“Top 10 products account for 70% of total revenue.”*  

---

## 🛠️ Tools Used
- Power BI Desktop  
- Power Query (ETL)  
- DAX (Data Analysis Expressions)  

---

## 👤 Author
- **[Your Name]**  
- LinkedIn: [Your Profile]  
- GitHub: [Your Profile]  

---
