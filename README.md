#  Movie Analytics CTE Project

##  Overview
This project is designed to help you **master Common Table Expressions (CTEs)** in SQL using a practical, real-world dataset.  
You’ll work with a **movie analytics database** that includes tables for movies, genres, actors, users, ratings, and movie casts.



---

##  Database Schema

**Database Name:** `movie_cte_db`

| Table | Description |
|--------|--------------|
| `genres` | Stores all movie genres |
| `movies` | Contains movie titles, release year, and genre_id |
| `actors` | Contains actor names and countries |
| `movie_cast` | Relationship between movies and actors |
| `users` | Contains user details |
| `ratings` | Contains movie ratings given by users |

---

## Learning Objectives
- By completing this project, you will:
- Understand CTE syntax and structure
- Replace subqueries with clean CTE-based logic
- Use CTEs with joins, aggregations, and window functions
- Build multi-step CTEs for layered data analysis
- Practice recursive CTEs for sequence generation

-----

## 15 CTE Practice Query Questions

| #       | Question                                                       | Concept              |
| ------- | -------------------------------------------------------------- | -------------------- |
| **Q1**  | Create a CTE to list all movies released after 2015.           | Basic CTE filter     |
| **Q2**  | Use a CTE to calculate average rating per movie.               | Aggregate CTE        |
| **Q3**  | Find the top 3 highest-rated movies using a CTE.               | Ranking              |
| **Q4**  | List movies whose average rating is above the overall average. | Nested CTE           |


----
## Recommended Learning Path
- Start with basic CTE queries (Q1–Q5)
- Move to aggregations and joins (Q6–Q10)
- Finish with advanced and recursive CTEs (Q11–Q15)
-----

##  Setup Instructions

1. **Create the database**
   ```sql
   CREATE DATABASE movie_cte_db;
   USE movie_cte_db;


## Analysis

The documentation of the data analysis process is included in the file (movie_cte_db)[https://github.com/data-engineer-yogesh/movie_cte/blob/main/movie_cte_db.sql]

## Summary

The project was done for the purpose of practice and to improve skills in SQL.

