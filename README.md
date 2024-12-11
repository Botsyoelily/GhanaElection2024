Sentiment Analysis of YouTube Comments for Ghana's 2024 Presidential Election

Overview

This project uses YouTube API and TextBlob for sentiment analysis to predict public favorability toward Ghana's 2024 presidential candidates: John Dramani Mahama and Mahamudu Bawumia. It analyzes comments on videos related to each candidate to classify sentiments as positive, neutral, or negative.

Workflow

Data Collection:
Fetch video data for each candidate using the YouTube API with search queries.
Extract up to 100 videos per candidate along with their comments.
Sentiment Analysis:
Use TextBlob to classify each comment into one of three categories: positive, neutral, or negative.
Aggregate sentiment scores for each candidate.
Result Aggregation:
Calculate total sentiment scores for both candidates.
Compare scores to predict which candidate has stronger public favorability.
Key Files

SentimentAnalysisScript.ipynb: Contains the Python code for fetching video data, analyzing comments, and aggregating results.
YouTube API Key: Required to fetch video data (not included; generate your own API key).
How to Run

Install required libraries:
pip install google-api-python-client textblob
Replace the placeholder api_key in the script with your YouTube API key.
Execute the script to fetch video data and perform sentiment analysis.
Results

The analysis compares aggregate sentiment scores for each candidate, providing insights into public perception and favorability based on YouTube comments.

Limitations

Bias in Comments: YouTube users may not represent the entire voting population.
Data Restrictions: Disabled comments or limited video metadata may affect results.
Sentiment Complexity: TextBlob may misclassify nuanced or sarcastic comments.
Disclaimer

This project is an educational exercise conducted out of curiosity and is not a definitive predictor of election outcomes. Results should be interpreted as a reflection of online sentiment rather than a comprehensive public opinion analysis.






