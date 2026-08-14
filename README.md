# Music Store Data Analysis Using PostgreSQL

## Project Overview

This project analyzes a digital music store database using PostgreSQL to understand customer spending, sales performance, music preferences, popular genres, artists, and geographic purchasing patterns.

The analysis uses multiple related tables and SQL techniques to answer business-oriented questions about customers, invoices, tracks, artists, and genres.

## Database

The project uses PostgreSQL with the database:

`music_database`

The analysis uses the following tables:

- `album`
- `artist`
- `customer`
- `employee`
- `genre`
- `invoice`
- `invoice_line`
- `media_type`
- `playlist`
- `playlist_track`
- `track`

## Business Questions

- Who is the senior-most employee based on job level?
- Which countries have the most invoices?
- What are the top 3 invoice values?
- Which city generates the highest total invoice revenue?
- Who is the best customer based on total spending?
- Who are the Rock music listeners?
- Which artists have created the most Rock tracks?
- Which tracks are longer than the average song length?
- Which customers spent the most on the best-selling artist?
- What is the most popular music genre in each country?
- Who is the highest-spending customer in each country?

## Analysis Performed

### Employee Analysis

Identified the senior-most employee based on the highest job level.

### Invoice Analysis

- Counted invoices by country
- Identified the top 3 invoice values
- Identified the city generating the highest total invoice revenue

### Customer Analysis

- Identified the customer with the highest total spending
- Analyzed customer spending by country
- Identified the highest-spending customer in each country

### Music Preference Analysis

- Identified customers who listen to Rock music
- Identified the top 10 Rock artists based on the number of tracks
- Identified tracks longer than the average song length
- Determined the most popular genre in each country

### Artist & Sales Analysis

- Identified the best-selling artist based on total sales
- Analyzed how much customers spent on the best-selling artist
- Connected customer, invoice, track, album, and artist data to calculate artist-level spending

## SQL Concepts Used

- `SELECT`
- `JOIN`
- `WHERE`
- `GROUP BY`
- `ORDER BY`
- `LIMIT`
- `COUNT()`
- `SUM()`
- `AVG()`
- `DISTINCT`
- `LIKE`
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- `ROW_NUMBER()`
- `PARTITION BY`
- Aggregate Functions

## Key Skills Demonstrated

- PostgreSQL Data Analysis
- Relational Database Analysis
- Multi-Table Joins
- Customer Analysis
- Sales Analysis
- Revenue Analysis
- Music Preference Analysis
- Geographic Analysis
- Ranking Analysis
- Window Functions
- Business-Oriented Data Analysis

## Project Files

- `music ps.sql` — PostgreSQL queries used for the complete music store analysis
- `music store data.zip` — Dataset used for the analysis

## Project Structure

```text
music-store-sql-analysis/
│
├── README.md
├── music ps.sql
└── music store data.zip
