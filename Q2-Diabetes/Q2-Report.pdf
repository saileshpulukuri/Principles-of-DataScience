Findings (Q2 – Diabetes Dataset Analysis)

Q2(a) – Glucose: Sample (n=25) vs Population

After cleaning invalid zero values in the Glucose column, I took a random sample of 25 observations.
The sample mean Glucose level came out slightly lower than the population mean, and the maximum Glucose value in the sample was also a bit lower than the highest value in the entire dataset.

This makes sense because a small random sample does not always capture extreme values.
However, the sample still gives a reasonable estimate of the population trend, showing that the sample mean is fairly close to the true population mean.
The comparison chart clearly shows this small gap between the sample and population values.

Q2(b) – 98th Percentile of BMI: Sample vs Population

For the BMI values, I used the same sample indices (after dropping rows with missing BMI).
The 98th percentile of the sample BMI was slightly lower than the population’s 98th percentile.

This difference is expected because the top 2% of values are very sensitive to sample size.
Since the full population has 768 records and the sample has only around 24 valid BMI entries, the population includes more extreme high-BMI values.
The comparison bar chart shows that both values follow the same trend but the population has a higher extreme percentile.

Q2(c) – Bootstrap Analysis for BloodPressure

To understand how sample statistics behave across repeated sampling, I generated 500 bootstrap samples, each of size 150.
For each sample, I calculated the mean, standard deviation, and 98th percentile of BloodPressure.

The distribution plots show that:

The bootstrap means are centered very close to the population mean.
This confirms that the bootstrap averages are good estimates of the true population mean.

The bootstrap standard deviations are also close to the population SD, although the spread is a bit wider.
This is expected because SD is more sensitive to sample variation.

The bootstrap 98th percentiles vary more widely than the means but still cluster around the population’s 98th percentile.
Percentiles naturally fluctuate more because they depend on extreme values in each sample.

Overall, the bootstrap results demonstrate that repeated sampling with replacement produces statistics that are consistent with the population.
The charts also show how sampling variability affects each metric, especially extreme percentiles.