# netflix_analytics_dashboard

📌 Short Description 

This dashboard visualizes Netflix’s content data, analyzing over 7,900 shows, 4,100 directors, and 36 genres. It reveals patterns across global locations, release years, ratings, and more—empowering content strategists and decision-makers to evaluate the platform's content evolution and genre-wise popularity.

🛠 Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – For creating visually appealing and interactive dashboards

🐍 Python (Pandas) – Used for cleaning, filtering, and preparing raw Netflix data

🔍 Power Query – Used for minor transformations inside Power BI

🧠 DAX – For key measures like Total Shows, Genre Counts, Show Type Proportions

📁 Data Modeling – To connect datasets like shows, directors, and ratings

📝 .pbix File Format – Power BI’s dashboard project file

📊 Excel Dataset – Final cleaned dataset exported from Python for visualization

🗂️ Data Source
Source: Netflix Titles Dataset (internal/project-based)

Structure:

-> Show Data – Title, duration, type (TV Show or Movie), genre, country

-> Cast & Crew – Lead actors, directors

-> Timeline – Release years from 1942 to 2021

-> Ratings – MPAA-style ratings (e.g., TV-MA, PG-13)

-> Genre & Location – Categorization and geo-coverage of shows

✨ Features / Highlights
💼 Business Problem
Netflix’s large catalog requires constant monitoring to understand content spread, genre trends, and global reach. Static analysis lacks clarity over what content dominates or where gaps exist.

🎯 Goal
To offer a single-pane view of Netflix’s content library that helps:

Track total number of shows, directors, genres, and countries

Evaluate growth in release years

Understand genre and rating distribution

Compare proportion of Movies vs. TV Shows

Discover leading actors and directors

📊 Walkthrough of Key Visuals
Top KPI Cards
📺 Total Shows: 7,974

🎬 Total Directors: 4,150

🎭 Total Genres: 36

🌍 Locations: 689

📆 Release Year Range: 1942 to 2021

Visual Insights
🌎 Total Shows by Country – Map visual to explore regional show distribution

📈 Total Movies and Shows by Release Year – Trend line showing surge in releases

📊 Rating by Shows – TV-MA, TV-14 dominate show counts

🍿 Genre Breakdown – Dramas, Comedies, Action & Adventure lead the list

📺 Movies vs TV Shows – Donut chart shows 70.85% are TV Shows

🎖️ Top Director / Actor / Genre – Showcases most frequent contributors

Detailed Matrix Table
Interactive table to view:

-> Title
-> Genre
-> Lead Actor
-> Director
-> Duration
-> Release Year

🔍 Business Impact & Insights
-> Content Strategy: Understand which genres dominate to plan future productions

-> Market Coverage: Locate underserved countries or genres

-> User Retention: Tailor recommendations based on genre popularity

-> Catalog Curation: Discover potential gaps or oversaturation in content types

📁 Dashboard Preview Images:

![Netflix Dashboard 1](./Screenshot%20(34).png)  

![Netflix Dashboard 2](./Screenshot%20(35).png)  

![Netflix Dashboard 3](./Screenshot%20(36).png)  
