# Maratova Akbota Data Engineer group
NYC Mobility, Air Quality & Economic Analytics (Microsoft Fabric)

## Overview
This project demonstrates an end-to-end analytics pipeline built on Microsoft Fabric.
It integrates mobility, environmental, and economic data to analyze relationships between
urban traffic, air quality, and macroeconomic context

## Data Sources
- NYC Taxi & Limousine Commission (TLC) – trip-level data (Parquet)
- OpenAQ – air quality measurements (PM2.5, Temperature)
- World Bank – GDP (USD)
- ECB – USD/EUR exchange rates

## Architecture
- Bronze: raw data ingestion into OneLake
- Silver: cleaned, standardized, enriched datasets
- Gold: star schema + analytical fact tables

## Technologies
- Microsoft Fabric
- PySpark & Pandas
- Delta Lake
- Power BI

## Notes
Fabric workspace itself is not publicly shareable.
This repository contains all transformation and analytics code used in the project.
