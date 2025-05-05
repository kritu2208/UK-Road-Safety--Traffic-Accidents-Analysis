# 🚗 UK Road Safety & Traffic Accidents Analysis

A data analysis project exploring road safety and traffic accident patterns across the UK. Using real-world datasets, this project investigates accident causes, severity, contributing factors, and geospatial patterns with the goal of informing better road safety policies and urban planning.

---

## 📌 Project Objectives

- Analyze traffic accident trends across the UK
- Identify common causes and contributing factors of accidents
- Examine severity levels based on time, weather, road type, etc.
- Visualize high-risk areas using geospatial plots
- Derive actionable insights for road safety improvements

---

## 📂 Dataset

**Source:** [UK Government - Department for Transport](https://data.gov.uk/dataset/road-safety-data)

The dataset includes:
- Date and time of accidents
- Location (latitude & longitude)
- Number of casualties
- Road and weather conditions
- Light and surface conditions
- Vehicle and driver information
- Severity (Slight, Serious, Fatal)

---

## 📁 Project Structure

UK-Road-Safety--Traffic-Accidents-Analysis/
├── UK_Road_Safety_Analysis.ipynb # Main analysis notebook
├── Accidents_UK.csv # Dataset (or link to it)
├── images/ # Visualizations used in the notebook
└── README.md # Project documentation


---

## 🔍 Exploratory Data Analysis (EDA)

The EDA covers:

- **Temporal Analysis**: Accidents per year, month, day, and hour
- **Severity Analysis**: Proportion of fatal, serious, and slight accidents
- **Weather & Road Conditions**: Impact of fog, rain, icy roads, etc.
- **Casualties Distribution**: Number of injuries and deaths
- **Light Conditions**: Accidents in daylight vs darkness
- **Day of Week Patterns**: Are weekends riskier?

---

## 🗺️ Geospatial Analysis

- Heatmaps of accident locations
- Mapping high-risk zones using latitude/longitude
- Clustering accident-prone areas (optional with KMeans or DBSCAN)

_Example Map:_  
![Heatmap](images/accident_heatmap.png)

---

## 📈 Visualizations

- Line plots for trends over time
- Pie charts for accident severity distribution
- Count plots for categorical features (road type, light condition)
- Heatmaps to show correlations
- Bar graphs for top contributing factors

_Example Charts:_

![Severity Chart](images/severity_pie.png)  
![Time Series](images/monthly_accidents_trend.png)

---

## 🧠 Key Insights

- Most accidents occur during **rush hours** (8–9 AM & 5–6 PM)
- **Wet or icy roads** significantly increase accident severity
- **Urban single-carriageway roads** report the highest number of collisions
- Fatalities are more likely to occur during **night time in poor lighting**
- **Sundays** have fewer accidents but more fatal ones proportionally

---

## 🛠️ Tools & Technologies

| Category            | Tools Used                             |
|---------------------|-----------------------------------------|
| Language            | Python                                  |
| Data Manipulation   | pandas, numpy                           |
| Visualization       | seaborn, matplotlib, plotly, folium     |
| Mapping             | folium, geopandas (optional)            |
| Notebook            | Jupyter Notebook                        |

---

## 📌 Future Improvements

- Apply clustering to detect accident hotspots
- Predict severity based on weather, road, and driver conditions using ML
- Build an interactive dashboard using Plotly Dash or Tableau
- Incorporate real-time data from APIs (if available)

---

## 🚦 Real-World Applications

- Urban planning and traffic control strategies
- Dynamic speed regulation and hazard alerts
- Road maintenance prioritization
- Policy-making based on time and weather patterns

---

## 🧾 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

- Dataset by the UK Department for Transport
- Project inspired by real-world transportation analytics and public safety concerns

---

## ⭐ Like this Project?

If you found this project interesting or helpful, feel free to give it a ⭐ on GitHub!


