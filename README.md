# E-commerce-Marketing-Analysis
 Customer Clustering and Promotion Response Analysis
 
## Intention

To assist the marketing team in running well targeted camppaigns customized to customer's purchasing behavior.

## Data
**Raw data file**
- marketing_campaigns.csv

**Interim Data**
- Customer_Data_Modeling.csv
- Kmeans_Labeled_Customer_Data.csv
- campaign_data_w_predictions.csv

## Process Overview

### Data Cleaning and EDA
- Null values treatment and Outlier check
- Uni-variate and bi-variate analysis

### Customer Clustering Analysis
- Using PCA for reducing the dimensionality and handle the collinear variables
- K-Means clustering to segment the customers based on their demographic and purchasing behavior data.

### Promotion Response Analysis
- Classifying the customers' response (accepted:1, not_accepted:0) to the promotion campaign.
- Built a Support Vector Classifier with 'rbf' kernel (a variation of gaussian kernel)
- Use sklearn's GridSearchCV function to search for optimal parameters.

### Downstream Calculations
- Assessing promotion response activity's value using the campaign financials provided.
- Calculated incremental revenue and profits, possible through using this model.


## Limitations
- No access to population data.
- Lack of knowledge of company background.

## Conclusion
Above models and activities make it possible for well customized and targeted market campaigns, thus incrrasing customer affinity and lifetime value. Although, with access to population data and with more knowledge on company's marketing activities, financials etc., better hypothesis and analysis could be formulated. 
