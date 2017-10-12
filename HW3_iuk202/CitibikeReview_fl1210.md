### a. verify that their Null and alternative hypotheses are formulated correctly

The original hypothesises:

null hypothesis: the average trip duration of 'customers' is the same or shorter than the average trip duration of 'subscribers' with a significance level of alpha = 0.05

alternative hypothesis: the average trip duration of 'customers' is greater than the average trip duration of 'subscribers' with a significance level of alpha = 0.05

I feel that the hypotheses are formulated correctly.The purpose is to test the difference between means.

### b. verify that the data supports the project: i.e. if the a data has the appropriate features (variables) to answer the question, and if the data was properly pre-processed to extract the needed values (there is some flexibility here since the test was not chosen yet)

In the code, the averaged duration during a month is calculated.In order to examine the difference between two sample means, sample variances and sample sizes should also be listed.


### c. chose an appropriate test to test H0 given the type of data, and the question asked. You can refer to the flowchart of statistical tests for this in the slides, or here, or Statistics in a Nutshell.

To examine the difference between means, I suggest to use two-sample t test.Using sample means, sample sizes and sample variances to calculate test statistic and then compare to the threshold chosen.
