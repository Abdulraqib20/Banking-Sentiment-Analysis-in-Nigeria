# Banking-Sentiment-Analysis-in-Nigeria

## Description
The aim of this project is to perform sentiment analysis on Twitter data related to customer satisfaction with Nigerian banks, in order to gain insights into customer opinions and experiences and identify areas for improvement in the banking industry. By collecting and analyzing tweets mentioning Nigerian banks, we aim to understand the sentiments expressed by customers, whether positive or negative, towards various banking services and experiences. Through natural language processing techniques and the application of XGBoost, Support Vector Machine Classifier models, BERT and KerasNLP , we seek to accurately classify these sentiments and uncover valuable patterns and trends. The findings from this analysis can provide valuable business intelligence to Nigerian banks, enabling them to make data-driven decisions, optimize customer service strategies, and address customer concerns more effectively.

## Key Features
- Introduction: Overview of the project.
- Data Collection: Collected data from Twitter by querying the Twitter API.
- Data Cleaning: Clean and preprocess the collected data for analysis.
- Data Preprocessing: Perform text preprocessing techniques such as removal of URLs, hashtags, mentions and special characters and  tokenization, stop word removal, and stemming/lemmatization.
- Feature Engineering: Additional features such as character count and word count were considered, and new features were engineered from the dataset, such as time, hour, weekday, month, and year, to provide supplementary insights into the tweet structure and length.
- Sentiment Scoring: Calculating the sentiment scores and classifying sentiments into two distinct classes (positive and negative).
- Analyzing keywords and phrases used in the dataset.
- Exploratory Data Analysis: Conducted comprehensive EDA on the pre-processed data to gain valuable insights into sentiment distribution trends, patterns, and potential anomalies. This analysis will provide a deeper understanding of how customers perceive Nigerian banks on Twitter.
- Model Development: Building robust ML models using XGBoost and Support Vector Machine (SVM) for predicting sentiments and also performing hyperparameter tuning to optimize model performance. For the modelling, the preprocessed tweets were transformed into numerical features. The `Term Frequency-Inverse Document Frequency (TF-IDF)` vectorizer was used to convert the text data into a numerical matrix, effectively representing the significance of words in tweets relative to the entire dataset.
- Model Testing and Evaluation: Evaluating the models using various classification metrics and also accesing it's efficiency and robustness by testing it on new unseen data. Accuracy scores served as a primary metric to gauge the overall effectiveness of the models in classifying sentiments. Cross-validation was employed to assess the model's generalization performance and reduce the risk of overfitting. In addition, confusion matrices were analyzed to gain deeper insights into true positive, true negative, false positive, and false negative predictions, providing a detailed assessment of model performance. The goal is to ensure the model's optimal performance in correctly classifying sentiments.
- Text Classification With BERT and KerasNLP: The evaluation process also harnessed the capabilities of KerasNLP and BERT, enabling advanced analysis of natural language processing and deep learning outcomes. Using BERT, a popular Masked Language Model which is bidirectional (it has access to the words left and right) to build a the text classification model and also KerasNLP, which provides a simple Keras API for training and finetuning NLP models to classify the sentiments.
- Conclusion: This sentiment analysis project has been an enlightening exploration into the realm of natural language processing and machine learning. The project used advanced models like XGBoost, BERT, and KerasNLP to analyze customer sentiment on Twitter towards Nigerian banks. The models were able to accurately categorize sentiments as positive or negative, with impressive accuracy scores and robust evaluation metrics. The project's findings suggest that sentiment analysis has great potential for the banking industry 

## Installation
Clone the repository: `git clone https://github.com/Abdulraqib20/Banking-Sentiment-Analysis-in-Nigeria.git`

## Results and Findings
The sentiment analysis of Nigerian bank customers' tweets has yielded valuable insights and recommendations for improvement. The sentiment distribution indicates a majority of `Negative` tweets at 57.6% with the remaining 42.4% of the tweets `Positive` sentiments.
From the analysis, it was seen that the most frequently used words are “teller” and “forex”. The use of these words may reflect broader trends in the Nigerian banking industry. For example, customers might be discussing common issues or topics related to tellers and forex that affect multiple banks.	The prevalence of these words might also indicate that Nigerian banks actively engage with their customers on Twitter regarding teller services and forex transactions. This engagement could be in response to customer inquiries, feedback, or complaints related to these specific banking services. It was also observed that the highest number of tweets occurred on Saturday. Saturdays are typically part of the weekend when people have more free time and may be more active on Twitter. As a result, customers may take the opportunity to share their experiences and opinions about Nigerian banks, leading to an increase in the number of tweets on Saturdays. First Bank stands out as having a vast majority of positive sentiments. This indicates that a significant number of customers are expressing positive opinions or experiences related to this bank. It suggests that the bank has been successful in meeting customer expectations and providing satisfactory services. UBA and Access also have mostly positive sentiments. GT Bank stands out as having mostly negative sentiments. This suggests that a notable number of customers are expressing negative opinions or experiences related to this bank. The sentiment distribution varies significantly across the analyzed banks, indicating that customer experiences and opinions differ from one bank to another. Understanding these variations is crucial for each bank to tailor their strategies and services to meet customer needs effectively. The machine learning and deep learning models also gave impressive accuracy scores with all of them greater than 85% showcasing strong predictive capabilities to classify sentiments accurately. 

## Contributing
Contributions are welcome! If you would like to contribute to the project, feel free to reach out to me. Together, we can enhance the analysis and make an impact in opinion mining in banking.

## Contact
For any questions or inquiries, please contact abdulraqibshakir03@gmail.com.
