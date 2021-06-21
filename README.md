## Travel Insurance Prediction -Hackathon

<a href="https://colab.research.google.com/github/its51/Travel-Insurance-Prediction---Hackathon/blob/master/Final_Travel_Insurance_Claim_Team_Kernel_Matters_edit.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


> ## Problem Description

Insurance companies take risks over customers. Risk management is a very important aspect of the insurance industry. Insurers consider every quantifiable factor to develop profiles of high and low insurance risks.

Insurers collect vast amounts of information about policyholders and analyze the data.

Travel Insurance Claim Prediction.

During travel, there are a lot of risk factors - loss of baggage, airline cancellations, health issues etc. The potential customers are travellers who want to insure themselves against travel-related risks. 

They have different product offerings like 1-way travel insurance, 2-way insurance, insurance against cancellations and so on. 

They receive thousands of claims spread across different products.

Wrongly denying a genuine claim could lead to lawsuits against the company and approving the wrong claim would lead to a loss.

Automatically predicting the claims could lead to a lot of benefits and solve some other supplementary problems too.

I Analyzed the available data and predict whether to sanction the insurance or not.

> ## Dataset Description

The training dataset consists of data corresponding to 52310 customers and the test dataset consists of 22421 customers.
Following are the features of the dataset

|Variable|Description|
|--------:|:------------|
| (Claim)|Target: Claim Status|
|(Agency)|Name of agency  |
|(Agency.Type)|Type of travel insurance agencies  |
|(Distribution.Channel)|Distribution channel of travel insurance agencies  |
|(Product.Name)|Name of the travel insurance products  |
|(Duration)|Duration of travel  |
|(Destination)|Destination of travel  |
| (Net.Sales)|Amount of sales of travel insurance policies |
| (Commission)|The commission received for travel insurance agency |
|(Age)|Age of insured  |
|(ID)|The identification record of every observation |

> ## Evaluation Metric
The evaluation metric is precision_score for classification model 
