# Data-analyst-projects

A data analyst specializes in collecting, processing, and performing statistical analyses on large datasets. They interpret data to discover patterns and deliver reports with clear visualizations to communicate their findings and support decision-making. Data analysts often work in many sectors, including finance, healthcare, technology, and government.

Key responsibilities of a data analyst typically include:

- Collecting data from primary or secondary sources and maintaining databases.
- Cleaning and preprocessing the data to ensure accuracy, completeness, and uniformity.
- Exploring and analyzing the data using statistical techniques.
- Creating visual representations of data, like graphs and charts.
- Identifying trends, correlations, and patterns in complex datasets.
- Preparing reports and presenting results to stakeholders with actionable insights.
- Assisting in decision-making processes by providing data-driven recommendations.

Some tools commonly used by data analysts include:

1. **Spreadsheets**: Such as Microsoft Excel or Google Sheets, for data entry, manipulation, and basic analyses.

2. **SQL databases**: Understanding Structured Query Language (SQL) is essential for data analysis, as it enables analysts to extract and manipulate data stored in relational databases.

3. **Statistical Software**: Programs like R or Python (with data-focused libraries such as pandas, NumPy, and scikit-learn) are used for more in-depth analyses, including statistical testing and machine learning.

4. **Business Intelligence (BI) Tools**: Software like Tableau, Power BI, or Looker provides powerful data visualization and interactive dashboards that help communicate insights effectively.

### Project 1:

Create a functional dashboard in Google Sheets to analyze and visualize data related to bike buyers.

Step 1:- Data Acquisition
Download the provided dataset or use a dataset of your choice related to bike buyers. Ensure it contains relevant information such as customer demographics, purchase history, and product preferences.

Step 2:- Google Sheets Set-up
Open a new Google Sheets document and import the dataset into a new sheet.

Step 3 Data Exploration
Explore the dataset to understand its structure and contents. Identify key variables to provide insights into bike buyers’ behavior and preferences.

Step 4:- Dashboard Design
Plan the layout of your dashboard, deciding which key metrics and visualizations you want to include. Create separate sections for demographics, purchasing trends, and any other relevant categories.

Step 5:- Data analysis and visualization
Utilize Google Sheets features to perform data analysis. This may include creating pivot tables, charts, and graphs. Visualize key metrics such as customer age distribution, popular bike models, and purchasing patterns.

Step 6:- Interactive Elements
Enhance the dashboard with interactive elements like dropdown menus or filters to allow users to explore the data dynamically. Ensure that the dashboard is user-friendly and provides a seamless experience.

Step 7:-  Insights and Recommendation
Draw insights from your analysis and use them to make informed recommendations. For example, which bikes are most popular among certain age groups or demographics?

Step 8:- Documentation
Document the steps you took to create the dashboard. Include explanations for the design choices and any challenges faced. Create a summary of the insights gained and recommendations made.

## Content:-
Data Analytics with Excel, Function in Excel, Pivot Tables, Conditional Formatting, Charts, Data Cleaning.
## Skills:-
Data Acquisition, Google Sheets Set-Up, Data Exploration, Data Visualization.

1. Bar Chart (Marital Status):

Question: How does the count of bike purchases vary among different marital statuses? Are married individuals more likely to purchase bikes?

Ans: 
From the pivot table of two columns Marital Status and Purchased Bike, we know the count of married and single people purchasing the bikes.
There are two categories: "Married" and "Single." The counts of bike purchases are divided into two categories: "No" (indicating no bike purchase) and "Yes" (indicating a bike purchase). 
There are two categories: "Married" and "Single." The counts of bike purchases are divided into two categories: "No" (indicating no bike purchase) and "Yes" (indicating a bike purchase). 
- For married individuals: 307 individuals did not purchase a bike ("No"). 232 individuals purchased a bike ("Yes").
- For single individuals: 212 individuals did not purchase a bike ("No"). 249 individuals purchased a bike ("Yes").
- No, single individuals are more likely to buy bikes.

2. Bar Chart (Gender):

Question: Build a bar graph to compare the count of male and female customers. Does gender influence bike purchases, and if so, to what extent?

Ans: 
Count of females who purchased a bike: 239
Count of females who did not purchase a bike: 252
Total count of females: 491
For Males:
Count of males who purchased a bike: 242
Count of males who did not purchase a bike: 267
Total count of males: 509
Based on this data, there is a marginal difference in the counts of bike purchases and non-purchases between males and females.

3. Histogram (Income):
Question: What is the distribution of income among bike buyers? Are there specific income brackets that show a higher likelihood of bike purchases?

Ans:

| Income Bin | Frequency |
|------------|-----------|
| 10,000     | 74        |
| 20,000     | 77        |
| 30,000     | 134       |
| 40,000     | 153       |
| 50,000     | 40        |
| 60,000     | 166       |
| 70,000     | 123       |
| 80,000     | 91        |
| 90,000     | 38        |
| 100,000    | 29        |
| 110,000    | 16        |
| 120,000    | 17        |
| 130,000    | 32        |
| 140,000    | 0         |
| 150,000    | 4         |
| 160,000    | 3         |
| 170,000    | 3         |
| More       | 0         |

For instance, you might observe that the 60,000 bracket has a relatively high frequency. Conversely, brackets such as 140,000 and "More" have zero frequencies, indicating no buyers in those income ranges.

4. Histogram (Age):
Question: Create a histogram to understand the age distribution of bike buyers. Are certain age groups more inclined to purchase bikes?

Ans:

| Age     | Frequency |
| ------- | --------- |
| 20      | 0         |
| 25      | 5         |
| 30      | 103       |
| 35      | 146       |
| 40      | 171       |
| 45      | 157       |
| 50      | 142       |
| 55      | 104       |
| 60      | 71        |
| 65      | 51        |
| 70      | 39        |
| 75      | 7         |
| 80      | 3         |
| 85      | 0         |
| 90      | 1         |

Based on the provided age distribution data, we can observe that the highest frequency of bike buyers falls within the age group of 35 to 50. This suggests that individuals in their mid-thirties to mid-forties are more inclined to purchase bikes. Age groups below 35 and above 50 also show interest, but the frequency decreases in those ranges.

5. Box Plot (Income):
Question: Identify outliers in the income distribution of bike buyers. Are there any extreme income values, and how might they impact purchasing behavior?

Ans:
From the provided frequency distribution of income, it appears that there are no data points beyond the specified bin of 170,000.

7. Pie Chart (Region):
Question: Represent the distribution of bike purchases by region using a pie chart. Are there regions where bike purchases are notably higher?

Ans:
We can analyze the distribution of bike purchases by region using the pie chart. Let's interpret the results:
-Europe: 148 bike purchases
-North America: 220 bike purchases
-Pacific: 113 bike purchases
In the pie chart, each region's slice represents the proportion of bike purchases in that region relative to the total. Here are some observations:
North America has the highest proportion of bike purchases with 220 purchases, making it the largest slice in the pie chart.
Europe is the second-highest contributor with 148 purchases.
Pacific has the smallest slice, indicating a lower number of bike purchases compared to the other two regions.
Therefore, bike purchases are notably higher in North America, followed by Europe, while the Pacific region has a comparatively lower share.

8. Scatter Plot (Income vs. Age):
Question: Create a scatter plot to investigate the relationship between income and age. Do individuals with higher incomes tend to be in specific age groups?

Ans:
There doesn't seem to be a clear pattern or trend between income and age in your scatter plot, it suggests that there may not be a strong correlation between the two variables in your dataset. This could mean that income and age are not strongly related, or there might be other factors influencing the relationship.

9. Stacked Bar Chart (Marital Status & Gender):
Question: How does the distribution of bike purchases differ when considering both marital status and gender simultaneously? Are there notable patterns?

Ans: 
There's a higher number of single individuals in both genders.
The difference between married and single females is relatively smaller than the difference between married and single males.
These patterns suggest that marital status may have a more pronounced impact on the bike purchase decision for males compared to females.

10. Correlation Heatmap (Numeric Variables):
Question: Use a heatmap to visualize the correlation matrix between numeric variables. What variables show a strong correlation, and how might this influence purchasing behavior?

Ans:


