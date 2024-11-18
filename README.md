**JUMIA-PRODUCTS-RECOMMENDATION-AND-PRODUCT-REVIEW-SYSTEM**

****************************************************************************************************************

![download 3](https://github.com/user-attachments/assets/9d55becf-06b2-49de-b100-af748ba00a2f)


**Overview**

The growth of e-commerce in Kenya has been exponential, with platforms like Jumia attracting large numbers of users. However, users frequently encounter challenges in locating relevant products due to expansive and sometimes disorganized product catalogs. Moreover, the limited use of recommendations and unreliable review systems further complicate the shopping experience, leading to reduced user satisfaction and lower conversion rates. To address these issues, we propose a recommendation and sentiment analysis system that leverages interaction history and user feedback. This system aims to provide more relevant recommendations and insights from customer sentiments, enabling Jumia to better serve its users and enhance its retail offerings.

**Problem Statement**

The problem of finding relevant products on Jumia’s extensive catalog significantly affects customer satisfaction and conversion rates. Current limitations include:

Inadequate product recommendations based on user behavior, which leads to a lack of personalization.
An unreliable rating and review system, leaving customers with limited insights into product quality.
Limited retailer insights into customer sentiment, hindering their ability to refine offerings and optimize marketing strategies.
These issues reduce user satisfaction, decrease sales, and limit the potential for enhanced customer-retailer relationships on Jumia.

**Objectives**

Develop a Recommendation System:
Create an intelligent recommendation engine that uses customer interaction history, preferences, and similar behavior patterns to provide relevant product recommendations.

Implement Sentiment Analysis:
Extract sentiments from customer reviews to offer meaningful feedback, categorizing it as positive, negative, or neutral. This feedback will help refine recommendations and improve customer trust in the platform.

Enhance User Experience:
Improve customer satisfaction by reducing the time and effort needed to find relevant products, potentially increasing conversion rates.

Provide Insightful Retailer Analytics:
Equip sellers with sentiment analysis reports and recommendation patterns to refine product and marketing offerings based on customer preferences.

Support Kenyan E-commerce Growth:
Contribute to developing the e-commerce sector in Kenya by addressing key pain points in product discoverability and review reliability on Jumia.
 
**Data**

The data was scraped from the Jumia website (https://www.jumia.co.ke/) and can be accessed (input github link). The dataset contains 11615 rows and 20 columns.  The Jumia policy for data collection limited the data scraping.

**Data Preparation**

The raw data had a lot of missing values, 49 duplicates, and unnecessary features such as scraping links.  Data cleaning was done by removing duplicates, imputing the missing values with measures of central tendency, and extracting information embedded in some features.  The cleaned data set had 13 columns and 8375 columns. 

**EDA**

Frequency distributions of prices, categories, and subcategories were plotted.  relationship of features about customers such as average rating against the category was visualised.
Concerning sentiment analysis,  A sentiment column with categories; positive, neutral, and negative was mapped.  Distribution  plots of the sentiment and their relationship to ratings  are shown. 
Review titles and review columns are cleaned using natural language processing. 
Wordclouds for the sentiment categories have been shown, For the positive sentiment, 'good', 'nice', and 'love', words appeared more often in the positive reviews. i Interesting that the word 'product' appeared often too!

**Modelling**
After training the dataset, BOW SVM, TFIDF, Naive Bayes, andom Forest were tested. Random Forest performed best, with an accuracy level of 87% compared to BOW SVM, TFIDF,Naive Bayes which had 82%, 85%, 81%, 83% accuracies respectively. 

**Recommendation system**
Unpersonalised recommendation:  products  and categories with the highest weighted ratings were successfully recommended. 
Item-based Recommendation: products that were similar to what the customer purchased were successfully  recommended. 
Content-based filtering: Based on metadata, Items  that had been previously liked were successfully  recommended. 

**Limitations**
1. Data scraping- the scarping site restricted scarping to 10 reviews prt product
2. Lack of unique identifiers.

**Conclusion**

This project successfully developed and evaluated a dual-purposed system integrating product recommendation and sentiment analysis to address key challenges in Kenya's e-commerce landscape. It focus on user interaction, It provides actionable insights that enhance user satisfaction and retailer efficiency.

**Collaborators**

[Joakim Tipape](https://github.com/joakimTI)

[Brian Ouko](https://github.com/WellBrian)

[Hanan Dayah](https://github.com/Hanan-Dayah)

[Dorothy Chomba](https://github.com/Messagefordorothy)

[Zenah Biwott](https://github.com/Biwott54)

