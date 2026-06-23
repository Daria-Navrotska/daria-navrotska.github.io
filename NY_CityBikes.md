# Mapping the Pulse of NYC: A 2022 Citi Bike Demand

Since its launch in 2013, Citi Bike has grown into New York City’s largest bike-sharing program and one of the biggest worldwide. Rising demand - especially since the COVID-19 pandemic - has exposed weaknesses in station capacity and bike distribution. Stations in busy commuter areas often run out of bikes, while others remain full, preventing returns. This project investigates the causes of such imbalances and provides data-backed recommendations to improve operational efficiency and customer satisfaction.

## Project Goal
Analyze user behavior of a bike-sharing service based in New York City (USA) to help the business strategy department
assess the current logistics model of bike distribution across the city and identify expansion opportunities.

## Objectives
The main objective is to perform a descriptive analysis of Citi Bike’s 2022 data and generate actionable insights about:

- Where and when bike shortages or surpluses occur?
- Which stations experience the highest demand?
- How seasonality and weather affect bike usage?
- Whether current station placement ensures fair coverage across the city?

## Data:
- [Citi Bike Dataset](https://s3.amazonaws.com/tripdata/index.html): Open-source transaction data capturing New York bike-sharing trips throughout the year 2022 (including start/end times, station locations, and trip types).  
- Weather Data from [NOAA](https://www.noaa.gov/) LaGuardia Airport Station: Enrichment dataset sourced via NOAA’s API service to account for daily environmental factors affecting ridership.
- [Waterfront Access Plans](https://data.cityofnewyork.us/Environment/Waterfront-Access-Plans/d9z4-v86m).

## Scope
- Build hands-on experience with Python, API integration, and interactive geospatial mapping in a real-world urban logistics context.
- Learn to translate raw, large-scale trip logs and weather data into strategic insights for business decision-makers.
- Gain exposure to cross-functional data delivery, serving as the bridge between technical analytics and business development teams.
- Craft a compelling strategic dashboard project that highlights data engineering, visualization, and deployment skills. 

## Tools:
- Python (v3.13): pandas, requests, matplotlib, seaborn, plotly, kepler.gl, streamlit.
- Jupyter Notebook / Anaconda.
- API from the National Centers for Environmental Information (NOAA).

## Skills:
- API data sourcing and programmatic data integration.
- Structured data cleaning, aggregation, and merging of disparate datasets within Python.
- Spatial data manipulation and interactive mapping.
- Dashboard interface design, UI/UX optimization, and multi-page deployment.  
- Presenting insights and recommendations to stakeholders.
- Storytelling and reporting.

# Methodological Approach
## Project Planning
Formulated analytical questions to guide dashboard development:
- Which stations attract the highest ridership in the city?
- During which months is trip activity at its peak? Does the weather influence travel patterns?
- What are the most common station-to-station routes?
- How evenly are stations spread across the network?
- Designed a visualization plan pairing each question with an appropriate chart or map.

## Data Sourcing and Preparation
- Downloaded Citi Bike 2022 trip data and sourced daily weather data from NOAA’s API.
- Used list comprehension and generators to efficiently read and combine multiple monthly CSV files.
- Cleaned datasets, standardized date formats, and merged the trip and weather data for combined analysis.

## Descriptive and Exploratory Analysis
- Calculated trip frequencies by station and month to identify demand peaks.
- Analyzed seasonal trends and correlations with temperature and precipitation.
- Mapped the geographic distribution of stations to identify underserved areas.

## Visualization and Dashboard Deployment
- Created visualizations using Matplotlib, Seaborn, and Plotly.
- Designed interactive geospatial maps in Kepler.gl.
- Built a prototype dashboard in Streamlit, organizing visual outputs into clear sections: Popular Stations, Seasonal Patterns, Weather Impact, Station Distribution.

---

## ...?

...

![...](images/picture_1.png)

## ...

...

![picture name](images/picture_2.png)

## ...

...

![picture name](images/picture_3.png)

## Key Findings:

- Temporal Constraints: Severe shifts in ridership occur across different seasons, pointing to a need for fluid seasonal strategy rather than a static model.
- Logistical Bottlenecks: Specific high-traffic routes create daily "docks full" or "empty station" crises, showing that distribution issues stem from asymmetric commuting patterns.
- Weather Sensitivity: Clear correlations between specific weather thresholds and dramatic usage spikes/drops, which serves as a predictive indicator for bike demand. 

## Recommendations:

- Implement a dynamic, predictive bike rebalancing schedule that proactively moves assets ahead of high-traffic hours.
- Align station maintenance and fleet scaling plans closely with seasonal demand models to avoid under-utilization in off-peak periods.
- Optimize business development and marketing targets toward expanding station capacities at identified bottleneck hubs. 
  
---

## Project Challenges 

- Managing and cleaning massive, multi-gigabyte open-source trip logs alongside API-driven unstructured weather data.
- Presenting intricate spatial-temporal insights without overwhelming non-technical stakeholders. 

## Solutions:

- Leveraged optimized Pandas aggregations and programmatic sorting to merge weather profiles with trip metrics cleanly.
- Utilized Streamlit's multi-page design principles to separate different variables across individual tabs, creating a scannable narrative.  

![picture name](images/picture_4.png)

---

## Future Steps:

Integrating real-time inventory tracking and expanding the dataset across consecutive years to form predictive machine learning models for live fleet rebalancing.

![Picture name](images/picture_5.png)

---

## Project Files

For more details, see the [new-york-citi-bike-2022](https://github.com/Daria-Navrotska/new-york-citi-bike-2022) project on GitHub, [New York CitiBike 2022](https://new-york-citi-bike-2022-dashboard.streamlit.app/) dashboard on Streamlit, and video presentation ["Exploring New York Citi Bike Strategy Dashboard](https://share.vidyard.com/watch/1e3J4ggaPqn8eUq59r6PGE).
