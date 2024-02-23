# Data Science Job Market Analysis

## Unlock Insights from Glassdoor Job Data with Python

Welcome to the Glassdoor Data Science Job Analysis repository! This project empowers you to delve into the realm of data science job opportunities by seamlessly scraping, cleaning, and analyzing data from Glassdoor. 

## Table of Contents

- [Project Background](#project-background)
- [Objectives](#objectives)
- [Data Cleaning and Processing](#data-cleaning-and-processing)
- [Key Insights for Action](#key-insights-for-action)

## Project Background

The Data Science Job Market Analysis project is designed to provide actionable insights into the current landscape of Data Science job postings. Leveraging Glassdoor data, this analysis zooms in on practical details such as salary estimates, company sizes, and geographical distribution. The goal is to equip professionals with valuable, actionable information for informed decision-making in the dynamic field of Data Science.

## Objectives

The project aims to deliver actionable insights by:
- Analyzing salary estimates to help professionals negotiate competitive compensation.
- Examining company sizes to guide job seekers in aligning with their preferred work environments.
- Exploring geographical distribution to inform relocation or remote work considerations.

## Data Cleaning and Processing

### Title Consolidation

To ensure meaningful analysis, the dataset's 172 unique titles were consolidated. Titles occurring less than five times were grouped into broader categories, simplifying job market understanding.

### Salary Estimation Conversion

Transforming the 'Salary Estimation' column from an object to an integer enables professionals to better gauge earning potential and market value.

### Title Grouping

Similar titles with less than five occurrences were grouped under common titles for a more insightful analysis of job trends.

### Skill Focus

Highlighting the importance of Python and SQL skills guides aspiring Data Scientists in developing the most impactful competencies.

## Key Insights for Action

1. **Salary Negotiation Strategies:**
   - Data Analysts should be aware of a comparatively lower salary range. Negotiation emphasis should be on additional benefits or growth opportunities.
   - Professionals considering Senior Data Engineer roles should cautiously evaluate compensation, considering potential limitations in the dataset.

2. **Strategic Career Moves:**
   - The Data Manager position stands out with a significantly higher salary. Job seekers may find it valuable to explore opportunities in this role for enhanced financial rewards.

3. **Rating Column Cleanup:**
   - Identifying and addressing negative values in the 'Rating' column ensures accurate assessments of potential employers. Prospective employees should prioritize companies with positive ratings.


