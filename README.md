# Spotify-Analysis-SQL-Project

## Project Overview

This project analyzes music streaming and engagement data from Spotify and YouTube using SQL to understand song popularity, artist performance, and cross-platform user engagement. The analysis focuses on identifying trends that drive streams, views, and audience interaction.

## Objectives
Compare engagement metrics between Spotify and YouTube

Identify top-performing tracks and artists

Analyze cross-platform popularity trends

Support data-driven music marketing insights

## Tools & Technologies

SQL (MySQL / PostgreSQL / SQLite)

Relational Database

CSV Dataset

## Analysis Performed

Top streamed tracks on Spotify

Most viewed and liked songs on YouTube

Artist-wise performance comparison

Cross-platform engagement analysis

Release year vs popularity trends

## Key Analytical Questions
🧠 Advanced Technical Highlights

This project demonstrates advanced SQL proficiency through:

Use of Window Functions (ROW_NUMBER(), RANK(), SUM() OVER, AVG() OVER)

Common Table Expressions (CTEs) using WITH clauses

Multi-level aggregations and performance-based ranking

Analytical comparisons across streaming platforms

🟢 Beginner-Level Analysis

Identify all tracks that have crossed one billion Spotify streams.

Retrieve a list of albums and their corresponding artists.

Calculate the total number of user comments for tracks marked as licensed content.

Extract all tracks released as singles.

Determine the number of tracks released by each artist.

🟡 Intermediate-Level Analysis

Compute the average danceability score per album.

Identify the top 5 tracks with the highest combined energy and liveness scores.

Display tracks that have an official music video, along with their total views and likes.

Calculate the total YouTube views per album.

Find tracks that perform better on Spotify than on YouTube based on stream counts.

🔴 Advanced-Level Analysis

Rank the top 3 most-viewed tracks per artist using window functions.

Identify tracks with a liveness score higher than the overall average.

Using a CTE, calculate the energy range (max − min) for tracks within each album.

Detect tracks where the energy-to-liveness ratio exceeds a defined performance threshold.

Compute the cumulative number of likes, ordered by total views, using window functions.
