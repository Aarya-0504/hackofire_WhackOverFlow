# hackofire_WhackOverFlow
## For Sentiment Analysis
-Can rank complaints to be resolved on the basis of urgency by ranking complaints according to negative sentiment scores.
-Can be used for analytics in admin dashboard to analyze sentiments of feedback after complaint resolution.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Data Collection: Obtain customer feedback data from sources like Kaggle, ensuring it includes columns such as "Reviews" and "BankName."

Data Preprocessing: Clean and preprocess the text data by removing special characters, punctuation, and stopwords. Tokenize the text data for further analysis.

Sentiment Analysis with ROBERTA:

Use ROBERTA to perform sentiment analysis on the preprocessed text data.
Calculate sentiment scores for each feedback, including "roberta_neg," "roberta_neu," and "roberta_pos."
Labeling Based on Scores:

Assign labels based on the sentiment scores obtained. For example:
If "roberta_pos" > "roberta_neg" and "roberta_pos" > "roberta_neu," label the feedback as positive.
If "roberta_neg" > "roberta_pos" and "roberta_neg" > "roberta_neu," label the feedback as negative.
Otherwise, label the feedback as neutral.
DataFrame with Scores and Labels:

Create a DataFrame containing columns such as "roberta_neg," "roberta_neu," "roberta_pos," "Stars," "Reviews," and "BankName."
Add a new column for labels based on the sentiment analysis results.
Analysis and Reporting:

Analyze the labeled data to understand customer sentiment trends for different banks.
Generate reports or visualizations (e.g., charts, graphs) to present the findings effectively.

[Kaggle Dataset Link](https://www.kaggle.com/datasets/darpan25bajaj/bank-reviewcomplaint-analysis)
## OUTPUT
![image](https://github.com/Aarya-0504/hackofire_WhackOverFlow/assets/97930406/bebc2a29-a1ed-4942-979c-a58a5e2c6d76)
## Plotting Pairplot to check accuracy of transformer model:
![image](https://github.com/Aarya-0504/hackofire_WhackOverFlow/assets/97930406/9a811aa4-dab1-41d9-9c9a-5f5ba1f7a32f)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## For Text Summarization
-Implemented on Dummy Bank Complaints dataset to provide quick summaries to admin and department side for quick overview to get a gist of complaint issue.
-Implemented Pipeline Transformer Models(Falconsai & BART(meta))
-Achieved 80% Length compression (approx.) 

Dataset WordCloud:

![image](https://github.com/Aarya-0504/hackofire_WhackOverFlow/assets/97930406/595b3a48-396e-4437-8e7b-2ba65fdff948)

Results:

![image](https://github.com/Aarya-0504/hackofire_WhackOverFlow/assets/97930406/4ce21d10-49f6-40c2-a2d9-880bcae99b2b)

Length Compression Bar Graph:
![image](https://github.com/Aarya-0504/hackofire_WhackOverFlow/assets/97930406/954812dc-ef1e-431f-8a82-d5e0a11b4fb5)





