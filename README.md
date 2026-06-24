# Maingames_Streamer_analysis

# I. Problem Statement
MainGames aims to help streamers increase their revenue by leveraging streaming data and personality-related features. The objective of this analysis is to identify factors associated with streamer monetization and determine which characteristics are most influential in driving audience contributions.

The target variable used in this study is:

PaidStarPerWatchedHour — the amount of stars received per watched hour.

The analysis seeks to answer the following questions:

What factors influence streamer monetization?
Do personality traits contribute more than follower count?
Which streamer characteristics should MainGames prioritize for creator development programs?

# II. Dataset Overview
The dataset contains information from 631 streamers across Southeast Asia.

# Data Coverage
Countries: Indonesia, Vietnam, Philippines
Total Records: 631 streamers
Features: 127 variables

# Feature Categories
Streamer Information:
- Country
- Gender
- Game
- Total Follower
- Broadcast Hours

Personality Features
Generated using AI-based personality assessment tools:
- Character Traits
- Temperament
- Self-Esteem Indicators
- Personal Values
Examples:
- Character_Cont_Extraversion
- Character_Cont_Conscientiousness
- Temperament_Sanguine
- Personal_Values_Facet_Cont_Hedonism

Role Features
Streamer archetypes such as:
- Role_Guru
- Role_Strategist
- Role_Director
- Role_Designer

Target Variable
PaidStarPerWatchedHour

# III. Methodology
1. Data Cleaning
- Removed missing values in the target variable.
- Removed unnecessary index columns.
- Checked missing values and handled them appropriately.

2. Exploratory Data Analysis (EDA)
Performed exploratory analysis to understand:
- Distribution of PaidStarPerWatchedHour
- Country-level differences
- Gender-level differences
- Game-level differences

3. Feature Engineering
- Applied log transformation to the target variable to reduce skewness.
- Converted categorical variables into numerical representations using One-Hot Encoding.

4. Machine Learning Model
A Random Forest Regressor was used to identify the most influential variables affecting monetization.
Model evaluation metrics:
- R² Score
- Mean Absolute Error (MAE)

5. Feature Importance Analysis
Feature importance scores were extracted from the Random Forest model to determine which streamer attributes contributed most to monetization outcomes.

# IV. Key Findings
1. Strategic Streamer Profiles Matter
Role_Strategist emerged as the most influential feature in predicting monetization performance.
This suggests that streamers with strategic and structured engagement behaviors may generate higher audience spending.

2. Hedonism Is Strongly Associated With Monetization
Personal_Values_Facet_Cont_Hedonism showed significant importance.
Streamers who project enjoyment, entertainment, and positive experiences may encourage greater audience participation.

3. Educational Streamers Show Strong Potential
Role_Guru was identified as one of the top predictors.
This indicates that audiences may be more willing to support streamers who provide guidance, knowledge, or educational value.

4. Personality Traits Outperform Follower Count
Several personality-related features ranked higher than Total Follower.
This suggests that streamer behavior and audience engagement style may be more important than popularity alone.

5. Monetization Distribution Is Highly Skewed
A small number of streamers generate significantly higher monetization compared to the majority of streamers.
This indicates the existence of high-value streamer segments that deserve further investigation.

# V. Business Recomendations
1. Develop creator coaching programs focused on strategic audience engagement techniques.
2. Identify and nurture streamers with strong Strategist and Guru characteristics through targeted creator development initiatives.
3. Use personality-based segmentation in addition to follower count when selecting creators for promotion and support programs.
4. Investigate high-performing streamer outliers to uncover best practices that can be replicated across the platform.
5. Collect additional behavioral and engagement data to improve future monetization prediction models.




