# hackofire_WhackOverFlow

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
## Plotting Pairplot to check if RoBERTa giving correct output or not:
![image](https://github.com/Aarya-0504/hackofire_WhackOverFlow/assets/97930406/9a811aa4-dab1-41d9-9c9a-5f5ba1f7a32f)

