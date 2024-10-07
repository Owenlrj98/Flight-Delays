# Flight-Delays

Summary of Flight Delay Analysis Report

This report analyzes various factors contributing to flight delays, focusing on arrival delays as the primary metric. Key findings include:

Question 1: Timing for Minimizing Delays

Best Time of Day: Data from 1997 and 1998 shows that the highest percentage of early/on-time arrivals occurs between 4 AM and 5 AM.

Best Day of Week: Saturday has the highest percentage of early/on-time arrivals for both years, making it the best day to minimize delays.

Best Time of Year: September is identified as the month with the highest percentage of early/on-time arrivals in both 1997 and 1998.

Question 2: Impact of Plane Age on Delays

Analysis of planes from 1956 to 1998 indicates that newer planes experience more delays than older ones. In both 1997 and 1998, delays peaked in planes manufactured in the most recent years, suggesting no correlation between older planes and increased delays.

Question 3: Seasonal Flight Frequency Trends

Flight frequency data for 1997 (ORD to DFW) shows the highest travel in Fall, whereas in 1998 (ORD to ATL), the highest travel occurs in Summer, highlighting seasonal variations in passenger volume.

Question 4: Cascading Failures

Examples illustrate cascading failures in flight schedules, where initial delays lead to subsequent delays on connecting flights. Two specific cases show significant delays propagating through the flight schedules.

Question 5: Predictive Modeling of Delays

Logistic regression is employed to predict flight delays based on month, day of the week, and flight number. The model shows average accuracy (around 50-52%) for both years, with varying sensitivity and specificity. The 1998 model is better at predicting non-delays but less effective at predicting actual delays compared to 1997.

Conclusion

The analysis demonstrates the potential to statistically evaluate flight delays using R and Python, identifying significant variables that affect delays. However, the average accuracy of the logistic regression model suggests a need for improved predictive methods and consideration of additional factors influencing flight delays.
