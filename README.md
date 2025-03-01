# Diet-Labels-and-Lifestyle-A-NHANES-Analysis

This project uses NHANES data to explore the relationships between gender, nutrition habits, BMI, income, and health behaviors, focusing on protein consumption, nutrition label usage, and drinking patterns.

# Introduction



# Data Source



# Data preprocessing 



# Results Summary
## Analysis 1: Protein Consumption Among Genders

This analysis aimed to determine whether males consume significantly more protein than females using a bootstrapped two-sample t-test. By performing 10,000 bootstrap resamples, we found a statistically significant mean difference of 20.34 grams (SE = 0.90), with a 95% confidence interval ranging from 18.58g to 22.08g. The bootstrap p-value (< 0.0001) strongly supports this difference, confirming that males have a consistently higher protein intake than females. However, an important limitation is that protein intake was measured for only a single day, which may not reflect habitual dietary patterns. Future research should incorporate multiple days of dietary assessment to obtain a more accurate estimate of long-term protein consumption differences between genders.

## Analysis 2: BMI and Nutrition Label Reading Habits 

This analysis aimed to determine whether there was a difference in the BMI of individuals based on how often they read the nutrition label of food. Our analysis found statistically significant differences in BMI based on nutrition label reading frequency (Kruskal-Wallis: χ^2^ = 37.175, p < 0.0001). Dunn’s post hoc test revealed that BMI differed significantly between the Never vs. Sometimes (p < 0.0001) and Always vs. Sometimes (p = 0.0045) groups, suggesting that individuals who sometimes read nutrition labels have a different median BMI than those who never or always read them. Other comparisons were not statistically significant. These findings suggest a non-linear relationship between label reading habits and BMI, warranting further investigation into potential behavioral and socioeconomic influences.

## Analysis 3: 

## Analysis 4: 

# Future Work


# Source

