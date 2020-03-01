# StatQuest Notes

---

A. 2020/02/29 - StatQuest: The standard error (A+B_Tipping.ipynb)
https://www.youtube.com/watch?v=XNgt7F6FqDU
1. Standard error is essentially, a standard deviation of the mean of bootstrap samples (many samples from the same population)
2. Sampling with replacement means if I have a sample of [1, 2, 8], my first sample could be [1, 2, 2] (repeated sampling of the same measurement), and my second sample can be [2, 2, 2]

---

B. 2020/02/29 - StatQuest: Confidence Intervals (A+B_Tipping.ipynb)
https://www.youtube.com/watch?v=TqOeMYtOc1w
1. Sample mean is not the mean of the whole population, but we can use bootstrapping to determine reasonable values of the mean for the whole population
2. A 95% confidence interval is just an interval that covers 95% of the bootstrapped means
3. Two-tailed t-tests are used to determine whether there is a statistically significant difference between two population's means while one-tailed t-tests are used to determine whether a population's mean is statistically larger than or lesser than another population's mean

---

C. 2020/03/01 - StatQuest: R-squared explained
https://www.youtube.com/watch?v=2AQKmw14mHM&t=5s
1. R^2 is the percentage of variation explained by the relationship between two variables
2. R^2 is easier to interpret because it's not obvious that R=0.7 is twice as good as R=0.5, but R^2=0.7 is what it looks like, 1.4 times as good as R^2=0.5
