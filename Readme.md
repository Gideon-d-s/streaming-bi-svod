# Streaming Platform Strategy Analysis: The Prime Video Content Playbook
## Project Overview
The streaming video-on-demand (SVOD) market has evolved into a highly saturated and fiercely competitive landscape. As platforms battle for subscriber watch-time, distinct content strategies have emerged—ranging from tightly curated, franchise-driven catalogs to massive, broad-appeal aggregators. This project analyzes the content libraries of major streaming platforms (Prime Video, Netflix, Hulu, and Disney+) using publicly available datasets to reverse-engineer their strategic content identities.

## Objective
The primary objective of this analysis is to evaluate Amazon Prime Video's competitive positioning within the broader streaming industry. By analyzing content volume, genre distribution, critical reception, and target demographics, this project aims to identify Prime Video's core strengths and vulnerabilities, ultimately providing data-driven strategic recommendations to improve subscriber retention and platform engagement.

## Dataset
This analysis utilizes the "Movies and TV Shows on Streaming Platforms" dataset (commonly found on Kaggle).
Key features analyzed include:

## Content Attributes: 
Title, Type (Movie vs. TV Show), Release Year, and Genre.

## Target Demographics: 
Age ratings (e.g., 7+, 13+, 16+, 18+, ALL).

## Platform Availability: 
Boolean flags indicating presence on Prime Video, Netflix, Hulu, and Disney+.

## Quality Metrics: 
Aggregated critical scores from Rotten Tomatoes.

## Methodology
The project follows a standard data analytics workflow to extract actionable insights:
1) Data Cleaning & Preprocessing: Handling missing values, standardizing genre tags, formatting release years, and normalizing Rotten Tomatoes scores for accurate cross-platform comparison.
2) Exploratory Data Analysis (EDA): Investigating the distribution of content types, age ratings, and historical release trends to establish baseline platform profiles.
3) Platform Comparison: Benchmarking Prime Video against its top three competitors to identify "content gaps" and strategic overlaps.
4) Strategic Recommendation: Translating data visualizations into a SWOT analysis and actionable business strategies using Porter's Five Forces framework.

## Key Findings
Our analysis revealed distinct platform identities, with a specific focus on Prime Video's unique positioning:
1) Prime Video operates on a sheer volume strategy, boasting over 4,000 movies and significantly outpacing Netflix, Hulu, and Disney+ in total library size.
2) Prime Video aggressively targets adult demographics, showing an exponential surge in 18+ content over the last decade that completely dwarfs its competitors.
3) Despite Disney+'s dominance in family branding, Prime Video actually outpaces all competitors in the sheer volume of youth and teen (7+, 13+, 16+) additions, acting as a mass-market household hub.
4) Prime Video's high-volume, movie-heavy approach results in the lowest median Rotten Tomatoes score among its peers, indicating a "quantity over quality" dynamic that threatens critical prestige.

## Strategic Recommendations
Based on the data, Prime Video should:
1) Continue leveraging massive content volume as a primary competitive moat, ensuring users never feel the need to look elsewhere for sheer variety
2) Implement advanced, personalized recommendation engines to cure user "choice paralysis" and surface hidden gems from the massive catalog
3) Shift a portion of the budget toward high-quality, episodic original series to drive weekly cultural conversations and improve average critical reception
4) Expand investment in unscripted and reality television, which the data shows is a top-performing, highly engaging, and cost-effective genre
5) Deeper integration of Prime Video with the broader Amazon retail ecosystem (e.g., shopping tie-ins, exclusive Prime perks) to maximize overall subscriber lifetime value


## Repository Structure
A brief overview of how this repository is organized:

--> Uncleaned data/         # Raw datasets used for the analysis

--> Notebooks/              # Jupyter Notebooks containing the Python code

--> Cleaned data/           # Cleaned datasets used for the analysis

--> Visuals/                # Exported charts and graphs

--> PPT.pptx                # Final slide deck summarizing the analysis

--> README.md               # Project overview and key findings

--> requirements.txt        # Requirements for the setup


## Tools Used
Python: The core programming language used for data manipulation.
Pandas: Used for robust data cleaning, aggregation, and tabular analysis.
Matplotlib & Seaborn: Utilized for generating high-quality static visualizations (bar charts, heatmaps, box plots) to highlight trends.
Jupyter Notebook: The interactive environment used to compile the code, visualizations, and markdown commentary into a reproducible workflow.
