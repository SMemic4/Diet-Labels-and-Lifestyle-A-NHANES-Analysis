# Diet-Labels-and-Lifestyle-A-NHANES-Analysis

This project uses NHANES data to explore the relationships between gender, nutrition habits, BMI, income, and health behaviors, focusing on protein consumption, nutrition label usage, and drinking patterns.

# Introduction



# Data Source



# Data preprocessing 



# Results Summary
## Analysis 1: Protein Consumption Among Genders

This analysis aimed to determine whether males consume significantly more protein than females using a bootstrapped two-sample t-test. By performing 10,000 bootstrap resamples, we found a statistically significant mean difference of 20.34 grams (SE = 0.90), with a 95% confidence interval ranging from 18.58g to 22.08g. The bootstrap p-value (< 0.0001) strongly supports this difference, confirming that males have a consistently higher protein intake than females. However, an important limitation is that protein intake was measured for only a single day, which may not reflect habitual dietary patterns. Future research should incorporate multiple days of dietary assessment to obtain a more accurate estimate of long-term protein consumption differences between genders.

## Analysis 2: BMI and Nutrition Label Reading Habits 

This analysis aimed to determine whether there was a difference in the BMI of individuals based on how often they read the nutrition label of food. Our analysis found statistically significant differences in BMI based on nutrition label reading frequency (Kruskal-Wallis: χ² = 37.175, p < 0.0001). Dunn’s post hoc test revealed that BMI differed significantly between the Never vs. Sometimes (p < 0.0001) and Always vs. Sometimes (p = 0.0045) groups, suggesting that individuals who sometimes read nutrition labels have a different median BMI than those who never or always read them. Other comparisons were not statistically significant. These findings suggest a non-linear relationship between label reading habits and BMI, warranting further investigation into potential behavioral and socioeconomic influences.

## Analysis 3: Drinking Habitis between Genders

This analysis aimed to determined whether there was an association between gender and self-reported past heavy drinking. By performing a 2x2 analysis with Bayesian augmentation, our analysis found a significant association between gender and self-reported past heavy drinking (exact p-value < 0.0001). Males were 1.61 times more likely to report a history of consuming four or five alcoholic drinks almost every day compared to females (RR: 1.61, 95% CI: 1.537, 1.682). The odds ratio (OR) was 3.10 (95% CI: 2.710, 3.537), indicating that males had over three times higher odds of reporting past heavy drinking than females. The absolute probability difference between genders was 26.8% (95% CI: 24.0%, 29.6%), further highlighting this disparity. 

## Analysis 4: 

This analysis aimed to determined whether there was an association between education level and how often an individual reads nutrition labels.  The Pearson's chi-squared test provided strong evidence of an association between educational attainment and nutrition label reading frequency. The association plot further highlighted key differences, showing that college graduates were more likely than expected to read nutrition labels frequently, particularly in the "always" and "most of the time" categories, while those with lower educational attainment were less likely to do so. Individuals with less than a 9th-grade education had a significantly higher-than-expected frequency in the "never" and "rarely" categories, indicating a trend where higher education levels correlate with more frequent nutrition label usage. These findings suggest that education may play a role in shaping consumer health behaviors, particularly in making informed dietary choices.

# Future Work


# Source

