# Part I - Ford GoBike System Data

## Dataset

> This dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area for Feruary 2019.
The dataset can be found [here](https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems)

## Summary of Findings

> The dataset has a lot of categorical data and only 1 column of continuous data which is the duration_seconds. This made it hard to study correlations through scatter plots but provided me with an opportunity to deep dive into categorical data analysis. I derived age from member_birth_year for ease of interpretation and also converted duration_seconds to duration_minutes and duration_hours, also for ease of interpretation.

The main findings I made on this data are in relation to the effect users and user characteristics on duration. There are more rentals that spend less than an hour although very few rentals get to spend 23 hours with the bike. Thusday has a higher count of rentals whereas Saturday and Sunday have the lower count of rentals. Howerver, The average time spent on rentals by weekday indicate that Saturday and Sunday are the days where people spend more time with the bikes, with the average time of about 16 minutes.

There is a higher count of male bike renters, although on average they use the bike for less duration. The 'other' gender spends more duration on the bikes on a daily basis.

There are more subscriber users than there are customer users, and interestingly the subscribers use less duration on the bike than customers.

## Key Insights for Presentation

> Key insights for presentation

For the presentation, I focus on the relationship betweet the gobike renters' demographics and the duration and date.
I start by introducing the duration and date variable, and then I proceed to the renters' columns and plot the relationships between these. The different relationships I explore are:
> What is the distribution of the duration and age
> What is the average time spent on rentals by age 
> On average, which user type spends more time on the bike and what is their gender?
> On average, which gender spends more time with a bike throughout the week?
