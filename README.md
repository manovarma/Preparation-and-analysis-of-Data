Data Preparation and Statistical Analysis of Supply Chain Performance
Overview
This project presents an in-depth analysis of a supply chain management system using statistical methods to explore key performance indicators and operational efficiency. The primary goal was to answer specific research questions regarding delivery delays, sales drivers, and seasonal patterns in order volume (pp. 3, 5, 7). The analysis provides insights into potential improvements in efficiency, customer satisfaction, and overall operational effectiveness. 
Project Structure
This repository contains the presentation slides (.pptx or similar) and screenshots of visualizations from the analysis. The core findings and methodology are documented in this README file.
Research Questions & Key Findings
The project addressed three main research questions, the hypotheses for which were all supported by the data analysis:
RQ1: Does the chosen shipping mode influence delivery delay beyond planned shipment time?
Finding: Yes. Multiple linear regression and Type II ANOVA showed that shipping mode has a significant effect on delivery delay, even when controlling for scheduled shipment time (p. 4).
RQ2: Does increasing the discount amount lead to higher sales?
Finding: Yes. Using Ordinary Least Squares (OLS) regression (
), it was determined that discounts explain a significant portion of sales variation. Sales behavior is better explained when product price is also considered (p. 6).
RQ3: Do monthly changes in order volume affect shipping performance?
Finding: No, not significantly. Despite strong seasonal variation in order volume, shipping performance remains statistically stable (determined via one-way ANOVA), indicating robust logistics operations that can handle demand fluctuations effectively (p. 8).
Methodology
The analysis utilized the following statistical methods:
Multiple Linear Regression: Used to assess the effect of shipping mode on delivery delay while controlling for scheduled shipment days (p. 4).
Type II ANOVA: Employed to test the independent effects of shipping mode on delivery delay (p. 4).
Ordinary Least Squares (OLS) Regression: Used to quantify the relationship between discounts and sales (p. 6).
One-way ANOVA: Used to compare shipping performance across different months (p. 8).
Visualizations and Results
Key visualizations from the project are included as screenshots within the repository. These include a correlation heatmap of business variables (p. 1), predicted delivery delay by shipping mode (p. 4), a linear relationship plot for discount and sales (p. 6), and charts showing average shipping delay and monthly order volume (p. 8).
Author
Manovarma Krishnasamy Thalaivar (FD0003362)
