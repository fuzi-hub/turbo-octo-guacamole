
# 🏙️ Airbnb NYC 2019 Exploratory Data Analysis

This project explores Airbnb listing data in New York City using 2019 public data. Through a series of visualizations and statistical summaries, the analysis identifies distribution patterns, pricing structures, availability trends, host behavior, spatial dynamics, and customer engagement insights across the platform.

---

## 📌 Objectives

1. Examine the distribution of Airbnb listings across different neighbourhoods and boroughs in New York City.  
2. Analyze the pricing structure of Airbnb listings and identify the factors influencing listing prices.  
3. Investigate the relationship between availability (number of days per year) and price, room type, and neighborhood.  
4. Assess host activity levels by evaluating number of listings per host and total reviews.  
5. Identify and visualise spatial patterns of Airbnb density and pricing using geolocation data.  
6. Explore customer engagement through review frequency and evaluate its relationship with pricing or availability.  

---

## 📊 Interpretation by Objective

### ✅ Objective 1: Distribution of Listings Across Boroughs and Neighborhoods  
The analysis showed that Airbnb listings are heavily concentrated in **Manhattan** and **Brooklyn**, which together account for the majority of all listings in New York City. Neighborhoods such as **Williamsburg**, **Harlem**, and **Bedford-Stuyvesant** appeared as top Airbnb hubs, while areas like **Staten Island** and **The Bronx** were underrepresented. This indicates a strong urban-tourism bias in listing distribution and reveals geographic gaps that may present opportunities for growth in lesser-sat...

### ✅ Objective 2: Pricing Structure and Influencing Factors  
Airbnb prices in NYC are highly variable, with most listings priced below $500 but a long tail of luxury or overpriced listings stretching far beyond. **Entire home/apartment** listings command the highest average rates, especially in **Manhattan**, while **shared** and **private rooms** are more budget-friendly. Interestingly, price had only weak correlations with numerical factors like availability and reviews, suggesting that **location and room type** are far stronger pricing determinants.

### ✅ Objective 3: Availability vs. Price, Room Type, and Neighborhood  
The availability of listings (number of days per year) followed a **bimodal distribution**, with many listings either always available or rarely available. **Private rooms** showed higher average availability than entire homes, likely due to lower personal usage or regulatory restrictions. Scatter plots revealed no strong correlation between availability and price, indicating that hosts may keep listings open regardless of price point, perhaps to stay flexible or maximize occupancy.

### ✅ Objective 4: Host Activity Levels and Reviews  
Most hosts in the dataset manage only one listing, but a small group of **"power hosts"** own dozens of properties, suggesting a semi-professional or commercial presence on the platform. Interestingly, those with the most listings weren’t necessarily the ones with the most guest reviews, implying that guest satisfaction and visibility aren’t solely driven by portfolio size. The analysis suggests that **quality and engagement** matter more than volume in maintaining host success.

### ✅ Objective 5: Spatial Patterns in Listing Density and Pricing  
Geospatial visualizations showed that Airbnb listings are densely clustered in central locations like **Lower Manhattan**, **Brooklyn Heights**, and **Harlem**. Heatmaps and scatter plots highlighted how **higher-priced listings** are often found in downtown or tourist-frequented areas, while **outer boroughs** host more budget-friendly options. Room types are also spatially stratified, with shared rooms spread across a broader radius, and entire apartments clustered more centrally.

### ✅ Objective 6: Guest Engagement via Reviews and Their Relationships  
Most Airbnb listings receive only a few reviews per month, and while some listings had hundreds of total reviews, many others had very few, showing unequal guest engagement across the platform. The analysis found no strong correlation between **review frequency and price or availability**, suggesting that engagement is influenced more by **host behavior, communication, and stay quality** than by pricing or availability alone. This underscores the importance of experience design over simply being active o...

---

## 📈 Actionable Insights

### 🔹 1. Location Strategy  
While Manhattan and Brooklyn dominate, **Queens and The Bronx** show untapped growth potential due to low competition. Targeting these outer boroughs may offer better visibility and affordability advantages for new or mid-level hosts.

### 🔹 2. Pricing Optimization  
Since price is driven more by **location and room type** than engagement, hosts should benchmark locally rather than globally. Entire apartments in central boroughs can be priced premium, while private rooms in outer boroughs suit budget travelers.

### 🔹 3. Availability Management  
Private rooms with high availability tend to perform well. Hosts unable to list properties full-time should favor **flexible, room-based offerings** to stay competitive and booked.

### 🔹 4. Host Strategy and Growth  
New hosts should emphasize **guest satisfaction and review volume** before scaling listings. High engagement matters more than sheer listing count in sustaining long-term success.

### 🔹 5. Geographic Expansion Opportunities  
Heatmaps reveal strategic gaps in areas like **Staten Island, East Bronx**, and **parts of Queens** — zones that offer cost-effective entry points for new hosts.

### 🔹 6. Experience Over Exposure  
Boosting reviews requires more than visibility — it depends on **host responsiveness, stay quality**, and accurate listings. Engagement-first strategy yields long-term growth.

---

## 🧠 Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn, Plotly)
- Jupyter Notebook
- NYC Open Data (2019 Airbnb dataset)

---

## ✍️ Author

**[Your Name]**  
Data Analyst | EDA Specialist  
GitHub: [yourgithubhandle]  
LinkedIn: [yourlinkedinurl]

---
