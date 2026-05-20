
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

---

If you want, I can now turn this into a cleaner exam-style revision sheet with the same week-by-week structure but even more formula-heavy and less explanatory prose.
