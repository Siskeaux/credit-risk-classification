# credit-risk-classification
Supervised Machine Learning Challenge for TCC/EdX Data Analytics Bootcamp, 2022-2023

Code written and tested with help and feedback from cohort peers. Special thanks to my peers in the inaugaral cohort of the TCC/EdX Data Analytics of Fall, 2023 for their help and advice.

## Overview of the Analysis

Using a dataset of past lending activity, a model has been built that can, to a certain degree of accuracy, determine the credit-worthiness of potential borrowers. Information used includes: loan size, interest rate, income of the borrower, debt-to-income ratio, count of accounts, "derogatory marks", sum of all debts, and loan status. 

This model provides a standardized, tailored, and consistent means of visualizing creditworthiness in order that a client (i.e., lending companies) might make risk-minimizing credit decisions.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balanced Accuracy:
    * 95.2%

  * Precision:
    * Healthy: 100%
    * High Risk: 85%

  * Recall:
    * Healthy: 99%
    * High Risk: 91%


* Machine Learning Model 2:
  * Balanced Accuracy:
    * 99.36%

  * Precision:
    * Healthy: 100%
    * High Risk: 84%

  * Recall:
    * Healthy: 99%
    * High Risk: 99%

## Summary

Overall, Model #2 appears to be the winner if one had to chose between the two. It should be mentioned that both models operate to a high degree of precision, with the averaged accuracy scores across all categories being within an acceptable margin of error of 5%-8%.

Considering the performance and margin-for-error that this model presents, I believe that this would make excellent tool for small-scale applications to aid in data-driven decision-making. Especially with the small footprint required, one could easily integrate this model into a self-service web interface to apply for credit services.
