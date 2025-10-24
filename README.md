Kenyan Olympic Performance Analysis

# Project Overview
This project analyzes Kenya's Olympic performance, focusing on medal achievements from 1956 to 2016, with an extended view to 2024 where data permits. The dataset, compiled from historical records, includes approximately 103 medals (30 Gold, 38 Silver, 35 Bronze) earned primarily in athletics and boxing, with an estimated 49 medals from 2000 to 2016. The analysis explores overall medal trends, gender breakdowns, regional comparisons with African nations (South Africa, Uganda, Nigeria, Ethiopia), and global context, highlighting the impact of the 1976 and 1980 boycotts. Visualizations were generated using Python (Matplotlib) and integrated into Canva for presentation.

Read more [https://brendachebyte.hashnode.dev/kenya-olympic-analysis-tracing-kenyas-athletic-excellence-through-data](https://brendachebyte.hashnode.dev/kenya-olympic-analysis-a-data-driven-journey-1?showSharer=true)

Access the detailed analysis report here https://kenya-olympic-tapestry.lovable.app/analysis

# Dataset
The core dataset contains Kenya's Olympic medal counts from 1956 to 2016, totaling 106 medals. It includes:
- Medal types: 30 Gold, 38 Silver, 35 Bronze.
- Sports: Predominantly athletics, with some boxing.
- Timeframe: Full record from 1956 to 2016, with a subset focus on 2000-2016 (~49 medals estimated).
- Additional data: Includes medal counts for South Africa, Uganda, Nigeria, and Ethiopia for comparative analysis, sourced from the same dataset or supplemented by IOC records.
- Source: Your provided DataFrame 'df' with columns like 'NOC', 'Year', 'Medal', and 'ID', validated against historical Olympic data.

# Methodology
The project uses Python (pandas, Matplotlib) for data processing and visualization. Key steps include:
- Filtering the DataFrame for Kenya (NOC='KEN') and valid medals.
- Grouping data by year and medal type to track trends (e.g., Gold, Silver, Bronze counts).
- Creating visualizations: grouped bar charts for medal trends, stacked bars for gender breakdowns, and comparative charts for African nations.
- Adding features like minor ticks on x-axes (every 2 years) and legends for medal colors (#CD7F32 for Bronze, silver for Silver, gold for Gold).
- Handling missing data by filling with zeros and estimating medal types from totals when needed.

# Findings
- Kenya won approximately 103 medals from 1956-2016, with growth from 1 medal in 1964 to 13 in 2016, peaking at 16 in 2008.
- Gender analysis (2000-2016) shows women’s medals rose from 2 in 2000 to 7/13 (54%) in 2016, reflecting equity gains.
- Medal trends indicate Gold dominance (e.g., 6 in 2008), with boycotts (1976/1980) causing zeros.
- Regionally, Kenya leads Africa (~50% of medals), with early joiners (1960s) like Ethiopia and late joiners like Nigeria (1972).
- Globally, Kenya’s efficiency (0.98 medals/million) ranks ~10th-12th among top nations.

# Visualizations
- Slide 1: Introduction to Kenyan Olympic Journey (text overview).
- Slide 2: Kenya Medal Trends (grouped bar chart, kenya_medal_trends_bar.png).
- Slide 4: Kenya Medalist Gender Breakdown (stacked bar chart, kenya_gender_trends_with_medals.png).
- Slide 5: African Medal Trends and Comparisons (grouped bar chart, african_yearly_comparison_from_df.png).
- Slide 7: Medal Efficiency (horizontal bar chart, medal_efficiency_2000_2016.png).
- Slide 8: Kenya in Global Top 10 Context (bar chart, global_top10_context.png).


# Technical Details
- Tools: Python (pandas, Matplotlib) for analysis, Canva for presentation design.
- Data Source: kaggle, merged athlete_events.csv and noc_regions.csv
- Code: Available in the project scripts.
- Output: PNG files for each slide.

# License
This project is licensed under the MIT License.

# Contact
For questions or contributions, please contact:
- Name: [Brenda Chebet]
- Email: [koskeybrenda1@gmail.com]
