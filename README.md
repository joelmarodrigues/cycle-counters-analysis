# Cycling Traffic - Dublin Council Counters

This project applies **Exploratory Data Analysis (EDA)** techniques to investigate cycling traffic patterns in Dublin City. The dataset, provided by the Dublin City Council, contains the number of cyclists counted hourly across different street sensors.

---

## Project Context

This work was developed as part of the **Data Exploration & Preparation** module (Semester 7) of the BSc (Hons) in Computing & IT at **CCT College Dublin**.

---

## Objectives

- Identify high and low traffic areas for cyclists.
- Understand seasonal and daily cycling trends.
- Use clustering (K-Means) and PCA to uncover insights.
- Support planning decisions through data-driven findings.

---

## Visual Insights

**1. Sensor Correlation Heatmap**  
![Sensor Correlation](outputs/Correlation%20Between%20Cycle%20Counters.png)

---

**2. Daily Cyclist Volume (2023)**  
![Daily Count](outputs/Daily%20Number%20of%20Cyclist%20in%202023.png)

---

**3. Seasonal Trends**  
![Seasonal Trends](outputs/Seasonal%20Number%20of%20Cyclists%20in%20Dublin%20in%202023.png)

---

**4. Distribution of Cyclists per Location**  
![Total Cyclists](outputs/Total%20Cyclists%20in%20Dublin%20in%20202.png)

---

**5. Distribution Histogram**  
![Histogram](outputs/Distribution%20Histogram.png)

---

**6. Skewness & Kurtosis**  
![Skewness & Kurtosis](outputs/Distribution%20of%20Skewness%20and%20Kurtosis.jpg)

---

**7. K-Means Cluster Overview**  
![Clusters](outputs/Average%20Values%20of%20Key%20Columns%20by%20Top%20Clusters.png)

---

## 📁 Project Structure

| File                                | Description                                 |
|-------------------------------------|---------------------------------------------|
| `cycle_data.csv`                    | Main processed dataset                      |
| `cycle_data_PCA.csv`                | Dataset with PCA components                 |
| `cycle_data_pca_scaled.csv`         | Scaled version for clustering               |
| `cycle-counts-2023.csv`             | Raw counts by Dublin Council                |
| `counters_locations.csv`            | Sensor metadata (locations)                 |
| `/outputs/`                         | Images used in the visual analysis          |
| `std.csv`                           | Std values by cluster                       |
| `.ipynb` + `.pptx`                  | Report and slides (final submission)        |

---

## Technologies

- Python (Jupyter Notebook)
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn (KMeans, PCA)
- Feature Engineering, Outlier Detection, Standardisation

---

## References

- Dublin City Council and the NTA: Dataset available at https://data.gov.ie/dataset/dublin-city-centre-cycle-counts  
- IBM (n.d.): [What is EDA](https://www.ibm.com/topics/exploratory-data-analysis)  
- [Guide to EDA – Towards Data Science](https://towardsdatascience.com/a-data-scientists-essential-guide-to-exploratory-data-analysis-25637eee0cf6)  
- [SciPy Interpolation Docs](https://docs.scipy.org/doc/scipy/tutorial/interpolate.html)  
- [Scatter Plots – Atlassian Guide](https://www.atlassian.com/data/charts/what-is-a-scatter-plot)  
- [Leaflet JS Library](https://leafletjs.com/)  
- [OpenStreetMap](https://www.openstreetmap.org/)  
- [Zelt Eco-Multi Counter](https://traffictechnology.co.uk/blog/portfolio/eco-display-light/)  
- [Transform Skewed Data – Marsja](https://www.marsja.se/transform-skewed-data-using-square-root-log-box-cox-methods-in-python/)  
- Iqbal, M. (2024): *Data Exploration & Preparation*, CCT College Dublin – [Module Page](https://moodle.cct.ie/course/view.php?id=1705)