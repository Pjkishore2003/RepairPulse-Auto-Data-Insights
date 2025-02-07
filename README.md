**RepairPulse: Auto Data Insights**

##  Project Overview  
This project focuses on **analyzing vehicle repair data** to extract meaningful insights. The dataset consists of **100 records and 52 columns**, covering various aspects such as vehicle mileage, repair age, cost, complaint codes, and labor descriptions. The goal is to **clean the data, generate visualizations, identify trends, and create meaningful tags** to support proactive maintenance and customer service improvements.  

##  Files in This Repository  
- 📊 `cleaned_data.csv` → The cleaned and processed dataset.  
- 📄 `DA -Task 2..xlsx` → The original dataset used for analysis.  
- 🐍 `data_analysis_task2.py` → Python script for data processing, cleaning, and visualization.  
- 📑 `Task2_Report.pdf` → Summary report covering column analysis, data cleaning, visualizations, and insights.  
- 📜 `README.md` → This file, explaining the project details.  

## 🔍 Key Analysis & Findings  
### 1️⃣ **Data Cleaning Summary**  
✔ **Removed null columns** (e.g., `CAMPAIGN_NBR`)  
✔ **Handled missing values** (Categorical → 'UNKNOWN', Numerical → Median Imputation)  
✔ **Standardized text fields** (Fixed typos and capitalization mismatches)  
✔ **Identified high-cost outliers** ($3,000+ repairs, potential warranty claims)  

### 2️⃣ **Visualizations & Key Insights**  
📌 **Vehicle Mileage Distribution** → Most vehicles have lower mileage; a few have significantly high mileage.  
📌 **Repair Cost Distribution** → Most repairs are low-cost; a few high-cost outliers exist.  
📌 **Repair Age vs. Cost (Scatterplot)** → Older vehicles tend to have higher repair costs.  
📌 **Top 10 Complaint Codes** → Electrical, performance, and safety concerns are the most common.  
📌 **Correlation Heatmap** → Identifies key factors affecting repair costs.  

### 3️⃣ **Generated Tags**  
✅ **ELECTRICAL_ISSUE** → Battery, sensors, ECU failures  
✅ **SAFETY_CONCERN** → Brakes, airbags, or potential hazards  
✅ **PERFORMANCE_PROBLEM** → Engine stalling, power loss  
✅ **COMFORT_FEATURES** → Seat heating, infotainment, climate control  
✅ **RECURRING_ISSUE** → Repeat customer complaints  

## 🛠 How to Run the Analysis  
1. **Install dependencies**  
   ```sh
   pip install pandas seaborn matplotlib scikit-learn fuzzywuzzy python-Levenshtein
2. **Run the script**
   sh
   python data_analysis_task2.py


### **How to Use This File?**  
- **Save it as `README.md`** in your project folder.  
- It will be automatically displayed when you upload your project to **GitHub**.  

Let me know if you need any modifications! 

