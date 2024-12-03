# Project Proposal: Visualizing Brexit and Its Impacts

## Overview

This project aims to create a comprehensive and visually engaging analysis of Brexit-related data to better understand the referendum's impact on the UK's population, regional voting patterns, well-being, and current issues. The project will use both interactive and static visualizations to illustrate how Brexit has affected different aspects of society in the UK, including anxiety levels, well-being, voting patterns, and current public discourse.

## Goals and Motivation

The primary goal of this project is to visualize the impact of Brexit by focusing on critical aspects such as:
- Voting patterns and population density
- Well-being and anxiety levels across regions
- Current issues around Brexit

The motivation for this project is to provide clear and insightful data visualizations that inform the general public, policymakers, and researchers about the effects of Brexit on the UK's social and political landscape. The project uses data storytelling to deliver a compelling message about Brexit's consequences.

## Data Sources

The project uses several datasets to provide regional and temporal insights:
1. **Population Density Data**: Population density by region within the United Kingdom.
2. **Voter Turnout Data by Region**: Voter turnout percentages across regions during the Brexit referendum, categorized by support for Leave or Remain.
3. **Region Vote Data**: Flow of votes (Leave or Remain) for each region, enabling analysis of voting proportions.
4. **Anxiety Levels Data (2012-2018)**: Tracks anxiety levels in different parts of the UK (Wales, Scotland, England, Northern Ireland) to evaluate changes in well-being after the referendum.
5. **Well-Being Data**: Metrics such as life satisfaction, happiness, and anxiety, assessed across different regions, to analyze the impact of Brexit.
6. **Age Support Data**: Voting patterns by age group, highlighting which age groups had the highest support for Leave or Remain.
7. **Brexit Issues Data**: Prominent topics from Financial Times headlines related to Brexit (January - March 2020).

## Key Questions and Visualizations

1. **What is the population density of the United Kingdom?**
   - **Visualization**: A map of the United Kingdom using a gradient scale to represent population density, where darker shades indicate higher density.

2. **What is the voter turnout by region?**
   - **Visualization**: A bar graph displaying voter turnout for each region, categorized by the proportion of votes supporting the EU referendum (Leave or Remain).

3. **How did each region vote?**
   - **Visualization**: A Sankey diagram showing the flow of votes (Leave or Remain) from each region, with the thickness of lines representing the proportion of votes.

4. **Has personal well-being been impacted in areas voting Remain now that the UK is leaving the EU?**
   - **Visualization**: A line graph depicting anxiety levels in the UK from 2012 to 2018, divided by different countries (Wales, Scotland, England, and Northern Ireland). Additionally, multiple line graphs display metrics such as life satisfaction, feeling that life is worthwhile, happiness, and anxiety, assessed across regions.

5. **Was vote choice influenced by age?**
   - **Visualization**: Bar graphs showing age groups with the highest support for Leave and Remain.

6. **What are the issues around Brexit today?**
   - **Visualization**: A word cloud generated from Financial Times headlines (January - March 2020), highlighting prominent topics such as "trade," "talks," "immigration," and political figures like "Boris Johnson."

## Weekly Plan

| **Task Name**                         | **Status**    | **Assignee** | **Due**   | **Priority** | **Summary**                                                                                      |
|---------------------------------------|--------------|--------------|-----------|--------------|--------------------------------------------------------------------------------------------------|
| **Dataset Collection and Cleaning**   | Done         | Team         | Week 1    | High         | Gather all necessary datasets, clean and preprocess them for analysis.                           |
| **Exploratory Data Analysis (EDA)**   | Done         | Team         | Week 2    | High         | Conduct an initial analysis to understand data trends, relationships, and outliers.              |
| **Data Visualization Planning**       | Done         | Team         | Week 3    | Moderate     | Outline and sketch visualizations to illustrate key trends and insights.                         |
| **Create Initial Visualizations (Static)** | Done    | Team         | Week 4    | Moderate     | Use ggplot2 to create static visualizations for the identified trends.                           |
| **Interactive Visualization Development** | Done    | Team         | Week 5-6  | High         | Develop interactive and animated visualizations using Shiny or Plotly for deeper exploration.    |
| **Gender and Regional Analysis Visualizations** | Done | Team     | Week 7    | Moderate     | Create focused visualizations showing gender-specific and regional trends for each dataset.      |
| **Final Visualization Refinement and Testing** | Done  | Team     | Week 8    | High         | Refine visuals for clarity, interactivity, and aesthetics. Test for accuracy and usability.      |
| **Report Writing and Documentation**  | Done         | Team         | Week 9    | Moderate     | Compile findings into a well-documented report, including descriptions of methodologies.         |
| **Project Presentation Preparation**  | Done         | Team         | Week 10   | High         | Prepare a presentation of findings, including visual aids and an overview of key insights.       |