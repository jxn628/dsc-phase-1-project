# dsc-phase-1-project
# Summary
I was tasked with researching movies to see what types of movies are currently being made and using that information to make recommendations to Microsoft as to what types of movies to make with their new production studio.

I used financial data from The Numbers and Genre data from IMDB for this research. By linking them together, I was able to see which Genres had performed well at the box office as well as the production budget, total profit, and ROI. I used this data to caluculate Success Rates for breaking even and/or performing in the top quartile. 

The metrics that I recommend that Microsoft seek to emulate are movies where there was a very high break even success rate and high chance of performing in the top quartile. Using these metrics, I determined that Microsoft should focus on high budget movies primarily in the genres of Animation and Adventure. I also determined that they could diversify by making  Low Budget movies to suppliment their primary focus on high budget movies. For low budget, I recommended that they explore other genres with a high chance of breaking even and good potentional for perfoming in the top quartile. Specifically, Comedy, Mystery, Horror, Thriller, and Romance. 

# The Problem
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. I have been charged with exploring what types of films are currently doing the best at the box office, as well as translating those findings into actionable insights.

# The Data
I have been provided with data from several movie tracking websites. The data includes:
- general movie information (title, staff, release date)
- financial data (production budget, gross revenue)
- user and critic ratings

The data is very broad and each data set contains certain data points but none contain all of the data points. My task will be to clean and organize this data into a usable format for gaining insights into the movie industry so that I can make recommendations to Micorosoft.

For this project, I will using the following data:
- Financial Data from The Numbers
- Genre information from IMDB
- Ratings from IMDB

# Questions to Answer
1. How do we determine what a successful movie is?
2. Which genres have been the most successful recently?
3. Which of these genres should Microsoft pursue?
4. How much should Microsoft budget for the movies they produce?

# My Findings:
##  Measuring Success
I am going to use the 2010-2019 dataset as it contains the **genre data** that I need in order to answer future questions. I will slice out the most successful movies.
The two metrics that I will be using are **total profit and return on investment (ROI)**
I will then slice out the top 500 movies as that is roughly the top quartile for this dataset.
**These movies would be good for Microsoft to emulate as we want to be as successful as possible.**


**Justifying My Sample Size:**

In the above figure, you can see that while the total profit has a very wide range year-to-year, production budgets have largely stayed the same. In fact, average production budgets remained fairly consistent from the late 1990s through 2015.

While production budgets are currently trending up, the data that I have should be accurate for forecasting future performance.

## Which Genres have been the most successful?

**What genres correspond to the most profitable movies as well as the movies with the best ROI?**

Note: Since a movie can have multiple genres, I will do value counts for each of the 3 genre columns, and then do value counts to determine how many times each genre is associated with each dataset.



# Recommendations:
## Microsoft Should Focus on Animation and Adventure
**Animated Films** have highest break-even rate and top 500 rate of any other genre.

- This means that not only did 85% of these films recoup their production costs, but 81% of them ended up in the top quartile of profit performance.
- Animation is as safe of a bet as you can get.

**Adventure films** are a close second to Animation. 
- Ranked Second in both break-even rate and Top 500 rate.
- However, they have a higher average budget and lower average profit than Animation.


**Budget**

**I recommend a budget of 80 Million - 150 Million for these two genres.**
- 80 Million is high enough to avoid much of the risk that comes from attempting these genres with a low budget.
- 150 Million was where the top quartile of production budget begins. Microsoft is welcome to spend more than I have recommened, but if they stay in the range they have a low chance of losing money, and a high chance of getting a ROI of 2-6.
- Microsoft has a lot of resources at it's disposal and can afford the necessary budgets to make these movies.

##Other Genres to Consider
Fantasy, Sci-Fi, Action, Family, Comedy, and Mystery all have high break-even rates (67% or better), and a decent chance of making it into the Top 500. While these genres are not as safe of a bet as Animation or Adventure, they should reliabily hit the metrics that we care about.

**Low Budget Genres:**
- **Horror, Thriller, and Romance** films all have a better than 50% chance of breaking even, rank high in ROI potentional, and about a third of them could end up being one of the Top 500 profitable movies. 


