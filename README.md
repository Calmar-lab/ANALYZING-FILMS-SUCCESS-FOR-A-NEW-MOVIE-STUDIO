# ANALYZING-FILMS-SUCCESS-FOR-A-NEW-MOVIE-STUDIO
This analysis identifies key factors for film success to guide a new movie studio in building a successful portfolio. We examine genre popularity, and budgets, among other features to provide insights to align productions with audience demand and maximize profitability.

## BUSINESS UNDERSTANDING
To capitalize on the recent surge in original video content, our company is launching a new movie studio. This project seeks to analyze box office data to study the successes of films, genres, and directors, among other key performance factors to help the company make informed decisions on the type of films to produce.

The project's findings will be translated into strategic recommendations, guiding stakeholders to make data-driven decisions and positioning the studio for success.


## OVERVIEW
Our project analyzes the trends in the movie industry over the past few years in terms of the volume of production, which is the number of movies produced per year, preferences, and trending genres. It also focuses on the production costs and the gross revenue earned from the movies. It also focuses on the months and seasons that had the highest average gross revenue. This analysis intends to offer insight into market trends and audience preferences for different genres that could guide our company's decision-making.


## PROJECT OBJECTIVES
#### 1. Identify the top-rated genres to prioritize:
By identifying the most popular genres with audiences and generating high returns, the company can focus its production efforts on genres with the highest potential for profitability. This would involve analyzing past performance data on genre-based ratings, allowing the company to strategically invest resources into the genres that resonate with a wider audience.

#### 2. Identify the most popular directors/writers for collaboration:
Recognizing directors and writers with the most productions helps the company make informed partnership decisions. Collaborating with professionals can improve the quality of production.

#### 3. Find out the optimal seasons for movie releases:
Seasonal trends play a significant role in box office success. By understanding which release periods typically generate the most revenue, the company can schedule releases during high-demand periods. 

#### 4. Estimate the production budget:
Knowing the average production budget allows the company to set realistic financial expectations for new projects and assess potential funding requirements. 

#### 5. Estimate the average returns on films:
Analyzing the average return on investment (ROI) provides the company with a baseline for evaluating project performance. 

#### 6. Investigate the trend of movie production over the years:
By recognizing this trend, the company can adapt its production strategy to stay competitive, whether that means increasing output, adjusting genres, or diversifying distribution methods.



## DATA UNDERSTANDING AND ANALYSIS
This analysis uses data sourced from IMDb, a database, and TMDb, a CSV file, which provides comprehensive information on movies, including genres, directors, release dates, and audience ratings.
Key attributes such as genre, runtime, release timing, and financial performance will be assessed to ensure relevance and accuracy in analyzing factors that contribute to box office success. Quality checks will address any missing values or inconsistencies to prepare the data for analysis.

## DATA VISUALIZATIONS & RECOMMENDATIONS
#### 1. Identify the top-rated genres to prioritize:
![Alt text for the image](URL_of_the_image)

##### Recommendation
- Prioritize producing films in the highest-rated genres identified in the analysis, as these align with audience preferences and are likely to drive higher returns on investment.
- Top-rated genres often correlate with high viewership, so strategically invest in these genres to enhance audience engagement and maximize profitability.

##### Next Steps;
- Conduct a deeper market analysis to investigate the trends of audience genre preferences and interests. Further, analyze the top creators of these top-rated genres and consider collaboration.




#### 2. Identify the most popular directors/writers for collaboration:
![Alt text for the image](URL_of_the_image)

##### Recommendation
- Collaborate with the prolific directors and writers identified in the analysis to leverage their industry experience and minimize the risks associated with inexperience.
- Leverage the existing fan base of these creators to enhance the company’s credibility and attract an audience from the outset, fostering a strong market entry.

##### Next steps;
- Further investigate and analyze to understand the success rate of these creators, despite them producing the most films.




#### 3. Find out the optimal seasons for movie releases:
![Alt text for the image](URL_of_the_image)

##### Recommendation
- Release high-budget films during the months/seasons with historically higher revenues to maximize audience engagement and box office performance.
- Minimize major releases during the consistently low-revenue months/seasons; instead, consider using these periods for smaller films or niche projects, ensuring proper resource allocation.

##### Next steps
- Investigate how various genres perform in specific months to identify trends and optimal release periods for each genre.
- Further, analyze to find out the relationship between the time a movie is released and the revenue it generates.



#### 4. Estimate the production budget:
![Alt text for the image](URL_of_the_image)

##### Recommendations
- Consider maintaining production budgets near or below the mean (as indicated by the red line) to minimize financial risk while remaining competitive in the market.

##### Next steps;
- Analyze the correlation between budget ranges and revenue success.
- Examine which genres require higher budgets and investigate the ROI at lower budget levels.



#### 5. Estimate the average revenue on films:
![Alt text for the image]([URL_of_the_image](https://github.com/Calmar-lab/ANALYZING-FILMS-SUCCESS-FOR-A-NEW-MOVIE-STUDIO/blob/main/Average%20Worldwide%20Gross%20by%20Month.png?raw=true))

##### Recommendations
- Establish realistic revenue expectations, aiming for targets near or above the mean revenue to align with industry norms.
- Assess if the target revenue for upcoming films falls within competitive brackets, ensuring alignment with successful films in the market.

##### Next steps;
- Analyze the correlation between production budgets and worldwide gross revenue to identify optimal budget levels for returns.
- Assess gross revenue by genre to find out high-performing genres for targeted investments.



#### 6. Investigate the trend of movie production over the years:
![Alt text for the image](URL_of_the_image)

#### Recommendation
- Track the decline in movie production from 2019 to 2023 for potential industry challenges. In this case, investigate the rise of social media and the effects of COVID-19 during this decline period.
- Plan a careful investment approach in new productions.

##### Next steps;
- Identify and study successful films released post-2020 to discern effective genres, budgets, and distribution platforms.
- Investigate how streaming has influenced production and profitability, shaping future distribution strategies.


### LINEAR REGRESSION
#### Linear Regression Model of the Relationship Between Production Budget and Worldwide Gross Revenue

##### The relationship between production_budget and worldwide_gross



##### Interpretation
The scatter plot presents a not-so-perfect linear relationship between the variables but there is a positive relationship between the production budget and worldwide gross revenue.


##### Checking the model fit


##### Interpretation
- The upward slope of the regression line indicates a positive relationship between Production Budget and Worldwide Gross. This suggests that, on average, as the production budget increases, the worldwide gross revenue tends to increase as well.

- Visually, the regression line depicts a line of best fit illustrating how well our model is performing. Since most values are closely scattered around the regression line, it indicates that the model provides reasonably accurate predictions of worldwide gross revenue based on production budget. However, the presence of some scattered points, especially at higher budget levels, suggests that there are other influencing factors not captured by this model, indicating room for further exploration and improvement


#### Recommendation based on the model Analysis
Based on the analysis, we recommended that the company should consider budgeting for an increased production budget, as even a modest increase is likely to yield a proportional rise in worldwide gross revenue, enhancing overall profitability.

#### A PDF presentation is [here](https://www.canva.com/design/DAGU25uEniQ/2dUtZtnq2d3E0-AD998m4g/edit).

## CONCLUSION
This project has provided a comprehensive analysis of box office data sourced from IMDb and TMDb, uncovering success factors in the film industry. By examining genres, prolific creators, among other factors, we've derived actionable insights to guide the new movie studio's production strategy.
The visualizations effectively communicated these findings. As the company moves forward, leveraging these insights will be crucial for developing a profitable film portfolio and ensuring a competitive edge in the evolving landscape of original video content.
