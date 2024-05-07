## **Project Introduction:**

**Our project, titled "Skincare Sentiment Analysis for Dermalogica," employs Natural Language Processing (NLP) techniques to analyze a dataset of Ulta Skincare Reviews for Dermalogica products, scraped on March 27, 2023. The primary goal is to understand the overall sentiment associated with each product, providing valuable insights for product enhancement and customer satisfaction. The analysis covers aspects such as verified buyer status, review distribution, positive keywords, common skincare concerns, product types, upvotes/downvotes correlation, and a machine learning model evaluation. The project aims to empower Dermalogica in making data-driven decisions for continual product improvement.**

**Agenda:**

1. **Introduction to the Project: Highlight the significance of sentiment analysis in skincare and its impact on product development and customer engagement.**

2. **Dataset Overview: Present key attributes of the dataset, including review text, verified buyer status, and product details.**

3. **Project Goals: Outline the primary objectives, including gauging overall sentiment, identifying common skincare concerns, and exploring correlations within the data.**

4. **Buyer Verification Imbalance: Discuss the observed imbalance in buyer verification status and its implications for review authenticity.**

5. **Product Review Distribution: Present the distribution of reviews across Dermalogica products, emphasizing variations in review counts.**

6. **Positive Keywords and Skincare Concerns:** Explore positive keywords and common skincare concerns extracted from customer reviews.

7. **Product Types Mentioned: Highlight the variety of product types mentioned in the reviews and their implications for product diversification.**

8. **Upvotes and Downvotes Correlation: Discuss the correlation patterns between upvotes and downvotes, revealing insights into customer sentiment.**

9. **Initial Model Evaluation: Provide an overview of the initial sentiment analysis model, showcasing its impressive overall accuracy and challenges faced.**

# **Project Name : Ulta Skincare Reviews**

## **Problem Statement**

**Skincare brands, especially Dermalogica, heavily rely on customer reviews to understand product performance and consumer sentiments. The objective is to employ Natural Language Processing (NLP) techniques to analyze a dataset of Ulta Skincare Reviews, scraped on March 27, 2023, for Dermalogica products. The dataset encompasses various attributes, including review text, verified buyer status, and product details.**

**Our primary goal is to gauge the overall sentiment associated with each product, deciphering whether customer reviews predominantly express positivity, negativity, or neutrality. Additionally, the analysis aims to unveil common skincare issues reported by customers, highlighting areas where products excel or may require improvement.**

**Through inferential statistics, we seek to explore potential significant differences in sentiment scores among different Dermalogica products. The analysis will extend to examining correlations between sentiment scores and other variables, such as verified buyer status and upvotes/downvotes.**

**Data visualization techniques, including word clouds and bar plots, will be employed to present key words and phrases associated with positive and negative sentiments. The outcomes are expected to provide actionable insights for product enhancement, marketing strategies, and a deeper understanding of customer satisfaction in the realm of skincare products.**

## **Data Description:**

*   **Review Title: The title of the review.**

*   **Review_Text: The full text of the review.**

*   **Verified_Buyer: Whether the reviewer is a verified buyer of the product.**

*   **Review_Date: The date the review was published relative to the review scrape date.**

*   **Review_Location: The location of the reviewer.**

*   **Review_Upvotes: How many times the review was upvoted by other reviewers.**

*   **Review_Downvotes: How many times the review was downvoted by other reviewers.**

*   **Product: The name of the product the review was issued for.**

*   **Brand: The brand of the product.**

*   **Scrape Date: The date the data was pulled from the web.**

## **conclusion:**

1. **Buyer Verification:**
   **- There's a notable imbalance in buyer verification, with a higher count of non-verified buyers (approximately 3,000) compared to verified buyers (around 2,000). This suggests a substantial portion of reviews may be from non-verified sources.**

2. **Product Review Distribution:**
   **- The distribution of reviews across products varies, with the Daily Superfoliant leading with approximately 1,200 reviews. The Multi-Vitamin Thermafoliant and Hydro Masque Exfoliant show similar review counts, ranging from 800 to 900, while the Daily Microfoliant has the fewest reviews, around 400.**

3. **Positive Keywords:**
   **- Positive sentiments are expressed through words like hydrating, great, perfect, love, gentle, smooth, effective, light, clean, soft. These keywords provide insights into the positive aspects highlighted by customers in their reviews.**

4. **Skincare Concerns:**
   **- Common skincare concerns identified include dryness, sensitivity, oiliness, acne, enlarged pores, wrinkles, dark circles, and uneven skin tone. Understanding these concerns helps tailor product development and marketing strategies.**

5. **Product Types:**
   **- Reviews mention various product types such as cleanser, moisturizer, mask, scrub, serum, and SPF. This information aids in understanding customer preferences and can guide product diversification.**

6. **Upvotes and Downvotes:**
   **- A weak negative correlation between upvotes and downvotes suggests that reviews with more upvotes tend to have slightly fewer downvotes, and vice versa. Notably, reviews with 4 upvotes and 0 downvotes exhibit the strongest negative correlation, indicating positive sentiment.**

7. **Correlation Patterns:**
   **- Correlation patterns reveal that most reviews receive either 0 or 1 upvotes and downvotes. The weakest positive correlation is found in reviews with 0 upvotes and 4 downvotes, indicating potential areas for improvement in customer satisfaction.**

### **Model:**

 **In the initial model evaluation, the sentiment analysis achieved an impressive overall accuracy of 94%, showcasing proficiency in classifying instances within the dataset. However, a closer examination of class-specific performance revealed a significant imbalance in precision, recall, and F1-score between the negative and positive classes. The model exhibited a marked preference for positive instances, leading to substantial misclassifications in the negative class. After hyperparameter tuning, the overall accuracy dropped to 70%, unveiling a nuanced distribution of sentiment categories for two distinct products.The findings suggest a need for further model refinement, particularly in addressing the challenge of distinguishing between positive and negative sentiments. Continuous monitoring and iterative improvements will contribute to a more robust sentiment analysis, aligning with the intricacies of customer feedback and facilitating informed decision-making for product enhancement.**

