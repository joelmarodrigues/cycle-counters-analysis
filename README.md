# Cycling Traffic - Dublin Council Counters

This project applies **Exploratory Data Analysis (EDA)** techniques to investigate cycling traffic patterns in Dublin City. The dataset, provided by the Dublin City Council, contains the number of cyclists counted hourly across different street sensors.

![Counters Location](outputs/counters_loc.jpg)

Developed as part of the **Data Exploration & Preparation** module (Semester 7)  
BSc (Hons) in Computing & IT — CCT College Dublin

---

## Objectives

- Identify traffic patterns across multiple locations.
- Detect seasonal variations and daily peak hours.
- Apply clustering and PCA to support urban planning decisions.

---

## Key Results

### 1. Cyclist Distribution by Location  
![Total Cyclists](outputs/Total%20Cyclists%20in%20Dublin%20in%20202.png)

**Highest Traffic:** Grove Road Totem (~1 million cyclists)  
**Lowest Traffic:** Richmond Street (~2,200 cyclists)

---

### 2. Key Areas Clustered by Density  
![Key Areas](outputs/Correlation%20Between%20Cycle%20Counters.png)

- Grove Road Totem: High Traffic  
- Richmond Street: Moderate  
- Clontarf: Variable depending on time

---

### 3. Seasonal Traffic Pattern  
![Seasonal](outputs/Seasonal%20Number%20of%20Cyclists%20in%20Dublin%20in%202023.png)

- Peak: May (~600k), June (~550k)  
- Lowest: December (~300k)  
- Clear correlation with warmer months

---

### 4. Daily Peak Hours  
![Daily Peaks](outputs/Daily%20Number%20of%20Cyclist%20in%202023.png)

- 8:00 AM: ~1560 cyclists  
- 5:00 PM: ~1510 cyclists  
Morning and evening commute dominate daily trends.

---

## Conclusions

- **Plan Infrastructure:** Grove Road, Richmond Street, and Clontarf should be prioritised for cyclist infrastructure.  
- **Seasonal Variation:** Strong drop in cold months — public transport demand may need adjustment accordingly.  
- **Peak Hours:** Critical times are school/work commute. Improve traffic lights and signage to reduce congestion.  
- **Roadworks Impact:** Cycle counters should be relocated during roadworks to avoid data loss.  
- **Future Work:** Use clustering to optimise local cycling policies.

---

## Tools Used

- Python (Jupyter Notebook)
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (PCA, KMeans)

---

## References

- Dublin City Council and the NTA: Dataset available at https://data.gov.ie/dataset/dublin-city-centre-cycle-counts  
- IBM (n.d.): What is Exploratory Data Analysis (EDA)? Available at https://www.ibm.com/topics/exploratory-data-analysis  
- Towards Data Science: Guide to Exploratory Data Analysis. Available at https://towardsdatascience.com/a-data-scientists-essential-guide-to-exploratory-data-analysis-25637eee0cf6  
- SciPy Documentation: Interpolation Using SciPy. Available at https://docs.scipy.org/doc/scipy/tutorial/interpolate.html  
- Atlassian (n.d.): A Complete Guide to Scatter Plots. Available at https://www.atlassian.com/data/charts/what-is-a-scatter-plot  
- Leaflet: JavaScript Library for Interactive Maps. Available at https://leafletjs.com/  
- OpenStreetMap Contributors (n.d.): OpenStreetMap Data. Available at https://www.openstreetmap.org/  
- Eco-Multi Counter from Zelt Diamond Loop: Available at https://traffictechnology.co.uk/blog/portfolio/eco-display-light/  
- Marsja, E. (n.d.): How to Use Square Root, Log, & Box-Cox Transformation in Python. Available at https://www.marsja.se/transform-skewed-data-using-square-root-log-box-cox-methods-in-python/  
- Iqbal, M. (2024): Data Exploration & Preparation. Delivered as part of the Data Analysis module, BSc (Hons) in Computing in IT, CCT College Dublin. Available at https://moodle.cct.ie/course/view.php?id=1705  