# US-Health-Insurance-Data

## US Health Insurance Dataset Hypothesis Testing

In this project, we will be working with the US Health Insurance Dataset from Kaggle to answer three hypothesis questions using hypothesis testing:

- Q1. Do smokers have higher insurance charges than non-smokers?
- Q2. Are men more likely to smoke than women?
- Q3. Do different regions have different charges, on average?

### Hypothesis Statements

For each question, we have defined the Null Hypothesis (H0) and Alternative Hypothesis (H1) as follows:

- Q1. H0: Smokers and non-smokers have the same average insurance charges. H1: Smokers have higher average insurance charges than non-smokers.
- Q2. H0: The proportion of male smokers is equal to the proportion of female smokers. H1: The proportion of male smokers is different from the proportion of female smokers.
- Q3. H0: The average insurance charges for all regions are equal. H1: At least one region has a different average insurance charge than the others.

### Test Selection and Assumptions

We will select the appropriate test based on the data type and number of samples. We will also test the assumptions of each test to ensure its validity. If the assumptions are not met, we will use an alternative test. 

### Results Interpretation

After executing the selected test, we will interpret our p-value and reject or fail to reject our null hypothesis based on a significance level of 0.05. We will also show a supporting visualization that helps display the result of our hypothesis testing.

### Do smokers have higher insurance charges than non-smokers?
![download (3)](https://github.com/farisassallami/US-Health-Insurance-Data/assets/111199631/9c5d583e-cca0-4ac7-a3ab-07da74298c42)

We used 2-Sample T-test for this statement:
- P-Value .025 < .05, We reject the null hypothesis.
- There is a significant difference in insurance charges between the 2 groups.  Smokers have higher charges than non-smokers.

### Are men more likely to smoke than women?
![download (4)](https://github.com/farisassallami/US-Health-Insurance-Data/assets/111199631/2908695a-3659-4f1e-9f53-5f5935da0725)

We used Chi-Squared test for this statement:
- P-Value .006 < .05, We reject the null hypothesis.
- There is a significant difference in the gender that is more likely to smoke than the other gender.
- According to the countplot above, we can see that Males are more likely to smoke than females

### Do different regions have different charges, on average?
![download (5)](https://github.com/farisassallami/US-Health-Insurance-Data/assets/111199631/35a8215f-70d2-479d-b310-a299c0cc27c6)

- We used ANOVA test for this statement:
- P-Value: .19 > .05 , We do not reject the null hypothesis. 
- We conclude that the charges are not significantly different between regions.

