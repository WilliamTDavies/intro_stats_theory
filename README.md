
# Week 1 — Introduction to Statistical Data Analysis

This week introduced the module, the basic idea of statistical thinking, and why statistics matters in social and humanitarian research. The module is designed to help you work with quantitative and geospatial data, and to present findings clearly using tables, charts, figures, diagrams, and maps. It also explained that the course uses SPSS for statistical data analysis in the computer practicals. 

## Data vs information

A key distinction is between **data** and **information**. Data are raw facts or observations; information is data with context, meaning, and use. In the slides, weather temperature is an example of data, while a weather report is information. Maps were also presented as information artefacts because they transform geographic data into something interpretable. 

## Research methods

The course distinguishes between quantitative and qualitative research. Quantitative research uses many observations and is suited to describing patterns across larger populations, while qualitative research usually uses fewer observations and aims for depth rather than breadth. Questionnaires were introduced as a common quantitative method because they collect standardised data, often using closed questions. 

## Variables and operationalisation

A variable is anything that can vary from one case to another. A concept becomes usable in research only when it is operationalised into a measurable variable. That means the categories must be both mutually exclusive and collectively exhaustive. If they are not, the data become unreliable and invalid. 

## Levels of measurement

The slides emphasised the main measurement levels in statistics: nominal, ordinal, and interval/ratio. These differ by whether categories can be ordered and whether the distances between categories are meaningful. 

### Nominal

Nominal variables are categories with no natural order. Examples include sex, religion, property type, or nationality. They tell you what category something belongs to, but not whether one category is higher or lower than another. 

### Dichotomous

Dichotomous variables are nominal variables with only two categories, such as yes/no or male/female. 

### Ordinal

Ordinal variables can be ranked, but the gap between ranks is not measurable or equal. For example, “not at all / somewhat / very” gives order, but not exact distance. 

### Interval/ratio

Interval/ratio variables are numeric and have equal spacing between values. Ratio variables also have a true zero, while interval variables do not. That is why income, age, height, and weight are treated differently from categories like “high / medium / low.” 

---

# Week 2 — Graphs, Frequency Tables, and Measures of Central Tendency

This week focused on summarising data and presenting it clearly. Graphs and charts were presented as fast, visual ways to compare groups, identify trends, and reveal relationships that may not be obvious in raw numbers. Pie charts and bar charts were linked mainly to nominal and ordinal data, while histograms were linked to interval/ratio data. 

## Why graphs matter

Graphs help because they:

* present information quickly,
* show patterns and relationships,
* make comparisons easier,
* and reduce the need to interpret long lists of numbers. 

## Pie chart

Pie charts are often used with nominal and ordinal variables. Each slice represents a category, and all slices together make up 100%. 

## Bar chart

Bar charts are also used for nominal and ordinal variables. The height of each bar shows the frequency or percentage for each category. 

## Histogram

Histograms are used for interval/ratio variables. They display the distribution of values without grouping in the same way as a bar chart. They are especially useful for seeing whether a distribution is symmetric, skewed, or contains outliers. 

## Proportions, percentages, and ratios

These were introduced as standardisation tools so that groups of different sizes can be compared fairly.

### Proportion

A proportion expresses the fraction of a group that has a certain attribute.

$$
P = \frac{f}{N}
$$

Where:

* (f) = frequency of the category
* (N) = total number of cases

Proportions range from 0 to 1. 

### Percentage

A percentage is just a proportion multiplied by 100.

$$
% = P \times 100
$$

This gives the number of cases per 100. 

### Ratio

A ratio compares one group to another. In the slides, the key idea is that the group named after “to” goes in the denominator. Ratios are useful for comparing relative frequency across populations. 

## Frequency tables

Frequency tables summarise one variable by showing:

* frequency,
* percent,
* valid percent,
* cumulative percent. 

### Frequency

The number of times a category appears.

### Percent

The share of all cases, including missing data.

### Valid percent

The share of only the non-missing cases.

### Cumulative percent

The running total percentage up to a given category. 

## Missing data

The slides stress that missing data must be handled carefully. Missing cases are usually excluded from analysis, which is why a table can show different totals for percent and valid percent. 

## Population and sample

A population is the full group of interest. A sample is a subset taken from that population. Sampling is necessary because surveying everyone is usually impossible, too expensive, or too slow. The sample must represent the population if the results are to be generalised. 

## Measures of central tendency

These tell you where the data cluster.

### Mode

The mode is the most frequent value. It can be useful for categorical data as well as numerical data. A distribution can be unimodal, bimodal, or multimodal. 

### Mean

The mean is the arithmetic average.

$$
\bar{X} = \frac{\sum X}{N}
$$

Where:

* ($\sum X)$ = sum of all values
* (N) = number of values

The mean uses all values, but it is sensitive to outliers. 

### Median

The median is the middle value when the data are ordered. If there are two middle values, the median is their average. It is more resistant to outliers than the mean. 

## Outliers

Outliers are unusually high or low values compared with the rest of the distribution. They can distort the mean and create skew, which is why the median is often better for data such as income. 

## Measures of dispersion

These tell you how spread out the data are.

### Range

The range is the highest value minus the lowest value.

$$
R = H - L
$$

Where:

* (H) = highest value
* (L) = lowest value

It is simple, but it uses only two values from the whole dataset. 

### Quartiles

Quartiles split the data into four equal parts:

* Q1 = first quartile
* Q2 = median
* Q3 = third quartile 

### Interquartile range

The IQR measures the spread of the middle 50% of the data.

$$
IQR = Q_3 - Q_1
$$

It is less affected by outliers than the range. 

### Box plot

A box plot shows the five-number summary:

* minimum
* Q1
* median
* Q3
* maximum 

---

# Week 3 — Probability, Standard Deviation, Normal Curve, Skewness, and Significance

This week moved from descriptive statistics into uncertainty and inference. It covered probability, spread around the mean, the normal distribution, and the logic of statistical significance. 

## Probability

Probability measures the likelihood that an event will occur. It lies between 0 and 1, where 0 means impossible and 1 means certain. The slides use coins and dice to show that probabilities across all possible outcomes add to 1. 

### Probability formula

$$
P(E) = \frac{\text{number of favourable outcomes}}{\text{total number of possible outcomes}}
$$

For example, the probability of heads on a fair coin is:

$$
P(\text{heads}) = \frac{1}{2} = 0.5
$$

The same logic applies to dice, where the probability of rolling any one number is (1/6). 

## Standard deviation

Standard deviation measures how spread out data are around the mean. A low standard deviation means the values are tightly clustered; a high standard deviation means they are more dispersed. 

### Standard deviation formula

$$
s = \sqrt{\frac{\sum (X_i - \bar{X})^2}{N}}
$$

Where:

* ($X_i$) = each value
* ($\bar{X}$) = mean
* (N) = number of cases

The calculation steps are:

1. calculate the mean,
2. subtract the mean from each value,
3. square the differences,
4. average the squared differences,
5. take the square root. 

### Variance

Variance is the squared version of standard deviation.

$$
s^2 = \frac{\sum (X_i - \bar{X})^2}{N}
$$

It measures the same idea — spread — but in squared units. 

## Normal distribution

A normal distribution is bell-shaped and symmetric. It has one peak, and the mean, median, and mode are equal. The tails approach the axis but never touch it. 

### Empirical rule

In a normal distribution:

* about 68% of values lie within 1 SD of the mean,
* about 95% lie within 2 SD,
* about 99.7% lie within 3 SD. 

## Confidence intervals

A confidence interval is a range of values within which we expect the true mean or proportion to fall.

* 95% confidence interval = standard level used in most work
* 99% confidence interval = more conservative, wider interval 

## Skewness

Skew occurs when a distribution is distorted away from normality, usually because of outliers. Positive skew means a long tail to the right; negative skew means a long tail to the left. Outliers can pull the mean away from the median and mode. 

## Statistical significance

A result is statistically significant if the p-value is less than the chosen alpha level, usually 0.05. That means the result is unlikely to have occurred by chance alone if the null hypothesis were true. 

---

# Week 4 — Hypothesis Testing, t-tests, and Correlation

This week dealt with inferential statistics. The slides stressed that much of social research is based on comparing means across groups and testing whether observed differences are likely to be real. 

## Hypotheses

### Null hypothesis

The null hypothesis states that there is no trend, relationship, or difference in the population. 

### Alternative hypothesis

The alternative hypothesis states that a trend, relationship, or difference does exist. 

## One-tailed and two-tailed tests

A one-tailed test is used when the hypothesis predicts a direction, such as “greater than” or “less than.” A two-tailed test is used when the hypothesis predicts a difference without specifying direction, such as “not equal to.” 

## t-test: what it is

A t-test compares the means of two groups. It is used to test whether a process or intervention has a real effect, or whether two groups are statistically different from each other. 

The slides list the main uses as:

* comparing a sample mean with a population mean,
* comparing two independent samples,
* comparing the same sample at two different times. 

## t-test logic

The key idea is:

* calculate the t-value,
* find the critical t-value,
* compare them,
* reject the null if the calculated t-value exceeds the critical value. 

## t-test formula

For an independent-samples t-test, the slides give the formula in the form:

$$
t = \frac{\bar{x}_1 - \bar{x}_2}{\sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}}
$$

Where:

* ($\bar{x}_1,$ $\bar{x}_2$) = sample means
* ($s_1^2$, $s_2^2$) = sample variances
* ($n_1$, $n_2$) = sample sizes

That formula compares the difference in group means with the amount of variation in the data. 

## t-test example

In the example shown in the slides, there were 16 participants in each group, and the independent-samples t-test produced:

$$
t = 2.34
$$

with

$$
df = n_1 + n_2 - 2 = 16 + 16 - 2 = 30
$$

The critical value at the 0.05 level was 2.042. Since (2.34 > 2.042), the null hypothesis was rejected. 

## Why t-tests matter

The t-test matters because it gives a formal decision rule for judging whether a group difference is likely real or just sampling noise. That is the point of hypothesis testing: not to describe the sample, but to infer about the population.  

## Correlation

Correlation measures the strength and direction of a linear relationship between two interval/ratio variables. It is symmetrical, meaning neither variable is treated as inherently dependent in the same way as regression. 

### Pearson’s r

The usual null hypothesis for Pearson’s correlation is:

$$
H_0: r = 0
$$

This means no linear relationship exists in the population. The alternative ($H_a$ or $H_1$) is:

$$
H_a: r \neq 0
$$

This means a linear relationship exists. 

### Pearson correlation formula

$$
r = \frac{\sum (X - \bar{X})(Y - \bar{Y})}{\sqrt{\sum (X - \bar{X})^2 \sum (Y - \bar{Y})^2}}
$$

Interpretation:

* (r = +1): perfect positive correlation
* (r = 0): no linear correlation
* (r = -1): perfect negative correlation 

### Correlation and significance

A correlation should be read together with its p-value. A stronger coefficient and a larger sample both make statistical significance more likely. The slides also note that correlation does not mean causation. 

---

# Week 5 — Chi-square, Regression, and General Q&A

Week 5 moved into categorical association and prediction.

## Cross-tabulation tables

Cross-tabulation tables show the relationship between two variables by placing one variable in rows and the other in columns. They are especially useful for nominal and ordinal variables. 

## Chi-square

Chi-square tests whether the difference between observed frequencies and expected frequencies is large enough to be unlikely under the null hypothesis. It is based entirely on frequencies, not means. 

### Chi-square logic

* **Observed frequencies** = actual counts in the table
* **Expected frequencies** = counts expected if there were no relationship 

### Chi-square formula

The slides express chi-square as the sum of the squared differences between observed and expected frequencies, divided by the expected frequency in each cell:

$$
\chi^2 = \sum \frac{(f_o - f_e)^2}{f_e}
$$

Where:

* ($f_o$) = observed frequency
* ($f_e$) = expected frequency

The bigger the gap between observed and expected counts, the more evidence there is against the null hypothesis. 

### Rule of thumb

Chi-square should not be used if expected frequencies are below 5 in any category or cell. 

## Regression

Regression is used to describe and predict the relationship between two variables. The slides define linear regression as a best-fitting straight line used to make predictions from one variable to another. 

### Linear regression equation

The basic line equation is:

$$
Y = a + bX
$$

Where:

* (Y) = predicted dependent variable
* (a) = intercept
* (b) = slope
* (X) = independent variable

The slope tells you how much (Y) changes for a one-unit increase in (X). 

### Why regression is different from correlation

Correlation only tells you whether two variables move together. Regression goes further and uses that relationship to predict one variable from another. 

-------
-------
-------



# Key Terms and Definitions — Statistical and Geospatial Data Analysis

# Week 1 — Foundations, Data, Variables, and Measurement

## Data

Raw facts, observations, or measurements collected about the world. Data on their own have little meaning until interpreted. 

## Information

Data that have been organised, interpreted, or contextualised so they become meaningful and useful. A weather report is information created from weather data. 

## Quantitative research

Research based on numerical data and statistical analysis, usually involving larger numbers of observations. 

## Qualitative research

Research focused on meanings, experiences, or detailed understanding, usually involving fewer observations. 

## Variable

A characteristic or attribute that can change between cases or observations.

Examples:

* age
* income
* temperature
* education level

## Concept

An abstract idea researchers want to study.

Examples:

* vulnerability
* risk
* inequality

## Operationalisation

The process of converting a concept into a measurable variable. 

## Mutually exclusive

Categories arranged so that one case can belong to only one category. 

## Collectively exhaustive

Categories arranged so that every possible case fits somewhere. 

---

# Levels of Measurement

## Nominal variable

A categorical variable with no natural order or ranking.

Examples:

* religion
* nationality
* eye colour 

## Dichotomous variable

A nominal variable with only two categories.

Examples:

* yes/no
* pass/fail 

## Ordinal variable

A variable whose categories can be ranked, but where the spacing between categories is not measurable or equal.

Examples:

* low/medium/high
* strongly agree → strongly disagree 

## Interval variable

A numerical variable with equal spacing between values but no true zero point.

Example:

* temperature in °C 

## Ratio variable

A numerical variable with equal spacing and a true zero.

Examples:

* height
* weight
* income 

---

# Week 2 — Graphs, Sampling, Central Tendency, and Dispersion

## Frequency

The number of times a value or category occurs in a dataset. 

## Frequency table

A table summarising how often categories or values occur. 

## Percent

The proportion of cases multiplied by 100. 

## Valid percent

The percentage calculated after excluding missing data. 

## Cumulative percent

The running total of percentages across ordered categories. 

## Missing data

Cases where information is absent, unanswered, or unavailable. 

## Population

The full group researchers want to study. 

## Sample

A subset taken from a population for analysis. 

## Sampling error

The difference between sample results and the true population value caused by studying only part of the population. 

## Representative sample

A sample that accurately reflects the characteristics of the population. 

---

# Graphical Representation of Data

## Pie chart

A circular chart divided into slices representing category proportions. Usually used for nominal or ordinal data. 

## Bar chart

A chart using separate bars to compare frequencies or percentages across categories. 

## Histogram

A graph used for interval/ratio data where bars touch to show the distribution of continuous values. 

## Scatterplot

A graph showing the relationship between two interval/ratio variables using plotted points. 

## Box plot

A graph displaying the five-number summary:

* minimum
* Q1
* median
* Q3
* maximum 

---

# Measures of Central Tendency

## Mode

The most frequently occurring value in a distribution. 

## Mean

The arithmetic average.

$$
\bar{X} = \frac{\sum X}{N}
$$

Where:

* ($\sum X)$ = sum of all values
* (N) = number of observations 

## Median

The middle value in an ordered dataset. 

## Outlier

A value that is unusually high or low relative to the rest of the data. 

---

# Measures of Dispersion

## Dispersion

The degree to which data values are spread around a central value. 

## Range

The difference between the highest and lowest values.

$$
R = H - L
$$

Where:

* (H) = highest value
* (L) = lowest value 

## Quartiles

Values dividing ordered data into four equal sections. 

## First quartile (Q1)

The value below which 25% of the data lie. 

## Second quartile (Q2)

The median; the value below which 50% of the data lie. 

## Third quartile (Q3)

The value below which 75% of the data lie. 

## Interquartile range (IQR)

The spread of the middle 50% of the data.

$$
IQR = Q_3 - Q_1
$$



## Variance

The average squared distance from the mean.

$$
s^2 = \frac{\sum (X_i - \bar{X})^2}{N}
$$



## Standard deviation

A measure of how spread out data are around the mean.

$$
s = \sqrt{\frac{\sum (X_i - \bar{X})^2}{N}}
$$

A low standard deviation means data are tightly clustered; a high standard deviation means they are widely spread. 

---

# Week 3 — Probability and Normal Distributions

## Probability

The likelihood that an event will occur, ranging from 0 to 1. 

## Probability distribution

A table or graph showing probabilities for all possible outcomes. 

## Normal distribution

A symmetric bell-shaped distribution where mean, median, and mode are equal. 

## Gaussian distribution

Another name for the normal distribution. 

## Symmetric distribution

A distribution where the left and right sides mirror each other. 

## Unimodal distribution

A distribution with one peak. 

## Asymptotic

A curve that approaches but never touches an axis. 

## Empirical rule

The rule stating that approximately:

* 68% of values lie within 1 SD,
* 95% within 2 SD,
* 99.7% within 3 SD of the mean. 

## Confidence interval

A range within which the true population parameter is expected to lie with a specified level of confidence. 

## 95% confidence interval

An interval expected to contain the true value 95% of the time. 

## 99% confidence interval

A wider interval giving greater confidence that the true value lies within it. 

## Skewness

The degree to which a distribution is distorted away from symmetry due to outliers. 

## Positive skew

A distribution with a long tail extending to the right. 

## Negative skew

A distribution with a long tail extending to the left. 

---

# Week 4 — Hypothesis Testing, t-tests, and Correlation

## Hypothesis

A testable statement about a population or relationship.

## Null hypothesis ($(H_0$))

The hypothesis that no relationship, trend, or difference exists. 

## Alternative hypothesis ($(H_a)$)

The hypothesis that a relationship, trend, or difference does exist. 

## Hypothesis testing

The process of using sample data to decide whether evidence is strong enough to reject the null hypothesis.

## One-tailed test

A hypothesis test predicting the direction of an effect or relationship. 

## Two-tailed test

A hypothesis test predicting only that a difference exists, not its direction. 

## Statistical significance

The likelihood that a result is not due to random chance alone. 

## Significance level (($\alpha$))

The threshold probability used to decide statistical significance, commonly 0.05. 

## p-value

The probability of observing the data if the null hypothesis is true. 

## t-test

A statistical test comparing means to determine whether differences between groups are statistically significant. 

## Independent-samples t-test

A t-test comparing the means of two separate groups. 

## Degrees of freedom (df)

The number of independent values free to vary in a statistical calculation. For an independent t-test:

$$
df = n_1 + n_2 - 2
$$



## Correlation

A statistical relationship between two variables. 

## Pearson’s correlation coefficient ((r))

A measure of the strength and direction of a linear relationship between two interval/ratio variables. 

## Positive correlation

A relationship where both variables increase together.

## Negative correlation

A relationship where one variable increases while the other decreases.

## Correlation does not imply causation

Two variables moving together does not prove one causes the other. 

---

# Week 5 — Chi-square and Regression

## Cross-tabulation table

A table showing the relationship between two categorical variables. 

## Chi-square test (($\chi^2$))

A statistical test comparing observed and expected frequencies to determine whether variables are associated. 

## Observed frequency (($f_o$))

The actual number of cases observed in a category. 

## Expected frequency (($f_e$))

The number of cases expected if no relationship exists between variables. 

## Regression

A statistical method used to model and predict the relationship between variables. 

## Linear regression

Regression using a straight-line relationship between variables. 

## Dependent variable

The outcome variable being predicted.

## Independent variable

The predictor variable used to explain variation in the dependent variable.

## Regression line

The best-fitting line describing the relationship between variables. 

## Intercept ((a))

The predicted value of (Y) when (X = 0).

## Slope ((b))

The amount by which (Y) changes for each one-unit increase in (X). 








---------
---------
---------




Certainly. Here are more exam-style questions and model answers, kept fairly close to how an answer would be written in an exam.

# Levels of measurement

### 1. What are the four levels of measurement in statistics?

The four levels of measurement are **nominal, ordinal, interval, and ratio**. Nominal variables are categories with no order, ordinal variables can be ranked, interval variables have equal spacing but no true zero, and ratio variables have equal spacing plus a true zero.  

### 2. Why is nominal data different from ordinal data?

Nominal data are just categories with no natural ranking, whereas ordinal data have a clear order. The difference is that ordinal values can be arranged from low to high, but the distance between ranks is not measurable. 

### 3. What makes interval and ratio variables different from nominal and ordinal variables?

Interval and ratio variables are numerical and allow mathematical operations. Unlike nominal and ordinal data, they have equal spacing between values. Ratio variables also have a true zero point, while interval variables do not. 

### 4. Give an example of a dichotomous variable.

A dichotomous variable has only two categories, such as male/female or yes/no. It is a special type of nominal variable. 

### 5. Why does the level of measurement matter?

It matters because it determines what kind of analysis is appropriate. For example, nominal and ordinal data are usually summarised with counts and percentages, while interval and ratio data can also be analysed using means, standard deviations, t-tests, and correlation.  

### 6. Is “how worthwhile was the course?” with answers “not at all / somewhat / very” nominal, ordinal, or ratio?

It is **ordinal**, because the answers have a clear order, but the gaps between them are not equal or measurable. 

### 7. Is “0 to 100 rating of course worthwhileness” nominal, ordinal, or ratio?

It is treated as **interval/ratio** because it uses numbers on a scale and can be analysed quantitatively. 

### 8. Why is “income” usually treated as a ratio variable?

Income has a meaningful zero point: zero income means no income. That is what makes it ratio rather than interval. 

---

# Hypothesis testing and t-tests

### 9. What is hypothesis testing?

Hypothesis testing is a statistical procedure used to decide whether sample evidence is strong enough to reject a null hypothesis about a population. It is a core part of inferential statistics. 

### 10. What is the null hypothesis?

The null hypothesis ((H_0)) is the prediction that no trend, pattern, or difference exists in the data. 

### 11. What is the alternative hypothesis?

The alternative hypothesis ((H_a) or (H_1)) is the prediction that a trend, pattern, or difference does exist. 

### 12. What is a t-test?

A t-test is a statistical test used to compare the means of two groups. It is used to find out whether an observed difference is likely to be real or just due to chance. 

### 13. What is the purpose of a t-test?

Its purpose is to test whether two means are significantly different and whether the null hypothesis of equal means should be rejected. 

### 14. When would you use a t-test?

You would use a t-test when comparing:

* the mean of a sample with a population mean,
* the means of two independent samples,
* or the same sample at two different times. 

### 15. What are the two values you need in a t-test decision?

You need the **calculated t-value** and the **critical t-value**. If the calculated t-value is greater than the critical t-value, you reject the null hypothesis. 

### 16. What is the general form of the independent-samples t-test formula?

The slide gives the independent-samples t-test as a comparison of the difference between the two sample means divided by the standard error built from the two group variances and sample sizes. 

### 17. Why is the t-test significant in statistical analysis?

It gives a formal way to decide whether an observed difference between groups is likely to reflect a real population effect rather than random variation in the sample. That is why it is useful in research and hypothesis testing. 

### 18. What does a p-value tell you in a t-test?

The p-value tells you how likely it is to observe a result as extreme as the one found if the null hypothesis were true. If the p-value is less than alpha, the result is statistically significant. 

### 19. What does p < 0.05 mean?

It means there is a 5% risk of incorrectly rejecting the null hypothesis. In other words, the result is considered statistically significant at the 5% level. 

### 20. What is the difference between a one-tailed and two-tailed test?

A one-tailed test is used when the hypothesis predicts a result in one direction only. A two-tailed test is used when the hypothesis allows for a difference in either direction. 

---

# Mixed exam-style questions

### 21. Why are means not always the best summary of a dataset?

Because means are sensitive to outliers. A small number of unusually high or low values can pull the mean away from the centre of the distribution. 

### 22. Why might you use the median instead of the mean?

You would use the median when the data are skewed or contain outliers, because the median is less affected by extreme values. 

### 23. What is the difference between data and information?

Data are raw facts or observations. Information is data that has been given context so that it becomes meaningful and useful. 

### 24. What is the difference between discrete and continuous data?

Discrete data are counted and can only take certain values, while continuous data are measured and can take any value within a range. 


