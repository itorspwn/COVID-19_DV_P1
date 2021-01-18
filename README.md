# Tracking COVID-19 Cases in San Francisco and Los Angeles Counties 
- - -
## Background: 
COVID-19 has paralyzed the nation since mid-March. It has and continues to greatly impact our daily lives. Thus, when selecting a topic to analyze for Project 1, the global pandemic quickly emerged as the most salient current event to examine. Narrowing the scope of the project was difficult. There are so many different agencies, research institutes, universities and governments around the world collecting data on COVID-19. Thus, selecting one area to closely analyze was essential for the scope of this project.  Our initial key question was to examine COVID-19 spread in the major US metropolitan hubs. We uncovered key data from sources including Johns Hopkins, NIH and the CDC. We quickly realized the scope of our project was too large, leading us to look closer to home, within the same umbrella of major metropolitan areas. 
We made the decision to focus only on San Francisco and LA, specifically the counties. San Francisco is both a city and a county, whereas Los Angeles county included the city of Los Angeles and the surrounding area. Policy data for the two counties was inadequate; while we narrowed the scope, we now found ourselves with limited data. We made one final pivot and decided to focus on mobility data from Apple users to uncover any correlations between COVID-19 cases and changes in behavior as measured by tracking movements. 
- - -
## Key Questions: 
 1. Why the discrepancy of COVID-19 cases between the two areas? To answer this question, we needed to quantify and visualize the discrepancy between the two counties. We looked at the individual county demographics, industries of employment and COVID-19 testing, cases and death rate. 

 2. Comparing the two counties mobility data, will we see differences in mobility changes comparing work vs residential movements and retail vs grocery shopping? To answer these questions, we pulled the data from Apple mobility data for our counties of focus. 
- - -
## Data Exploration:
### County Demographics:
![demographic](output/census_bargraphs.png)
### COVID-19 Testing:
![testing](output/DailyTests.png)
### COVID-19 Daily Cases:
![dailycase](output/DailyCases_PerCapita.png)
### COVID-19 Cases, Two-Week Intervals:
![dailycase2](output/AverageCases_PerCapita.png)
### COVID-19 Daily Death Rate:
![deathrate](output/DailyDeaths_PerCapita.png)
### COVID-19 Death Rate, Two-Week Intervals:
![deathrate2](output/AverageDeaths_PerCapita.png)
### Top 10 Areas of Employment, San Francisco County:
![employmentsf](output/SF_top10_employees.png)
### Top 10 Areas of Employment, Los Angeles County: 
![employmentla](output/LA_top10_employees.png)
### All Types of Activites:
![allactivities](output/google_trend_2.png)
### Workplace and Residential Activity:
![WorkplaceResidential](output/google_trend_4.png)
### Retail and Grocery Activity: 
![RetailGrocery](output/google_trend_3.png)
### Mode of Transportation:
![transportation](output/apple_trend.png)
- - -
## Discussion, Conclusions, and Challenges:
More testing, fewer cases and fewer deaths have been recorded in SF County versus LA County. There is a clear difference in mobility changes between the two areas. LA County’s Apple users have seen less of a decrease of their mobility as compared to SF County across retail and shopping. SF County residents are now moving about their residence more, indicating they are home. Additionally, SF County residents have decreased their mobility at their workplaces in comparison to LA County. This could potentially correlate well with SF County’s increased movement at home. The areas of employment did not provide as much insight as we would have hoped. Initially, there was a thought that if many SF County residents are employed in tech, these jobs could translate well to work from home. However, of the top ten industries within SF, tech was not listed. A limitation of the data is that SF County residents do not necessarily work within SF County, and thus, we may be missing where the residents are employed.
Controlling community spread of COVID-19 has been a priority of the pandemic. SF County and the surrounding Bay Area counties were amongst the first in the nation and state of California to have a “shelter in place” mandate. We cannot make any conclusions about whether this initial shelter in place had lasting effects, but SF County residents have reduced mobility out in public versus LA county and LA County has had more COVID-19 cases and deaths. Continuing to limit mobility may help contain the spread of this virus. 
