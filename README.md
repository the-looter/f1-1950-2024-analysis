# -Formula-1-World-Championship-1950-2024-Dataset-Analysis
Data analysis of Formula 1 World Championship (1950–2024) using Python, Pandas, and Seaborn — exploring race statistics, driver nationalities, constructor performances, and lap time trends
## 📂 Dataset Files
The project utilizes multiple CSV files:
- circuits.csv  
- constructor_results.csv  
- constructor_standings.csv  
- constructors.csv  
- driver_standings.csv  
- drivers.csv  
- lap_times.csv  
- pit_stops.csv  
- qualifying.csv  
- races.csv  
- results.csv  
- seasons.csv  
- sprint_results.csv  
- status.csv  

---

## 🧹 Data Cleaning
- Handled null values in **races** and **qualifying** files by replacing missing times with `00:00:00`.  
- Removed newline characters and dropped unnecessary columns (like “number” in drivers.csv).  
- Dropped columns with excessive nulls (e.g., “points” in constructor_results.csv).  

---

## 📊 Key Insights
- 🇬🇧 **British drivers** have the highest participation rate in Formula 1 history.  
- 🕐 The **fastest lap time** recorded was `0:55.404`, and the **slowest** was `9:45.712`.  
- 🏆 The **highest constructor performance** recorded was **21 wins** with **860 points**; the lowest was **6 points** with **0 wins**.  

---

## 🧠 Tools & Libraries Used
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Formula1-World-Championship-Analysis.git
Open the notebook in Jupyter:

bash
Copy code
jupyter notebook "Formula 1 World Championship (1950 - 2024).ipynb"
