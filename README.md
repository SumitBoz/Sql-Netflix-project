# Netflix Movies and TV Shows Data Analysis using SQL

![Nelfix Logo](https://github.com/SumitBoz/Sql-Netflix-project/blob/main/logo.png)

# Overview
This project involves a comprehensive analysis of Netflix's movies and TV shows data using SQL. The goal is to extract valuable insights and answer various business questions based on the dataset. The following README provides a detailed account of the project's objectives, business problems, solutions, findings, and conclusions.

# Objectives
Analyze the distribution of content types (movies vs TV shows).
Identify the most common ratings for movies and TV shows.
List and analyze content based on release years, countries, and durations.
Explore and categorize content based on specific criteria and keywords.

# Schema

DROP TABLE IF EXISTS netflix;
CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);

# Business Problems Solved
📌 A few key insights uncovered from the dataset:

Count of Movies vs TV Shows

Most Common Ratings for Each Content Type

Movies Released in a Specific Year

Top 5 Countries by Content Volume

Longest Movie on the Platform

Content Added in the Last 5 Years

All Titles by a Specific Director ('Rajiv Chilaka')

TV Shows with More Than 5 Seasons

Content Count by Genre

Top Years by Average Content Release in India

Documentaries on Netflix

Titles Without a Director Listed

Salman Khan’s Appearances in the Last 10 Years

Top 10 Most Frequent Indian Actors

Categorizing Content Based on Violent Keywords

# Check out the full SQL queries in the solutions.sql file.

📊 Key Findings
Balanced Content: Movies slightly outnumber TV Shows on the platform.

Frequent Ratings: TV-14 and TV-MA are the most common ratings, suggesting a teen and adult-oriented audience.

India’s Contribution: India ranks high in content volume, with rising yearly releases.

Data Quality Issues: Many records are missing director data, and cast fields are inconsistent.

Thematic Analysis: Keyword filters allow for content classification based on descriptions (e.g., violence-related themes).

# Tech Stack
SQL (PostgreSQL)

Dataset from Kaggle

DBMS: PgAdmin / DBeaver (or your tool of choice)

# Files
solutions.sql – All SQL queries written to extract and analyze data.

README.md – Overview and documentation of the project.
This analysis provides a comprehensive view of Netflix's content and can help inform content strategy and decision-making.


