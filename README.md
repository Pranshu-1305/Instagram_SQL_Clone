# Instagram_SQL_Clone
SQL-based Instagram clone project featuring a normalized database schema, data insertion, and analytical queries to uncover user insights, content trends, and suspicious activity.
**Project Overview**
This project is a scaled-down simulation of Instagram built using SQL. It manages users, photos, likes, comments, follows, and hashtags while enabling powerful analytical queries. The goal is to demonstrate how structured data and pure SQL can be used to analyze user behavior, detect anomalies, and extract business insights.

The system is developed using MySQL and tested on MySQL Workbench.

🎯**Objective**
Design a normalized relational database for a social media platform.

Ensure referential integrity with constraints and relationships.

Insert synthetic data to simulate real-world activity.

Perform advanced analytical SQL queries for engagement and trends.

Detect anomalies (e.g., bots) based on suspicious activity.

Gain actionable insights for content strategy and user growth.

🛠️ **Key Features**

👤 Manage users and their accounts.

📸 Store and track photo uploads.

❤️ Manage likes and detect top-performing content.

💬 Handle comments and user interactions.

🔗 Manage follower/followee relationships.

🏷️ Store and analyze hashtags with photo-tag relationships.

🤖 Detect bots/users with abnormal like patterns.

📊 Generate insights on engagement, trends, and user behavior.

🧱 **Technologies Used**

MySQL (v8+) – Relational Database

MySQL Workbench – GUI for schema design and queries

📂 **Project Structure**
Section	Description
Tables Creation	users, photos, likes, comments, follows, tags, photo_tags
Constraints	Primary & foreign keys for data integrity
Sample Data	Insert statements for users, photos, likes, follows, etc.
CRUD Operations	Insert, update, delete, select queries
Analytical Queries	Advanced SQL queries for insights
Results	Outputs of each task (oldest users, top hashtags, bots, etc.)
📊 **Insights Generated**

Oldest Users → Identified 5 most loyal users.

Inactive Users → Found users with zero uploads.

Top Performing Photo → Most liked content revealed.

Top Hashtags → Discovered trending topics.

Registration Patterns → Detected most popular signup day.

Average Engagement → Posts per user and total activity.

Bot Detection → Spotted users liking all photos (suspicious).

📌 **Conclusion**

This project demonstrates the power of SQL beyond simple data storage. By designing a relational schema and writing analytical queries, we can uncover meaningful insights, detect anomalies, and guide business strategies for a social media platform.

**Key Learnings**:

Database normalization and schema design.

Using joins, subqueries, and aggregations effectively.

Writing queries for trend analysis and anomaly detection.

Building SQL-only workflows for business intelligence.

🚀 **How to Run**

Clone or download this repository.

Open MySQL Workbench (or any MySQL IDE).

Execute the scripts sequentially:

Create database & tables

Insert sample data

Run analytical queries

Review insights from result sets.

📚 Thank you for exploring this project! Happy Querying! 🚀
