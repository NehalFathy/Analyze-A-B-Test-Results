# Analyze A/B Test-Results

# Project Overview: 
A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these. For this project, you will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Your goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.You will be provided a dataset reflecting data collected from an experiment. Use statistical techniques to answer questions about the data and report your conclusions and recommendations in a report.

# Project Details
The Project was divided into Three Parts i.e. :

## Part I - Probability
Statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.

## Part II - A/B Test
Next, hypothesis testing was conducted assuming the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%. The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

## Part III - Regression
Logistic regression was then performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.

# Project Motivation
This is an Udacity Nanodegree project.I was interested in using A/B Test Data to better understand:

- What do the z-score and p-value you computed in the previous question mean for the conversion rates of the old and new pages?
- Though you have now looked at the individual factors of country and page on conversion, we would now like to look at an interaction between page and country to see if there significant effects on conversion.

# Results
Based on the statistical tests I used, the Z-test, logistic regression model, and actual difference observed, the results have shown that the new and old page have an approximately equal chance of converting users. We fail to reject the null hypothesis. I recommend to the e-commerce company to keep the old page. This will save time and money on creating a new page.
