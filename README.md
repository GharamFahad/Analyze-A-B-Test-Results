# Analyze-A-B-Test-Results
A/B tests are very commonly performed by data analysts and data scientists. For this project, you will be working to understand the results of an A/B test run by an e-commerce website. Your goal is to work through this notebook to help the company understand if they should:

Implement the new webpage,
Keep the old webpage, or
Perhaps run the experiment longer to make their decision.
Findings.
First " What is the probability of an individual converting regardless of the page they receive"
Then,"Null Hypothesis  𝐻0  Testing"
- we calculate the p-value to getting the probability of the null is true but because the p-value is larger we canot reject the null hypothesis and should continue using the old website .
- The p-value give the 90% probability to get the observed difference given that the null is true. so we don't have enough evidence that the new page leads to more conversions and we should keep the old page.
- The probability of conversion in the treatment group lower than in the control group, so until now there is no evidence to say the new page more efficiency .

Finalley,
Based on the tests we used, the Z-test, logistic regression model, and actual difference observed, the result shown that the new and old page have an approximately equal chance of converting users.So, at the end of this test the company
