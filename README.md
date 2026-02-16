[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/onHdUoTH)
# Exploratory Data Analysis with Pandas

## Introduction

This assignment introduces Exploratory Data Analysis (EDA) using Pandas. You will load a real-world dataset, inspect its structure, and answer questions by filtering, grouping, and summarizing data.

## Dataset

The dataset is the [Adult Census Income dataset](https://archive.ics.uci.edu/ml/datasets/Adult). It contains demographic information (age, workclass, education, marital status, etc.) and a target column `salary` indicating whether an individual earns `<=50K` or `>50K` per year.

## Part 1: Basics

1. How many rows and columns does the dataset have?
2. What are the column names and data types?
3. How many men and women are in the dataset?
4. What is the average age of women?
5. What percentage of people are from the United States?
6. What is the average age of people who earn >50K vs. <=50K?
7. What are the top 5 most common occupations?
8. What is the maximum hours-per-week, and how many people work that many hours?
9. Display age statistics grouped by race and sex. What is the max age of men in the Amer-Indian-Eskimo group?
10. What is the average hours-per-week for each salary group?

## Part 2: Groupby and Aggregation

11. For each workclass, compute mean age, mean hours-per-week, and count. Sort by count descending.
12. For each education level, compute min, max, and mean of hours-per-week. Sort by mean descending.
13. Create a crosstab of education vs. salary. Which education level has the highest proportion of >50K earners?
14. Among people working >40 hours/week, what is the average capital-gain by occupation? (Top 5)

## Bonus (Extra Difficult)

15. Bin ages into groups (17-30, 31-45, 46-60, 61+). For each age group and sex, compute: percentage earning >50K, average hours-per-week, and most common occupation.
