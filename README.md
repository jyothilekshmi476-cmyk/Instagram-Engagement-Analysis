# Instagram Engagement Analysis Using Power BI

## Project Description
• This project analyzes Instagram user engagement using Power BI.  
• It focuses on likes, comments, shares, and posts.  
• The goal is to identify which city has the highest interaction and understand engagement patterns.

## Problem Statement
• To analyze Instagram engagement data.  
• To identify which city generates the highest number of likes, comments, and shares.  
• To compare engagement performance across different cities.

## Dataset Overview
• Source: Kaggle  
• Number of Rows: 10,001  
• Number of Columns: 8  

### Key Columns
• User ID – Unique number of each user  
• City – Location of the user  
• Post Type – Type of content (Reel, Image, Carousel)  
• Posts Count – Total posts made by the user  
• Likes – Total number of likes received  
• Comments – Total number of comments received  
• Shares – Total number of times the post was shared  
• Date Time – Date and time when the post was published  

## Methodology

### 1. Data Preparation
• Converted Date Time from Whole Number to Date/Time  
• Checked dataset for null values  

### 2. New Columns Created
• Time Slot – Morning, Afternoon, Evening, Night  
• Total Interactions – Likes + Shares + Comments  
• Interaction Level – High, Medium, Low  

### 3. Measures
• Total Likes = SUM(Likes)  
• Total Shares = SUM(Shares)  
• Total Comments = SUM(Comments)  

## Visualizations
• Clustered Bar Chart – Likes by City  
• Column Chart – Post Count by City  
• Stacked Column Chart – Comments by City  
• Pie Chart – Shares by City  
• Line Chart – Post Count by Year  
• Donut Chart – Average Comments by City  

## Tools Used
• Power BI  
• Kaggle Dataset  

## Conclusion
• The project identifies the city with the highest Instagram engagement.  
• It analyzes posts, likes, comments, and shares to understand user interaction patterns.

## Recommendations
• Create more engaging and creative posts.  
• Use polls, questions, and contests to increase engagement.  
• Collaborate with influencers.  
• Post content during peak activity hours.
