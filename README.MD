# Videogame Analysis

## Table of Contents
- [Videogame Analysis](#videogame-analysis)
  - [Table of Contents](#table-of-contents)
  - [Project Objective](#project-objective)
  - [Project Structure](#project-structure)
  - [Tools and Techniques Utilized](#tools-and-techniques-utilized)
  - [Specific Results and Outcomes](#specific-results-and-outcomes)
  - [What I Have Learned From This Project](#what-i-have-learned-from-this-project)
  - [How to Use This Repository](#how-to-use-this-repository)
  

## Project Objective

The objective of this project is to analyze the video game sales data for the online store Ice, which sells video games worldwide. The project aims to identify patterns that determine whether a game will be successful or not. These insights will help the company identify potential hit games and effectively plan advertising campaigns.

[back to top](#videogame-analysis)

## Project Structure

**Sales Trends by Year and Platform:**

- Analyzed the distribution of video game releases over the years and identified key periods of growth and decline in sales across different platforms.
- Found that some platforms have remained popular while others have seen their sales decrease over time. The lifecycle of new and old - platforms was examined to understand market dynamics.

**Platform Sales Analysis:**
- Identified platforms with the highest total sales and analyzed their year-over-year performance.
- Created boxplots to understand the global sales distribution of all games across different platforms.
- Examined the impact of user and critic reviews on game sales for a popular platform and calculated the correlation between these reviews and sales.

**Sales by Genre and Regional Trends:**
- Analyzed the distribution of games across various genres to identify the most lucrative ones.
- Created user profiles for key regions (North America, Europe, and Japan), identifying top platforms, genres, and the influence of ESRB ratings on sales in each region.

**Hypothesis Testing:**
- Conducted statistical tests to verify if user ratings are the same between platforms (e.g., Xbox One vs. PC).
- Tested the hypothesis that user ratings differ between genres, such as Action and Sports.

[back to top](#videogame-analysis)

## Tools and Techniques Utilized
Data Manipulation and Analysis:

- **pandas**: Cleaning, handling missing values, and exploring the dataset to find patterns.
- Various techniques for data type conversion, handling null values, and adjusting column formats for consistency.

- **Visualization:** Plots and graphs were created to visualize sales distributions, year-over-year trends, and the influence of factors like platform, genre, and region on game sales.

- **Statistical Analysis**:
  - Used statistical tests to confirm or refute hypotheses about user ratings and genre preferences.
  - Calculated and interpreted correlations to understand the relationship between reviews and sales.

[back to top](#videogame-analysis)

## Specific Results and Outcomes

**Sales Trends by Year and Platform:**
- **Games Release Trends:** The number of game releases peaked around 2008-2009, after which there was a decline in new releases up to 2016. This indicates a possible market saturation or shift in gaming preferences.
- **Platform Life Cycle**: Platforms like PlayStation 2 (PS2) and Nintendo DS saw their peak sales several years after their release but eventually declined as newer platforms emerged. The analysis showed that a platform's lifecycle typically spans around 10 years, with sales peaking 2-5 years after launch.

**Top Platforms and Their Dynamics:**
- **Best-Selling Platforms:** The top platforms with the highest total sales were PlayStation 2, Xbox 360, and PlayStation 3. The analysis revealed that some platforms like PlayStation 4 (PS4) and Xbox One were still growing in 2016, indicating potential for further growth in 2017.
- **Sales Distribution:** Boxplot analysis showed significant variance in game sales across platforms, with some outliers driving much higher sales (e.g., blockbuster games). Median sales figures were generally low, indicating that while some games are highly successful, most have modest sales.
- **Sales Trends Over Time:** PlayStation 4 and Xbox One, as newer platforms, had an upward sales trend compared to older platforms like Wii or PS2, which were declining.

**Genre Analysis and User Preferences:**
- **Most Popular Genres**: Action, Sports, Shooter, and Role-Playing were identified as the genres with the highest sales. The Shooter genre had the highest median sales, often driven by blockbuster titles, whereas genres like Puzzle and Adventure had significantly lower sales.
- **Sales by Genre**: Although Action and Shooter games dominated the market in terms of total sales, the Sports and Platform genres also maintained high average sales, often due to recurring franchises (e.g., annual sports titles).

**Regional Preferences and Sales Distribution:**
- **North America (NA)**: The top platforms were Xbox 360, PS3, and Wii, with the Shooter and Action genres performing the best. Games with higher ESRB ratings (Teen and Mature) had stronger sales.
- **Europe (EU)**: PlayStation platforms (PS3 and PS4) were more popular, and the Action, Shooter, and Sports genres dominated sales. Unlike NA, the difference in sales across ESRB ratings was less pronounced.
- **Japan (JP)**: Nintendo platforms like 3DS and DS were dominant. The Role-Playing genre was significantly more popular, and ESRB ratings showed little to no effect on sales, with a preference for games rated for all audiences.
- The analysis of these regional preferences showed that targeting campaigns according to genre popularity and platform availability in each region would be crucial for maximizing sales.

**Impact of Reviews on Sales:**
- **Critic and User Scores**: The analysis showed a moderate positive correlation between critic scores and sales, especially for popular platforms like PS4 and Xbox One. User scores had a weaker correlation, indicating that while positive reviews can help sales, they are not the sole driver of a game's success.
- **Scoring Differences Across Platforms**: The average user ratings on Xbox One and PC were not statistically different, confirming that user satisfaction is similar across these platforms.
- **Genre Ratings Comparison**: The hypothesis testing revealed a significant difference in user ratings for Action vs. Sports games, indicating different user preferences and expectations across genres.

**Insights for Planning the 2017 Campaign:**
- **Platform Trends**: Platforms like PS4 and Xbox One were identified as having the most growth potential in 2017. Investment in games for these platforms is likely to yield high returns.
- **Genre Targeting**: Action and Shooter games have the highest sales potential across regions, but localized campaigns in Japan should focus on Role-Playing games to match local preferences.
- **Marketing Strategies**: Emphasizing high critic scores in marketing campaigns can help boost game sales, especially for new releases on popular platforms.

[back to top](#videogame-analysis)

## What I Have Learned From This Project

**Data Cleaning and Preparation:**
- Skills in processing real-world datasets, managing missing data, and ensuring data consistency for analysis.
- Learned to handle special cases, such as the presence of abbreviations like TBD (To Be Determined) in the dataset.

**Market Analysis Skills:**
- Developed the ability to analyze sales trends across regions and platforms, drawing conclusions about consumer behavior and market dynamics.
- Ability to create regional user profiles based on platform and genre preferences, which is crucial for targeted marketing and advertising strategies.

**Hypothesis Testing and Statistical Techniques:**
- Improved skills in formulating and testing hypotheses, understanding the differences between user ratings across platforms and genres.
- Applied statistical methods to analyze the significance of different variables on video game sales.

**Visualization and Reporting:**
- Enhanced capability in creating meaningful visualizations to convey data trends effectively.
- Gained experience in summarizing key findings and drawing actionable insights for business strategy.

[back to top](#videogame-analysis)

## How to Use This Repository

1. **Clone the Repository**
git clone [https://github.com/realdanizilla/Videogames.git](https://github.com/realdanizilla/Videogames.git)


2. **Review Jupyter Notebooks**
Go through the notebooks for data exploration, sales analysis, and predictive modeling of video game sales trends.

3. **Run Data and Sales Analysis**
Execute the provided notebooks to understand the data, perform sales analysis, and review conclusions about platform performance.

4. **Extract Insights**
Use the analysis to explore patterns in game popularity, platform growth/decline, and genre-based sales trends.


[back to top](#videogame-analysis)