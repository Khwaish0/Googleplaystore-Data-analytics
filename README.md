# Googleplaystore-Data-analytics
📌 Project Overview
This project focuses on analyzing and visualizing real-time Google Play Store data using Python, Pandas, NumPy, and Matplotlib/Seaborn. The project aims to provide insights into app reviews, sentiment distribution, and rating trends through various data visualizations.

The dataset used includes app categories, ratings, reviews, install counts, and last update timestamps, allowing us to extract meaningful insights.

🚀 Internship Task Breakdown
1️⃣ Task 1: Sentiment Distribution Visualization
🔹 Goal: Visualize the distribution of positive, neutral, and negative sentiment for user reviews, segmented by app rating groups.
🔹 Key Features:

Use a stacked bar chart to compare sentiment across different rating groups (1-2⭐, 3-4⭐, 4-5⭐).

Filter apps with more than 1,000 reviews.

Consider only the top 5 categories by app count.

2️⃣ Task 2: Average Rating & Total Review Comparison
🔹 Goal: Compare the average rating and total review count for the top 10 app categories.
🔹 Key Features:

Use a grouped bar chart to display the average rating (blue) and total reviews (red).

Only include categories where:
✅ Average rating is ≥ 4.0
✅ App size is at least 10 MB
✅ Last updated in January

Time-based condition: The graph should only be displayed between 3 PM - 5 PM IST.

3️⃣ Task 3: Rating Distribution Using Violin Plot
🔹 Goal: Show the distribution of app ratings for each category using a violin plot.
🔹 Key Features:

Only include categories with:
✅ More than 50 apps
✅ App names containing the letter “C”
✅ Excluded apps with <10 reviews or rating ≥ 4.0

Time-based condition: The graph should only be displayed between 4 PM - 6 PM IST.
