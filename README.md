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

---

D. 2020/03/06 - What is a statistical distribution?
https://www.youtube.com/watch?v=oI3hZJqXJuc
1. Advantage of curve is not limited by width of bins and can estimate the measurements

---

D. 2020/03/06 - Histograms, Clearly Explained
https://www.youtube.com/watch?v=qBigTkBLU6g
1. Histograms are bins of measurements plotted to see how often a measurement has occurred

---

E. 2020/03/06 - The Normal Distribution, Clearly Explained!!!
https://www.youtube.com/watch?v=rzFX5NWojp0
1. Normal distributions are always centered on the average value
2. The width of the curve is defined by the standard deviation
3. Normal curves are drawn such that 95% of the measurements fall between +/-2 standard deviations around the mean

---

F. 2020/03/11 - StatQuest: Principal Component Analysis (PCA), Step-by-Step
https://www.youtube.com/watch?v=FgakZw6K1QQ&t=11s
1. Linear combination is simply a ratio between the two variables to make a PC
2. Singular Vector or Eigenvector is the 1 unit long vector consisting of x part units and y part units
3. The Loading Score is the scaled version of the linear combination
4. The Eigenvalue is the sum of squared distances for a PC
5. Square root of eigenvalue is the Singular Value for a PC
6. PC2 is the orthogonal version of PC1 if it's only 2D
7. Eigenvalues divided by sample size - 1 yields variation

---

G. 2020/03/15 - StatQuest: 
https://www.youtube.com/watch?v=pYxNSUDSFH4
1. Probabilities are the areas under a fixed distribution. pr(data|distribution)
2. Likeihoods are the y-axis values for fixed data points with distributions that can be moved. L(distribution|data)

---

H. 2020/03/23 - StatQuest:
https://www.youtube.com/watch?v=vemZtEM63GY
1. A 0.05 threshold for p-values means that 5% of the experiments, where the only differences come from weird random things, will generate p-value smaller than 0.05.
2. Getting a small p-value when there is no difference is called a False Positive.
3. P-value quantify how confident we should be that one item is different from another item
4. Hypothesis testing means determining whether two items are different
5. The null hypothesis is that the two items are the same
6. While p-values help decide whether two items are different, it doesn't tell us how different they are

---

I. 2020/04/11 - StatQuest - Sample Size and Effective Sample Size, Clearly Explained
1. Technical replicates only count when we want to describe a method
2. If we can calculate the correlation, we can calculate the effective sample size
3. Effective sample size = number of samples / (1 + (number of samples - 1) * correlation
