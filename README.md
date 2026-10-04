# Cognifyz Data Analysis Internship

A complete collection of data analysis projects completed during my Data Analysis Internship at Cognifyz Technologies.

The project focuses on exploratory data analysis, data cleaning, statistical analysis, visualization, geographical analysis, and extracting meaningful business insights from a restaurant dataset.

---

## 📌 About the Internship

During this internship, I worked on a structured set of data analysis tasks using a restaurant dataset.

The internship provided practical experience in analyzing real-world structured data, identifying patterns, comparing business metrics, creating visualizations, and communicating findings through concise insights and conclusions.

I completed:

- Level 1 – 4 Data Analysis Tasks
- Level 2 – 4 Data Analysis Tasks

The work was developed and documented using Python and Google Colab.

---

## 🎯 Project Objective

The main objective of this project was to explore restaurant-related data and derive meaningful insights from different aspects of the dataset, including:

- Cuisine preferences
- Restaurant distribution across cities
- Price ranges
- Online delivery availability
- Restaurant ratings
- Customer votes
- Cuisine combinations
- Geographic distribution
- Restaurant chains
- Customer popularity and engagement

The analysis combines numerical analysis with visual exploration to better understand restaurant trends and patterns.

---

# 📊 Level 1 – Exploratory Data Analysis

Level 1 focuses on understanding the basic characteristics of the restaurant dataset and identifying important patterns.

## Task 1 – Top Cuisines

### Objective
Identify the three most common cuisines in the dataset and calculate the percentage of restaurants serving each cuisine.

### Analysis Performed
- Cleaned and separated multiple cuisine entries.
- Counted the frequency of individual cuisines.
- Identified the top three cuisines.
- Calculated their percentage relative to the total number of restaurants.
- Created a bar chart to visualize cuisine popularity.

### Key Finding
North Indian, Chinese, and Fast Food were identified as the most common cuisines in the dataset.

### Skills Practiced
- String processing
- Pandas
- Frequency analysis
- Percentage calculation
- Data visualization

---

## Task 2 – City Analysis

### Objective
Analyze the distribution of restaurants across cities and compare their average ratings.

### Analysis Performed
- Counted the number of restaurants in each city.
- Identified the city with the highest number of restaurants.
- Calculated average restaurant ratings city-wise.
- Identified the city with the highest average rating.
- Visualized the leading cities based on average ratings.

### Key Findings
- New Delhi had the highest number of restaurants, with 5,473 restaurants.
- Inner City recorded the highest average restaurant rating at 4.90.
- The analysis showed that restaurant quantity and average rating do not necessarily move together.

### Skills Practiced
- GroupBy analysis
- Aggregation
- Sorting
- Comparative analysis
- Bar chart visualization

---

## Task 3 – Price Range Distribution

### Objective
Understand how restaurants are distributed across different price range categories and calculate the percentage represented by each category.

### Analysis Performed
- Counted restaurants in each price range.
- Calculated the percentage contribution of every price category.
- Created a bar chart showing the restaurant distribution.
- Compared lower-priced and higher-priced restaurant segments.

### Key Findings
- Price Range 1 had the highest number of restaurants with 4,444 restaurants.
- Price Range 1 represented approximately 46.53% of the dataset.
- Price Range 4 had the lowest number of restaurants with 586 restaurants.
- Higher-priced restaurants were comparatively fewer.

### Skills Practiced
- Categorical analysis
- Percentage calculation
- Pandas value counts
- Data visualization
- Business interpretation

---

## Task 4 – Online Delivery Analysis

### Objective
Determine the availability of online delivery and compare restaurant ratings based on delivery availability.

### Analysis Performed
- Counted restaurants with and without online delivery.
- Calculated the percentage distribution.
- Compared average ratings for restaurants with and without online delivery.
- Created separate visualizations for delivery availability and average ratings.

### Key Findings
- Approximately 25.66% of restaurants offered online delivery.
- Approximately 74.34% did not offer online delivery.
- Restaurants offering online delivery had a higher average rating of 3.25 compared with 2.47 for restaurants without online delivery.

### Skills Practiced
- Grouped analysis
- Percentage comparison
- Conditional comparison
- Rating analysis
- Data visualization

---

# 📈 Level 2 – Advanced Restaurant Analysis

Level 2 extends the analysis into restaurant ratings, cuisine combinations, geographical patterns, and restaurant chains.

---

## Task 1 – Restaurant Ratings

### Objective
Analyze the distribution of aggregate ratings, identify the most common rating range, and calculate the average number of votes received by restaurants.

### Analysis Performed
- Examined aggregate rating frequencies.
- Created meaningful rating ranges.
- Identified the most common rating range.
- Calculated the average number of votes per restaurant.
- Visualized both rating-range distribution and exact rating frequencies.

### Key Findings
- The 3–4 rating range represented the largest rated segment.
- A substantial number of restaurants had a rating of 0, representing restaurants without a recorded rating.
- The average number of votes was approximately 156.91 per restaurant.
- Vote counts varied considerably between restaurants.

### Skills Practiced
- Rating categorization
- Statistical analysis
- Pandas aggregation
- Distribution analysis
- Data visualization

---

## Task 2 – Cuisine Combination

### Objective
Identify common combinations of cuisines and examine whether certain cuisine combinations tend to receive higher ratings.

### Analysis Performed
- Standardized cuisine combinations.
- Focused on restaurants offering multiple cuisines.
- Identified the most frequent cuisine combinations.
- Compared average ratings across combinations.
- Applied a minimum restaurant-count threshold of 20 for more meaningful rating comparisons.
- Visualized both combination frequency and average ratings.

### Key Findings
Among combinations with at least 20 restaurants:

- Japanese, Sushi had the highest average rating of 4.06.
- Italian, Pizza followed with an average rating of 3.65.
- Other combinations generally showed moderate average ratings.

### Skills Practiced
- Data transformation
- String processing
- GroupBy aggregation
- Multi-variable comparison
- Data filtering
- Visualization

---

## Task 3 – Geographic Analysis

### Objective
Plot restaurant locations using latitude and longitude and identify geographical concentrations and patterns.

### Analysis Performed
- Selected valid latitude and longitude records.
- Identified 9,551 restaurants with valid location data.
- Created an interactive geographical map using Folium.
- Used marker clustering to handle dense restaurant locations.
- Analyzed restaurant concentration by city.
- Created a city-level comparison chart.
- Created a longitude-latitude scatter plot to visualize geographic distribution.

### Key Findings
- Restaurants were not evenly distributed geographically.
- Certain cities and areas showed considerably higher restaurant concentration.
- New Delhi had the highest restaurant concentration in the dataset.
- The geographic visualization revealed clusters of restaurant locations.

### Skills Practiced
- Geographic data analysis
- Latitude and longitude handling
- Folium
- Marker clustering
- Scatter plot visualization
- Location-based pattern identification

---

## Task 4 – Restaurant Chains

### Objective
Identify restaurant chains in the dataset and compare their outlet presence, ratings, and popularity.

### Analysis Performed
- Identified restaurant names appearing across multiple records.
- Treated repeated restaurant names as potential restaurant chains.
- Calculated outlet counts.
- Calculated average ratings.
- Calculated total customer votes.
- Calculated average votes per outlet.
- Compared chains using multiple visualizations.
- Identified highly rated and widely represented chains.

### Analysis Dimensions

The restaurant chains were compared using:

- Number of outlets
- Average rating
- Total votes
- Average votes

This helped distinguish between restaurant chains with a wider presence and those showing stronger customer engagement or ratings.

### Skills Practiced
- Frequency analysis
- GroupBy aggregation
- Multi-metric comparison
- Popularity analysis
- Rating analysis
- Business interpretation
- Data visualization

---

# 🛠️ Tools & Technologies

### Programming & Analysis
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn
- Folium

### Development Environment
- Google Colab
- Jupyter Notebook

### Analytical Techniques
- Data cleaning
- Exploratory Data Analysis (EDA)
- Data aggregation
- GroupBy analysis
- Frequency analysis
- Percentage calculations
- Rating comparison
- Geographic analysis
- Categorical analysis
- Data visualization
- Business insight generation

---

# 🧠 Skills Developed

Through these projects, I gained practical experience in:

### Data Analysis
- Understanding structured datasets
- Cleaning and preparing data for analysis
- Handling categorical and numerical variables
- Finding patterns and trends

### Python & Pandas
- DataFrame manipulation
- Filtering and sorting
- `value_counts()`
- `groupby()`
- Aggregation functions
- String processing
- Creating derived analytical columns

### Data Visualization
- Bar charts
- Horizontal bar charts
- Rating distribution plots
- Scatter plots
- Geographic maps
- Clustered location visualization

### Business Analytics
- Comparing restaurant performance
- Identifying customer preferences
- Understanding price segmentation
- Comparing ratings and popularity
- Interpreting geographical concentration
- Converting analytical results into business insights

### Analytical Thinking
- Selecting appropriate metrics
- Comparing different categories
- Using thresholds for meaningful comparisons
- Identifying patterns instead of relying only on raw numbers
- Communicating findings through concise conclusions

---

# 📁 Repository Structure

```text
Cognifyz-Data-Analysis-Internship/
│
├── Level 1/
│   └── Cognifyz_Data_Analysis_Level_1.ipynb
│
├── Level 2/
│   └── Cognifyz_Data_Analysis_Level_2.ipynb
│
└── README.md
