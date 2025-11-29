Goal

Using pandas, matplotlib.pyplot, and seaborn, based on a CSV file with advertising campaign data:
	1.	Build visualizations showing changes in daily spend and ROMI in 2021.
	2.	Analyze total spend and total ROMI across advertising campaigns.
	3.	Identify the distribution (spread) of daily ROMI for each campaign (boxplot).
	4.	Build a histogram of ROMI distribution.
	5.	Show the correlation between all numerical metrics.
	6.	Visualize the relationship between total_spend and total_value.

Data

CSV file with advertising campaign metrics (date, spend, revenue, campaign names, etc.).


Work Done

Data Preparation & Processing
	•	Grouped the data by day for the year 2021.
	•	Calculated ROMI, moving average of spend, and moving average of ROMI.

Trend Analysis
	•	Built a chart of daily spend in 2021.
	•	Built a chart of daily ROMI in 2021.

Campaign-Level Analysis
	•	Grouped data by campaign_name.
	•	Built a chart of total spend for each campaign.
	•	Built a chart of total ROMI for each campaign.

ROMI Exploration
	•	Created a boxplot to show the spread of daily ROMI across campaigns.
	•	Built a histogram of ROMI distribution.

Correlation Analysis
	•	Built a correlation heatmap for all numerical metrics.
	•	Identified metrics with the highest and lowest correlation values.
	•	Determined which metrics correlate with total_value.

Relationship Visualization
	•	Built a scatterplot with linear regression to visualize the relationship between
total_spend and total_value.


Result

A set of visualizations was created to demonstrate:
	•	the dynamics of spend and ROMI over time;
	•	comparison of metrics across campaigns;
	•	ROMI distribution;
	•	correlations between all numerical features;
	•	the relationship between total_spend → total_value.

This allows for quick insights into the performance and effectiveness of online advertising campaigns.

Tools
	•	Python
	•	pandas
	•	matplotlib
	•	seaborn
	•	Jupyter Notebook / Google Colab
