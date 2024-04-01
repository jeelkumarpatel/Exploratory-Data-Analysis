# Project Overview
The Waze data team is currently developing a data analytics project aimed at increasing overall growth by preventing monthly user churn on the Waze app. Thorough exploratory data analysis (EDA) enables Waze to make better decisions about how to proactively target users likely to churn, thereby improving retention and overall customer satisfaction. 

# Key Insights
The more times users used the app, the less likely they were to churn. While 40% of the users who didn't use the app at all last month churned, nobody who used the app 30 days churned.

Distance driven per driving day had a positive correlation with user churn. The farther a user drove on each driving day, the more likely they were to churn.

Number of driving days had a negative correlation with churn. Users who drove more days of the last month were less likely to churn.

Users of all tenures from brand new to ~10 years were relatively evenly represented in the data.

Nearly all the variables were either very right-skewed or uniformly distributed. 
For the right-skewed distributions, this means that most users had values in the lower end of the range for that variable. 
For the uniform distributions, this means that users were generally equally likely to have values anywhere within the range for that variable.

Several variables had highly improbable or perhaps even impossible outlying values, such as: driven_km_drives, activity_days and driving_days.
