# Sentiment-Analysis

Objective:

The project focuses on the sentiment analysis of customer reviews on eBay and Amazon. By examining the sentiments expressed in these reviews, the project aims to provide actionable insights into product quality, customer satisfaction, and overall customer experience. These insights are intended to help businesses understand consumer preferences and improve their marketing strategies, customer service, and product offerings.

Techniques Used:

To achieve these objectives, the project utilized a combination of Natural Language Processing (NLP), Machine Learning (ML), and Deep Learning (DL) models. The analytical process involved:

- Web Scraping: Automated extraction of customer reviews from Trust Pilot using Python and the BeautifulSoup library.

- Feature Extraction: Employed Text Feature Extraction techniques such as Term Frequency-Inverse Document Frequency (TF-IDF) and Bag of Words (BOW). For deep learning models, GloVe embeddings were used to capture semantic meanings of words.

- Model Implementation: A range of models were used to analyze the sentiments of the reviews, including Logistic Regression, Support Vector Machines (SVM), Bidirectional Long Short-Term Memory (Bi-LSTM), Convolutional Neural Networks (CNN), and Bidirectional Encoder Representations from Transformers (BERT).

Methodology:

- Data Collection: Reviews for eBay from 2017 to 2023 and for Amazon from 2020 to 2023 were collected. The models were trained on historical reviews and tested on the most recent 2023 data to simulate real-world application and validate the models' effectiveness over time.

- Model Training and Testing: Each model was trained and tested with a focus on accurately classifying the sentiment as positive or negative. Special attention was given to the performance of the models in minimizing false positives—negative reviews incorrectly predicted as positive—to enhance reliability.

Key Findings:

1.  Model Performance: Among the tested models, the BERT model exhibited superior performance by accurately classifying sentiments with high recall scores—75% for eBay and 84% for Amazon. This indicates a strong ability to correctly identify positive sentiments, which is crucial for maintaining customer relations and brand reputation.

2.  Importance of Customer Reviews: The analysis highlighted the significant impact of customer reviews on purchasing decisions and trust in e-commerce platforms. Insights from the sentiment analysis can help businesses prioritize areas for improvement and strategically adjust their practices to better meet customer expectations.

Recommendations:

- Enhanced Competitive Analysis: Utilize sentiment analysis to continually assess and compare customer satisfaction levels across different platforms, helping businesses stay competitive and responsive to market changes.

- Product Development and Marketing: Apply the insights from sentiment analysis to inform product development and create targeted marketing campaigns that resonate with customer needs and preferences.

- Customer Service Enhancement: Leverage detailed sentiment data to improve customer service strategies, addressing common concerns and enhancing customer interactions to boost satisfaction and loyalty.

By deploying advanced NLP and ML techniques to dissect and understand customer sentiments comprehensively, this project not only aids in tactical business decision-making but also enhances strategic planning across multiple domains of e-commerce operations.
