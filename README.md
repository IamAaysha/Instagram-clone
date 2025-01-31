# Instagram Clone - SQL Project

## Project Overview
This project replicates the backend database structure of an Instagram-like social media platform using MySQL. The database is designed to store users, photos, comments, likes, follows, and tags, allowing for comprehensive social media interactions and analysis.

## Database Schema
The project includes the following tables:

- **Users**: Stores user information such as username and account creation date.
- **Photos**: Stores uploaded photos along with their respective users.
- **Comments**: Stores comments made by users on photos.
- **Likes**: Stores user likes on photos.
- **Follows**: Tracks user relationships (who follows whom).
- **Tags**: Stores hashtags used in photo descriptions.
- **Photo_Tags**: A junction table connecting photos and tags.

## Queries Implemented
The project includes a variety of SQL queries that help analyze user activity and platform engagement, such as:

- **User Engagement**
  - Find the 5 oldest users.
  - Determine the most common day for user registrations.
  - Identify inactive users who have never posted a photo.
  
- **Content Interaction**
  - Identify the user with the most-liked photo.
  - Calculate the average number of posts per user.
  - Rank users based on their number of posts.
  
- **Community Trends**
  - Find the most commonly used hashtags.
  - Identify users who have liked every photo (potential bots).
  - Identify users who have never commented on a photo.

- **Platform Insights**
  - Calculate the percentage of users who have either never commented or commented on every photo.
  - Determine the number of users who have posted at least once.
  
## Technologies Used
- MySQL for database creation and querying
- SQL Joins, Aggregation Functions, and Subqueries for data analysis

## Future Enhancements
- Implement stored procedures for automated reporting.
- Introduce triggers to manage data consistency.
- Optimize query performance with indexing.

This project serves as a foundational example of database design and analytics in a social media context. Feel free to explore and expand upon it!

