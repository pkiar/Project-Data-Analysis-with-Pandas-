 # Phase One Project 

# Introduction: Overview

As Part of the company to venture into avaition Business, this project investigates the risk associated with different aircraft , aiming to identify the safest model for potention investment.The analysis focuses on determining which types of flights have the highest average fatalities and aircraft damage, assessing how engine types and weather conditions affect safety, and ranking aircraft make by risk level for commercial use.


The dataset used comes from the National Transportation Safety Board (NTSB) and includes records of aviation accidents and incidents from 1962 to 2023.The tools to be used in achieving this are:
       
    1.Pandas - Data cleaning, transformation, and aggregation </li>
    2.Numpy - Numerical computations</li>
    3.Matplotlib / seaborn - Static visualizations for analysis validation</li>
    4.Plotly - Interactive graphs for dynamic data exploration</li>

# Problem Statement

Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

# Goal
The Data Analysis goals are:To find out?

    1.Which flight types have the highest average fatalities and aircraft damage? 
    2.What effect do engine types have on safety, and how is this affected by weather conditions?
    3.What aircraft make have the lowest risk for commercial ventures?

  # Steps
  The Steps used to achieve the goals were;
    1.Define the problem statement.

    2.Data Preperation
        Data Cleaning using Pandas 
        - Removed irrelevant or empty columns  
        - Handled missing values using median imputation  
        - Standardized categorical data  
        - Trimmed whitespaces and formatted date columns 

    3.Aggregate and analyze the data to identify low-risk aircraft.

    4.Create visualizations to support findings.
        Visualization
        - Created plots using **Matplotlib** and **Seaborn**:
        - Fatalities by aircraft type  
        - Purpose of flight vs accident severity  
        - Weather impact on accident outcomes

    5.Translate findings into three actionable business recommendations.

# Tools Used
    - Python (Pandas, NumPy, Matplotlib, Seaborn)
    - Jupyter Notebook


# Dataset
- **Source:** National Transportation Safety Board (via Kaggle)
- **File:** data/Aviation_Data.csv  

 **Columns** 
 ['Event.Id', 'Investigation.Type', 'Accident.Number', 'Event.Date',
       'Location', 'Country', 'Latitude', 'Longitude', 'Airport.Code',
       'Airport.Name', 'Injury.Severity', 'Aircraft.damage',
       'Aircraft.Category', 'Registration.Number', 'Make', 'Model',
       'Amateur.Built', 'Number.of.Engines', 'Engine.Type', 'FAR.Description',
       'Schedule', 'Purpose.of.flight', 'Air.carrier', 'Total.Fatal.Injuries',
       'Total.Serious.Injuries', 'Total.Minor.Injuries', 'Total.Uninjured',
       'Weather.Condition', 'Broad.phase.of.flight', 'Report.Status',
       'Publication.Date']
**Column used**
['Event.Id', 'Investigation.Type', 'Accident.Number', 'Injury.Severity',
       'Aircraft.damage', 'Aircraft.Category', 'Make', 'Model',
       'Amateur.Built', 'Number.of.Engines', 'Engine.Type',
       'Purpose.of.flight', 'Total.Fatal.Injuries', 'Total.Serious.Injuries',
       'Total.Minor.Injuries', 'Total.Uninjured', 'Weather.Condition']  

# Conclusion and Recommendation 
    1. Based on the data, skydiving, firefighting, and executive flights show the highest risk of fatalities and aerial application activities demonstrate the least risk.
    2. The data suggests that a single-engine setup might be more conducive to surviving adverse weather conditions. The larger volume of data for single-engine aircraft likely contributes to its higher accuracy.I believe the dataset lacked enough data for multiple engine planes.
    2. Begin operations with Executive/Corporate or Small Business Charter aircraft, where accident frequency and fatality rates are lower.
    3. For commercial ventures prioritizing safety, aircraft from Maule, Bellanca, and Rockwell represent the lowest risk choices in this dataset.
    Overall, consistent maintenance practices, pilot training, and operational oversight remain the key determinants of aviation safety, regardless of manufacturer.
    4. Choosing aircraft with low fatality and damage rates helps reduce financial risk and improve profitability in commercial aviation.
    5. Invest in pilot training programs, aircraft maintenance, and weather monitoring systems to make the airplane extra safe.

# How to Run
    1. Fork the repo
    2. Clone the repo  
       https://github.com/pkiar/Project-Data-Analysis-with-Pandas-.git
    3. Install dependencies
       pip install -r requirements.txt
    4. Results
      All visualizations are saved in the /plots folder and summarized in Tableau.  
       Tableau links: https://public.tableau.com/authoring/AviationSafetyDataAnalysisVisualizingRiskPatternsUsingPython/Dashboard3#5

# License
This project is for educational and analytical purposes only.       


Kiarie Muhia
Data Scientist
