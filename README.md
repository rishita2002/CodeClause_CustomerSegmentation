# CodeClause_CustomerSegmentation

I did this project under CodeClause Internship as a Data Science Intern.In this project, I was support to implement a ML model that is able to perform customer segmentation based on the input dataset.I have chosen kaggle dataset for this purpose in the model.
Customer Segmentation is the subdivision of a market into discrete customer groups that share similar characteristics. Customer Segmentation can be a powerful means to identify unsatisfied customer needs. Using the above data companies can then outperform the competition by developing uniquely appealing products and services.

<b>The most common ways in which businesses segment their customer base are:</b>
<ol>
  <li>Demographic information, such as gender, age, familial and marital status, income, education, and occupation.</li>
  <li>Geographical information, which differs depending on the scope of the company. For localized businesses, this info might pertain to specific towns or counties. For larger companies, it might mean a customer’s city, state, or even country of residence.</li>
  <li>Psychographics, such as social class, lifestyle, and personality traits.</li>
  <li>Behavioral data, such as spending and consumption habits, product/service usage, and desired benefits.</li>
</ol>
<b>Advantages of Customer Segmentation</b>
<ol>
  <li>Determine appropriate product pricing.</li>
  <li>Develop customized marketing campaigns.</li>
  <li>Design an optimal distribution strategy.</li>
  <li>Choose specific product features for deployment.</li>
  <li>Prioritize new product development efforts.</li>
 </ol>
 
<b>The Challenge</b>
You are owing a supermarket mall and through membership cards, you have some basic data about your customers like Customer ID, age, gender, annual income and spending score. You want to understand the customers like who are the target customers so that the sense can be given to marketing team and plan the strategy accordingly.

<b>K Means Clustering Algorithm</b>
<ol>
  <li>Specify number of clusters K.</li>
<li>Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.</li>
<li>Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.</li>

![image](https://user-images.githubusercontent.com/78408338/198832009-7d8f7140-761f-4abd-b91c-efd6b347b75e.png)


K Means Clustering where K=3

The dataset can be downloaded from the kaggle website which can be found at https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python.

<b>Environment and tools</b>
<ol>
  <li>scikit-learn</li>
  <li>seaborn</li>
  <li>numpy</li>
  <li>pandas</li>
  <li>matplotlib</li>
