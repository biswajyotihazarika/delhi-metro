# 🚇 Delhi Metro Network Analysis

This project performs data analysis on the Delhi Metro network using a dataset of stations, lines, layouts, and distances. The analysis provides insights into infrastructure distribution, inter-station spacing, and the growth of metro connectivity across the city.

---

## 📁 Dataset

- **File:** `Delhi metro.csv`
- **Contents:**  
  Includes details such as station names, metro lines, distance from the first station, layout type (e.g., Elevated, Underground), and geographical coordinates.

- **Note:** Ensure the file is in the same directory as the scripts or provide the full path:  
  `C:/Users/Neel/Desktop/DAP LAb/Delhi_Metro_Network_Analysis/Delhi metro.csv`

---

## 📊 Analyses Performed

### 1. `line_wise_station_count.py`
- **Objective:** Count total stations per metro line.
- **Insight:** The Blue Line has the highest number of stations, showing its role as a major transit corridor.

---

### 2. `layout_distribution.py`
- **Objective:** Visualize how stations are built (Elevated, Underground, or At Grade).
- **Insight:** Most stations are Elevated, suggesting a cost-effective construction strategy in non-dense regions.

---

### 3. `average_distance_per_line.py`
- **Objective:** Calculate average distance between stations for each metro line.
- **Insight:** Airport Express has the longest average spacing between stations, enabling faster intercity travel.

---

## 🛠️ Tools Used

- **Python 3.10+**
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`

> ✅ To install dependencies, run:
```bash
pip install pandas numpy matplotlib
