# Sentiment-Analysis-and-Topic-Modeling-of-Hello-Tractor-App-Reviews
This project combined data scraping, sentiment analysis, topic modeling, and frequent term extraction to provide a comprehensive understanding of user feedback for the Hello Tractor app.
## Data Collection:

Scraped reviews of the Hello Tractor application from the Google Play Store, focusing on user feedback with a range of sentiments (positive to negative).

## Sentiment Analysis:

Performed sentiment analysis on the reviews to classify them as POSITIVE or NEGATIVE based on their content.
Created new columns in the dataset to capture sentiment and corresponding scores.

## Topic Modeling:

Applied BERTopic, a topic modeling technique, to extract underlying topics from the reviews.
Experimented with different settings (automatic topic number vs. default) to determine the optimal number of topics.

## Frequent Terms Extraction:

Used CountVectorizer to identify frequently occurring terms in both positive and negative reviews.
Extracted the most common words, identifying the pros (positive terms) and cons (negative terms) of the app based on user feedback.
Visualization:

Generated a word cloud to visually represent the most frequent words, where larger words indicate more frequent mentions.

## Outcome:

The analysis revealed key insights into what users appreciate (pros) and dislike (cons) about the Hello Tractor app, helping to highlight areas for improvement or further development.
