# Politics of Energy Transition Final Project
## Question ##

How does the support of environment change for Americans when tested over a few variables? I will test 3 variables in this file
1. Average Crude Oil Price In a Year
2. Total Lobbying Firm Money Spent In a Year
3. The Year over year-over-year change of Average Gas Price

Why is this important?

Using these methods can help Politicians or NGOs gain better clarity as to what makes Americans value the Environment over different scenarios, and how important their principles are when challenged through a variety of circumstances (high gas prices for example).

##Summary of Pol_Energy File and Findings##

Datasets Used:
To gauge how well Americans support the environment over the years, I will use a Gallup poll stemming from 1989 until 2023. The link can be found here: https://news.gallup.com/poll/1615/environment.aspx
I will use the Fred dataset to see how crude oil prices have changed over the years. I have matched the data to come from 1989 to 2023. The link can be found here: https://fred.stlouisfed.org/series/DCOILWTICO
For my second hypothesis I would like to track total Oil lobbying over the years 1989 until 2023, to find this I used an open secrets file found here: https://www.opensecrets.org/federal-lobbying/industries/summary?cycle=2007&id=E01
For my third hypothesis, I tested the rate of year-over-year change in gasoline prices from 1989 until 2023. The link is found here: https://www.opensecrets.org/federal-lobbying/industries/summary?cycle=2007&id=E01

Hypothesis 1:
- There is a negative effect between higher crude oil prices and the environmental support Americans have.
Scatter Plot demonstrating the relationship between both variables.

<img width="567" alt="Screenshot 2023-12-14 at 4 36 48 PM" src="https://github.com/Jorge9555/Pols-106-Final/assets/104950778/3f378754-a7f1-4584-9f1b-c75a317f765e">


Linear relationship: 
y = -0.00x + 62.00

Hypothesis 2:
-There is a negative relationship between higher lobbying efforts and environmental support. 
Scatter Plot demonstrating the relationship between both variables

<img width="567" alt="image" src="https://github.com/Jorge9555/Pols-106-Final/assets/104950778/4bb5cba6-e421-41c5-aa71-d887be5c9e6f">


Linear Relationship:
y = -0.00x + 64.55

Hypothesis 3:
-There is a negative relationship between high year-over-year gas price change and environmental support in the US
Scatter plot with both variables.

<img width="567" alt="image" src="https://github.com/Jorge9555/Pols-106-Final/assets/104950778/60c79988-47e9-4281-a492-9ee923dcd880">


Linear Relationship:
y = 0.05x + 60.91

The more extensive file can be found under the Pol_Energy.ipynb file in the repository. 
