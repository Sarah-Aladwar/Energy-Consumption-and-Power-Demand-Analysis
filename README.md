Energy Consumption and Power Demand Analysis

 Project Overview
This project investigates energy consumption patterns across regions and time periods, leveraging a dataset of energy records for 2013. The analysis aims to identify significant consumption differences, optimize resource allocation, and provide actionable insights for energy management.

 Folder Structure
- Data/: Contains the data files for analysis.
- Scripts/: Contains the Jupyter notebooks for the analysis ('Analysis.ipynb') and the dashboard ('Dashboard.ipynb').
- Report/: Contains the final report in PDF format ('Energy Consumption and Power Demand Report.pdf').
- requirements.txt: Lists the dependencies needed to run the project.

 Abstract
Key objectives of this analysis include:
- Understanding regional and temporal variations in energy consumption.
- Applying preprocessing techniques to ensure data integrity.
- Optimizing energy usage and cost savings through targeted strategies.

 Datasets
The project uses the following datasets:

1. Energy Consumption Data
   - Records for 82 unique cells across four regions (A, B, C, and D).
   - Time intervals of 30 minutes over the year 2013.

2. Power Demand Data
   - Half-hourly energy demand records.
   - Demand prices categorized into high, normal, and low demand levels.

 Key Features
- Data Cleaning: Removed duplicates, imputed missing values, and handled anomalies.
- Exploratory Data Analysis: Investigated consumption trends across regions and times of day.
- Statistical Analysis: Conducted ANOVA tests to validate regional and temporal consumption differences.
- Optimization: Applied thresholds to reduce energy consumption and costs by approximately 6.7% and 6.5%, respectively.
- Interactive Dashboards:
  - Energy Consumption Dashboard: Features interactive plots for average energy consumption aggregated by different intervals (e.g., hourly, monthly).
  - Energy and Cost Savings Dashboard: Includes a dynamic threshold adjuster, allowing users to select a percentile and view corresponding energy and cost savings, alongside insightful static visualizations.

 Results and Insights
1. Regional Patterns:
   - Region A has the highest consumption and variability, while Region D demonstrates the lowest.
   - Regions A and C exhibit dynamic energy demands; Region D remains stable and low.

2. Temporal Trends:
   - Peak energy consumption occurs during evening hours (6–8 PM).
   - Region-specific hourly trends reflect varying socio-economic activities.

3. Optimization Outcomes:
   - Threshold: 25th percentile
   - Energy saved: 13,841.88 kWh.
   - Cost saved: E£2,827.48.

 Technologies Used
- Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, Pingouin, Plotly, Dash.
- Tools: Jupyter Notebook.

 Usage Instructions
1. Clone the repository.
2. Ensure the necessary Python libraries are installed using:
   ```bash
   pip install pandas numpy matplotlib seaborn pingouin plotly dash 
   ```
3. Run the Jupyter Notebooks provided to reproduce the analysis.
4. Launch the interactive dashboards by running the respective Dash app scripts.

 Achievements
This project was completed as part of the Tech Her Up Program - Data Science Track and received a perfect grade of 100%.

 Future Work
-Develop predictive models using machine learning techniques (e.g., time series forecasting) to predict future energy consumption trends based on historical data.
- Apply clustering algorithms to identify groups of regions or cells with similar consumption patterns, aiding in targeted energy management strategies.
- Train classification models to predict high-demand periods based on contextual features like weather, holidays, or time of day.

 Contact
Prepared by: Sara Ibrahim  
Program: Tech Her Up - Data Science Track at Carerha 

For any inquiries, please reach out through the GitHub repository's Issues section.
