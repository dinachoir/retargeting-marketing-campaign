# Retargeting Marketing Campaign

## Work Environment

**Tool** : Jupyter Notebook \
**Programming Language** : Python 3 \
**Visualization** : Matplotlib, Seaborn \
**Dataset** : [Marketing Campaign Data]() 

## Project Background
An ecommerce company, Shopyy has a problem in term of the low conversion rate of marketing campaign. This problem drive a waste of marketing campaign targeting cost, since it is ineffective. As a data science team, we were asked to analyze the customer personality behaviours so that we can target the right customers to transact on the company's platform.

This project aims to reduce the cost of marketing campaign targeting by 20%, and increase gross profit by 30%. By processing historical marketing campaign data, we developed cluster prediction model to guide business decisions on retargeting marketing campaign.

The result of this project is that 

A company can develop rapidly when it knows its customer personality behavior, so it can provide better services and benefits to customers who have the potential to become loyal customers.

## Dataset Overview
The dataset contains 2,240 unique observations with 29 features in various data types. Each row represent customers' demographics, purchase history, and respond to marketing campaign records in a year period. There are 24 missing values in `income` feature.

## Preprocessing
  1. Feature Engineering
  2. Handling Missing Values
  3. Handling Duplicated Data
  4. Feature Selection
  5. Handling Outliers
  6. Feature Transformation

## Modeling
We leveraged k-means clustering algorithm with 5 optimum number of clusters to segment the customer personality behaviours. The silhoutte score is used to validate the clusters.

**Customer clusters:**
  1. High value sure things
  2. High value sleeping dogs
  3. High value persuadables
  4. Low value sleeping dogs
  5. Low value loss causes
  
## Recommendations
  1. **Targeting marketing campaign to the High value Persuadables segment**. Marketing campaign can impulse these customers to purchase items on a whim. Flash sales and limited-time offers are two prevalent and effective impulse triggers. Brand campaigns that guarantee the lowest price on certain days and offer seasonal discounts are a few of the mainstream triggers.
  2. **Targeting a small-amount marketing campaign** frequently and apply a minimum basket size to the **Low value loss causes** segment.
  3. **Apply a retention strategy to the High value sure things** segment. Appreciate these customers for their loyalty by rewarding them with loyalty badges and some exclusive privileges. Also keep providing good customer service and delivering great value.
  4. **Prioritize High value sleeping dogs** segment since this segment has the highest total spending, and has the second largest number of customers. Do not send them marketing campaign. Tailoring customer experience using product personalization instead.
  5. **Apply a minimum basket size to the Low value sleeping dogs** segment. Do not send them marketing campaign. Improve customer experience using cross selling and up selling recommendations instead.
