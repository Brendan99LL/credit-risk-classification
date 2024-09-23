# credit-risk-classification
Columbia University Bootcamp Module 20 Challenge
Supervised Machine Learning

**Credit Risk Analysis Report**
<p>
The logistic regression model analyzed how accurate the predictions observed would be in distinguishing between a healthy loan, which would have a value of 0, or a high-risk loan, value of 1.  
</p>
<p>
Precision is the ratio of correctly predicted positive observations to the total predicted positive observations.  The questions that can be answered with the precision are of all the samples classified as being a high_risk loan, how many actually are considered a high-risk, and of all the samples classified as being a healthy loan, how many are actually considered health?  Based on the classification report with the test data, there is a precision value of 0.85 (85%) for predicted high-risk loans and 1.00 (100%) for predicted health loans.  If a high-risk loan was to be tested to see if it is actually high-risk, the model would predict that it is actually a high-risk about 85% of the time.  If a healthy loan was to be tested to see if it is actually healthy, the model would predict that it is actually healthy about 100% of the time.
</p>
<p>
Recall is the ratio of correctly predicted positive observations to all predicted observations for that class.  The questions that can be answered with the recall are of all the actual healthy loans, how many were correctly classified as being healthy, and of all the actual high-risk loans, how mnay were correcetly classified as being high-risk?  With the recall, there should be very little room for error as it can cause more damage to companies if an actual positive result is predicted as a predicted negative.  In this case, when analyzing just the healthy loans, these loans would be considered the actual positive.  A value of approximately 99% recall for predicting a healthy loan would be beneficial for determining if the given loan in question would be a healthy or high-risk loan.  With this almost perfect detection for a healthy loan, this model can be considered trustworthy to determine the healthy loans and help customers secure them.
</p>
<p>
When analyzine the high-risk loans, the recall is shown to be about 91%, so in this case, receiving a high-risk would be considered the actual positive result and the remaining 9% would be the predicted negative of the loan possibly being healthy.  This piece of the model may be dangerous for companies as a higher recall value should what companies strive to achieve for their models to properly help their customers.  As mentioned, ther eis a higher chance of a healthy loan being identified as a healthy loan, with just about 1% chance of a healthy loan being identified as a high-risk loan.  If a healthy loan is identified to be a high-risk loan, this may make the lending company lose some money for one loan, but this means that the customer was saved from possibly facing a loss of money.  There might not be as much profit, if any, from the customer if they believe a healthy loan is a high-risk loan, but this can lead to the customer coming back for another possibly health loan, helping the lending company earn a profit while preventing a loss for the customer.  
</p>
<p>
The big issue would arise if a high-risk loan has been predicted to be a healthy loan.  A high-risk loan being classified as a healthy loan could cost the customer more money.  There is virtually no, or very little, risk if a healthy loan is predicted to be a high-risk loan.  With about 91% recall for predicting a high-risk loan accurately, the remaining 9% that a high-risk loan would be classified as healthy is more dangerous for the borrower, and possibly the lender.  Even though there is a high chance that the high-risk loan will be classified correctly, the 9% change that it will be classified incorrectly seems too high for the risk involved.
</p>
