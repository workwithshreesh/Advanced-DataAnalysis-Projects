# End-to-End Cricket Data Analysis Project

## Overview

Welcome to the **End-to-End Cricket Data Analysis** project! Developed based on the tutorials by Codebasics, this project encompasses the entire data analysis pipeline from data collection to insightful dashboard development. The project uses advanced data analysis techniques and tools such as SQL, Power BI, DAX, and Power Query to uncover valuable insights into cricket data, helping you understand trends, player performance, match outcomes, and more.

## Features

- **Complete Data Analysis Pipeline:** From data collection, cleaning, and transformation to analysis and visualization.
- **Advanced Analytical Tools:** Utilizes SQL for data handling, Power BI for visualization, DAX for calculations, and Power Query for data transformation.
- **Insightful Dashboards:** Interactive dashboards in Power BI providing detailed insights into various cricket statistics.
- **Comprehensive Documentation:** Step-by-step documentation of the entire process for easy understanding and replication.

## Repository Structure

```
.
├── DataCollection
│   ├── data_collection_script.sql
├── DataCleaning
│   ├── cleaning_script.sql
│   └── power_query_steps.txt
├── DataModeling
│   ├── dax_calculations.txt
├── DataAnalysis
│   ├── analysis_report.md
│   └── visualizations.pbit
├── Dashboard
│   └── cricket_dashboard.pbix
├── Insights
│   └── insights_report.md
└── README.md
```

## Process

### Data Collection

- **Tasks:** Collecting cricket data from reliable sources.
- **Tools Used:** SQL scripts for extracting and loading data.

### Data Cleaning and Transformation

- **Tasks:** Removing null values, eliminating unnecessary columns, handling duplicates, and adjusting data types.
- **Tools Used:** SQL for initial cleaning, Power Query for advanced data transformation.

### Data Modeling

- **Tasks:** Creating calculated measures and tables using DAX in Power BI.
- **Examples:**
  ```DAX
  # Example DAX Calculation for Player Average
  PlayerAverage = 
  DIVIDE(
    SUM(CricketData[Runs]),
    COUNT(CricketData[Matches])
  )
  ```

### Data Analysis

- **Tasks:** Performing detailed data analysis to uncover trends, player performance metrics, and match outcomes.
- **Tools Used:** Power BI for visualization, detailed reporting in Markdown files.

### Dashboard Development

- **Tasks:** Developing interactive and dynamic dashboards in Power BI to present the data insights clearly.
- **File:** `cricket_dashboard.pbix`

### Insights

- **Tasks:** Summarizing key insights derived from the analysis.
- **File:** `insights_report.md`

## Key Insights

- **Player Performance:** Detailed analysis of individual player performance across different matches and seasons.
- **Team Statistics:** Comparative statistics of different cricket teams.
- **Match Outcomes:** Trends and patterns in match outcomes over time.
- **Venue Analysis:** Performance statistics based on different cricket venues.

## How to Use This Repository

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/workwithshreesh/Cricket-Data-Analysis.git
   cd Cricket-Data-Analysis
   ```

2. **Follow the Process:**
   Navigate through each directory and follow the steps documented in the respective files for data collection, cleaning, transformation, modeling, and analysis.

3. **Explore the Dashboard:**
   Open the `cricket_dashboard.pbix` file in Power BI to interact with the visualizations and gain insights.

4. **Review the Insights:**
   Read the `insights_report.md` file for a summary of the key insights derived from the analysis.

## Contributing

Contributions are welcome! If you have suggestions for new features, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## Contact

If you have any questions or feedback, feel free to contact me at [Shreesh Tiwari](mailto:your-shreesht366.com).


---

If you found this project helpful, please give it a star and follow the repository for more advanced data analysis projects!

Happy analyzing!