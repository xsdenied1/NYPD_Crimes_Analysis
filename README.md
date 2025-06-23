# NYPD Crime Analysis

## Introduction

This project presents an in-depth exploration and analysis of the New York Police Department (NYPD) crime report dataset, which includes all valid felony, misdemeanor, and violation offenses reported across New York City from 2006 to 2022. The dataset comprises approximately 8 million reported incidents and is publicly accessible via the NYC Open Data portal.

## Objective

The primary objective of this project is to extract meaningful insights from the dataset using a combination of analytical techniques. All analysis is conducted in a Python-based Colab notebook, with SQL queries used to retrieve data from the underlying database.

## Analysis Overview

The analysis is structured into five key sections, each aimed at answering important questions about the nature and trends of crime in New York City:

### 1. Composition of crimes

* The total number of reported crimes in the dataset.
* Breakdown reported crimes among felony, misdemeanor, and violation.
* The top-10 most reported crimes among felonies.

### 2. Temporal trends in crime

* Total number of all reported crimes per year
* Total number of all reported crimes per month

### 3. Focus on major felonies

* Reporting the number of these crimes over time by felony type

### 4. Major felonies by hour of day

- Breakdown of major felonies by hour of the day
- Normalized hourly trend of major felonies for easier comparison

### 5. Spatial analysis

- Where in New York City are these crimes taking place?
- A density map is used to visualize the geographic concentration of each major felony.
