# car-market-analysis
A Competitive Analysis of the Entry-Level Luxury Car Market

## Objective
This project was completed as part of the Unstructured Data Analysis coursework, for the MS in Business Analytics program at the McCombs School of Business. 
It attempts to analyze the entry-level luxury car market in the USA by utilizing content from Edmunds.com discussion forums. The goal is to extract insights from user discussions to advise the 'client', JD Power and Associates, on brand positioning, consumer preferences, and the competitive landscape.

## Key Tasks
Data Scraping: A Python web scraper was developed to extract around 5000 posts from the "Entry Level Luxury Performance Sedans" forum on Edmunds.com. The output is stored in a CSV file with two columns: date and message.

## Data Analysis

*Zipf's Law:* Tested Zipf’s law econometrically to observe the frequency distribution of words, plotting the top 100 most frequent words.

*Brand Frequency Counts:* Extracted the top 10 car brands based on word frequency counts, replacing specific car models with their respective brands.

*Lift Calculation:* Calculated the lift ratios for associations between the top-10 brands, ensuring brands mentioned multiple times in a post were only counted once.

*Multi-Dimensional Scaling (MDS):* Visualized the relationships between brands using MDS to uncover proximity and clustering.

*Attribute Identification:* Identified the top 5 most frequently mentioned car features/attributes and analyzed the association between these features and the brands.

*Aspirational Brand Analysis:* Determined the most aspirational brand by analyzing consumer discussions about brand desire and purchasing intent.

## Insights & Recommendations

Provided insights based on lift calculations and MDS analysis to help JD Power understand brand associations.
Offered recommendations on product attributes and brand positioning in the luxury car market.
Identified key features that are strongly associated with top brands, providing strategic advice for brand marketing and development.

## Files Included

*analysis.ipynb:* A single Python notebook containing all the data analysis, including the scraper code, Zipf’s law test, brand frequency counts, lift ratio calculations, MDS mapping, and feature analysis.

*edmunds_forum_posts.csv:* The CSV file containing the scraped posts from the Edmunds forum.

*car_models_and_brands_v1.csv:* A CSV file containing the list of car models and brands used for data cleaning.

## Conclusion

This project provides actionable insights into the competitive landscape of entry-level luxury cars, guiding JD Power in understanding brand perceptions, consumer desires, and key product features that drive discussions.
