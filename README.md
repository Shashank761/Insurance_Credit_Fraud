# Insurance_Credit_Fraud
Our client is an Insurance company and they need our help in building a model to predict whether the policyholder (customer) will pay next premium on time or not based on their previous transactions.

Building a model to predict whether a customer would make the premium payment can be extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers who are less likely to pay and convince them to continue making timely payment.

 

Now, in order to predict, whether the customer would pay the next premium or not, you have information about past premium payment history for the policyholders along with their demographics (age, monthly income, area type) and sourcing channel etc.

 

Data

 train.csv
 It contains training data for customers along with premium payment status (target)

 Variable                                             Definition
 id                                                   Unique ID of the policy
 perc_premium_paid_by_cash_credit	                    Percentage of premium amount paid by cash or credit card
 age_in_days	                                        Age in days of policy holder
 Income	                                              Monthly Income of policy holder
 Count_3-6_months_late	                              No of premiums late by 3 to 6 months
 Count_6-12_months_late	                              No  of premiums late by 6 to 12 months
 Count_more_than_12_months_late	                      No of premiums late by more than 12 months
 application_underwriting_score	                      Underwriting Score of the applicant at the time of application (No applications under the score of 90 are insured)
 no_of_premiums_paid	                                Total premiums paid on time till now
 sourcing_channel	                                    Sourcing channel for application
 residence_area_type	                                Area type of Residence (Urban/Rural)
 target	                                              1 - premium paid on time, 0 - otherwise
 
 
 
 test.csv
 Test file contains policies for which participants need to submit the probability of premium being paid on time

 Variable	Definition
 id	                                                  Unique ID of the policy
 perc_premium_paid_by_cash_credit	                    Percentage of premium amount paid by cash or credit card
 age_in_days	                                        Age in days of policy holder
 Income	                                              Monthly Income of policy holder
 Count_3-6_months_late	                              No of premiums late by 3 to 6 months
 Count_6-12_months_late	                              No  of premiums late by 6 to 12 months
 Count_more_than_12_months_late	                      No of premiums late by more than 12 months
 application_underwriting_score	                      Underwriting Score of the applicant at the time of application (No applications under the score of 90 are insured)
 no_of_premiums_paid	                                Total premiums paid on time till now
 sourcing_channel	                                    Sourcing channel for application
 residence_area_type	                                Area type of Residence (Urban/Rural)
 
 
 sample_submission.csv
 Please submit as per the given sample submission format only  

 Variable

 Definition

 id	                                        Unique ID for the policy 
 target	                                    Predicted Probability for target
 

 

 

 



