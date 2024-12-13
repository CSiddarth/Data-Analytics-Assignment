# Data-Analytics-Assignment

**Overview**

This project analyzes datasets related to user behavior, cooking preferences, and order trends. The main goal is to derive insights and provide actionable recommendations for business strategy improvements.

**Objectives**

Clean and merge datasets: UserDetails, CookingSessions, and OrderDetails.
Analyze relationships between cooking sessions and user orders.
Identify popular dishes and their trends.
Explore demographic factors influencing user behavior.
Visualize insights and summarize findings in a report.

**Folder Structure:**

DataAnalyticsAssignment/
├── Data/
│   ├── UserDetails.csv          # Raw User Details Dataset
│   ├── CookingSessions.csv      # Raw Cooking Sessions Dataset
│   ├── OrderDetails.csv         # Raw Order Details Dataset
│   ├── MergedDataset.csv        # Final Cleaned and Merged Dataset
├── Notebooks/
│   └── analysis.ipynb           # Jupyter notebook for data analysis
├── Report/
│   └── Final_Report.pdf         # Final report summarizing findings
├── Visualizations/
│   └── plots/                   # Contains generated visualization images
├── README.md                    # This file

**Datasets**

**UserDetails**

Description: Contains user demographic information, registration details, and favorite meal preferences.
Key Columns: User ID, Age, Location, Favorite Meal, Total Orders.

**CookingSessions**

Description: Logs of cooking sessions with dish names, durations, and ratings.
Key Columns: Session ID, User ID, Dish Name, Meal Type, Session Rating, Duration (mins).

**OrderDetails**

Description: Records of user orders including dish names, amounts, and statuses.
Key Columns: Order ID, User ID, Dish Name, Order Date, Amount (USD), Rating.

**MergedDataset**

Description: Final dataset combining user demographics, cooking sessions, and order details.
Key Columns: All key columns from the datasets above.

**Visualizations**

The project includes the following key visualizations:

Top 10 Popular Dishes: Displays the most frequently ordered dishes.
Distribution of Orders per Cooking Session: Analyzes the relationship between sessions and order frequency.
Orders by Location: Highlights geographic trends in order volumes.
Orders by Age: Explores the age distribution of orders.
Meal Type Preferences: Shows the percentage breakdown of meal types (Breakfast, Lunch, Dinner).
Visualizations are saved in the Visualizations/plots/ directory.

**How to Run**

Clone the repository:

git clone <repository_url>
cd DataAnalyticsAssignment

Install required libraries:

pip install -r requirements.txt

Open the Jupyter Notebook:

jupyter notebook Notebooks/analysis.ipynb

Run the notebook to generate the merged dataset and visualizations.

**Key Insights**

- Popular Dishes: Spaghetti, Grilled Chicken, and Caesar Salad are the top 3 ordered dishes.
- Order Conversion: Cooking sessions with higher ratings lead to more completed orders.

**Demographics:**

- Cities like Chicago, Los Angeles, and New York dominate order volumes.
- Users aged 25-35 are the most active group.
- Meal Preferences: Dinner accounts for 50% of all orders.

**Recommendations**

- Offer discounts on high-demand dishes during peak times.
- Target marketing campaigns in major cities and the 25-35 age demographic.
- Expand breakfast offerings to capture the morning market.
- Incentivize feedback for higher session ratings.

