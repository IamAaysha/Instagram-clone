# Instagram Clone - SQL Database

## Overview
This project replicates the core functionalities of Instagram using SQL. It includes database schema creation and various queries to analyze user engagement, activity, and trends. The project demonstrates SQL skills in data modeling, relationships, and querying for insights.

## Features
- **User Management:** Tracks users and their registration dates.
- **Photo Uploads:** Stores images uploaded by users.
- **Comments & Likes:** Allows users to engage with posts through comments and likes.
- **Follow System:** Enables users to follow each other.
- **Hashtags:** Supports tagging photos with hashtags for better content discovery.
- **Data Analysis Queries:** Includes queries for finding top users, inactive users, most popular posts, and detecting bot activity.

## Database Schema
The database consists of the following tables:

- **users**: Stores user information (ID, username, registration date).
- **photos**: Stores photos uploaded by users with timestamps.
- **comments**: Tracks comments on photos.
- **likes**: Records likes given to photos.
- **follows**: Manages the follow relationships between users.
- **tags**: Stores hashtags used in photos.
- **photo_tags**: Junction table mapping photos to tags.

## Key SQL Queries
The project includes various SQL queries to extract insights:

1. **Oldest Users:** Identifies the five longest-registered users.
2. **Registration Trends:** Determines the most common day for user registrations.
3. **Inactive Users:** Finds users who have never posted a photo.
4. **Most Liked Photo:** Identifies the photo with the highest likes.
5. **User Engagement:** Calculates the average number of posts per user.
6. **Top Hashtags:** Retrieves the most frequently used hashtags.
7. **Bot Detection:** Identifies users who like every photo.
8. **Celebrity Accounts:** Finds users who have never commented on a photo.
9. **User Rankings:** Ranks users based on the number of posts.
10. **Community Insights:** Computes the percentage of users who never commented or liked every photo.

## How to Use
1. Run the SQL scripts to create the database schema.
2. Insert sample data (if required).
3. Execute the provided queries to analyze user activity and engagement.

## Technologies Used
- SQL (Standard Query Language)

## Future Improvements
- Implement additional analytics for engagement metrics.
- Enhance follow recommendations based on user interactions.
- Add support for private accounts and direct messages.

This project showcases database design and querying techniques, providing a strong foundation for social media analytics. 🚀
