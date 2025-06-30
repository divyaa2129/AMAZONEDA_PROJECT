# AMAZONEDA_PROJECT
<h2>Project Overview</h2>

This project analyzes Amazon Prime's content library using a dataset amazon_prime_titles. The goal is to explore trends in genres, directors/actors, country representation, and content addition patterns.

<h2>Dataset Used</h2>

File: amazon_prime_titles.csv

Source: Kaggle

<h2>Key Questions Explored</h2>
 
Most Common Genres – What genres dominate Amazon Prime’s library?

Directors/Actors with Widest Genre Diversity – Who has worked across the most genres?

Countries Represented – How many unique countries produce content?

Top 20 Content-Producing Countries – Which countries contribute the most titles?

Monthly Content Addition Trends – Are there peak months for new uploads?

<h2>Analysis & Visualizations</h2>

1. Most Common Genres

Top Genres: Drama, Comedy, Documentary, Action, Horror.

Visualization: Horizontal bar plot (seaborn).

2. Directors/Actors with Genre Diversity

Method: Group by director/actor and count unique genres.

Findings: Some directors/actors span 10+ genres.

Visualization: Bar plots for top 10 directors and actors.


3. Countries Represented
   
Method: Split country (some entries list multiple countries) and count unique values.

Result: 85+ countries represented.


4. Top 20 Content-Producing Countries
   
Method: Count titles per country.

Top Countries: US, India, UK, Canada, Japan.

Visualization: Horizontal bar chart.


5. Monthly Content Additions
   
Method: Extract month from date_added and count uploads.

Trend: Peaks in December (holiday season) and mid-year.

Visualization: Monthly bar plot.


<h2>Key Insights</h2>
Drama & Comedy dominate Amazon Prime’s library.

US, India, UK are the top content-producing countries.

December sees the highest number of new uploads.

Some directors/actors work across 10+ genres, showing versatility.



