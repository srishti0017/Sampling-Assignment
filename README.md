# sampling-assignment
# Comparing Sampling Techniques for 5 Machine Learning Models
# Srishti Sharma
# 102003017
# 3COE3

## Introduction

This project investigates the performance of various sampling methods in creating a balanced dataset for machine learning models. The initial dataset is imbalanced, and over-sampling and under-sampling techniques are employed to balance it. Five distinct sampling methods are then applied to this balanced dataset, and the accuracies of the resulting samples are evaluated using five machine learning models.

## Sampling Techniques

The following five sampling techniques were used in this project:

1. **Simple Random Sampling:** Simple random sampling is a sampling technique used in statistics to select a random subset of individuals or items from a larger population. In this technique, each member of the population has an equal chance of being selected for the sample.

2. **Convenience Sampling:** Convenience sampling is a non-probability sampling technique in which the researcher selects study participants based on their availability and accessibility. This means that the sample is chosen because they are convenient for the researcher to access, rather than being selected randomly from the population.

3. **Stratified Sampling:** Stratified sampling is a sampling technique used to ensure that the sample includes representative proportions of subgroups within a population. The goal of stratified sampling is to reduce sampling error and ensure that the sample is more accurate and representative of the overall population.

4. **Cluster Sampling:** Cluster sampling is a sampling technique in which the population is divided into clusters or groups, and a random sample of clusters is selected for analysis. Then, all individuals within the selected clusters are included in the sample.

5. **Quota Sampling:** Quota sampling is a non-probability sampling technique where a researcher selects a sample that reflects the characteristics of a larger population in terms of specific quotas or criteria, such as age, gender, race, education level, etc. Quota sampling is a method often used in market research, opinion polling, and political research.

## Comparison Table

The table below shows the accuracies of each sampling technique on five different machine learning models. The dataset used for all models is a balanced version of the original unbalanced dataset using random over-sampling and under-sampling techniques.

| Sampling Technique | Simple Random Sampling | Convenience Sampling| Stratified Sampling| Cluster Sampling | Quota Sampling |
|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Ridge Classifier | 0.666666667 | 0.636363636 | 0.333333333 | 0.6666666666666666 | 0.9464935064935 |
| Linear Discriminant Analysis | 0.75 | 0.5 |	0.888888889 |	0.5 |	0.935064935 |
| Quadratic Discriminant Analysis | 0.833333333 |	0.818181818 |	0.333333333 |	**1.0** |	0.964935065 |
| Linear Gradient Boosting Machine | 0.333333333 |	0.272727273 |	0.333333333 |	0.333333333 |	0.933425451 |
| Gradient Boosting Classifier | 0.5 |	0.818181818 |	0.666666667 |	0.666666667 |	0.978949351 |

Based on these results, it can be concluded that Cluster Sampling performs the best on all five models. Convenience sampling
 performs the worst on all five models. The other sampling techniques have varying performance depending on the model. The model which gives the best accuracy for all 5 samples is Quota Sampling.

## Conclusion

It is recommended to use Quota sampling for this dataset, as it consistently gives the best performance across all models. However, other sampling techniques may be worth considering for different datasets or models.
 
