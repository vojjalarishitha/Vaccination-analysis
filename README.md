# Vaccination-analysis
Relational database design and advanced SQL analysis of global COVID-19 vaccination records
# Vaccination Records Database & SQL Analysis

## Overview
Designed and queried a normalised relational database of global COVID-19 vaccination records. The project covers database schema design, data cleaning, and advanced SQL querying to extract meaningful trends across countries and vaccine manufacturers.

## Files
- `Database.txt` — Full SQL schema defining 9 normalised tables with primary/foreign keys and junction tables
- `Queries.txt` — SQL queries using window functions and conditional aggregation for vaccination trend analysis

## Database Schema
9 tables covering:
- Countries and data sources
- Vaccines and manufacturers
- Age group vaccination rates
- Time-series vaccination records by country and state

## SQL Queries
**Query 1 — Daily Vaccinations by Vaccine Type**
Used LAG() window function with PARTITION BY to calculate daily vaccination counts from cumulative totals, broken down by country and manufacturer up to December 2021.

**Query 2 — Weekly Vaccination Progress Across 6 Countries**
Used CASE/MAX/MIN conditional aggregation with multi-table joins to compare weekly fully-vaccinated counts across China, Chile, United States, New Zealand, Sweden and Sri Lanka for 2021-2022.

## Tools & Technologies
SQL | SQLite | Window Functions | Relational Database Design | Data Cleaning
