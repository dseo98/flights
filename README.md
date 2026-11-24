# Flight Delay Analysis: ORD vs. MSN


# About the Project
For this project, I'm analyzing flight delay data from two airports: Chicago O'Hare International Airport (ORD) and Dane County Regional Airport (MSN).

I wanted to see how flight delays differ between the two airports and whether one airport has a higher delay rate than the other. I also plan to use this data to build machine learning that can predict flight delays.

# Why I Chose this Project
I chose this topic because flight delays are something that many people experience when traveling. Since Thanksgiving is coming up, I started thinking how busy airports get during the holiday season and how common flight delays can be.

I became curious about whether some airports have more delays than others and what factors might affect flight delays. For example, I wanted to see if the airline, departure time, or airport could make a difference.

As a Data Science student, I wanted to apply what I have learned in class to a different dataset and see how I could use those skills in a real-world situation. I thought this project would be a good opportunity to practice data analysis and explore something I was personally interested in.

# Airline Delay Analysis
I started by looking at flight delays for different airlines. I calculated the total number of flights, delayed flights, and delay rates for each airline.

# Comparing ORD and MSN
ORD had a higher delay rate with 19.69% than MSN with 15.99%, with a difference of about 3.70%.

# Two-Proportion Z-Test
I used a two-proportion z-test to check whether the difference between the two airports was statistically significant. 

- H0: delay rates at ORD = delay rates at MSN
- Ha: delay rates at ORD != delay rates at MSN

- pooled proportion: 0.1954
- p-value: 0.00515
- significance level: 0.05

Since the p-value is less than 0.05, we can reject the null hypothesis. This suggests that there is a statistically significant difference in flight delay rates between the two airports.
