# Sentiment-Analysis-of-Climate-Change-Discourse-on-Wikipedia


## Description
This project aims to analyze the sentiment of the textual content related to climate change on the Wikipedia page. By using Natural Language Processing (NLP) techniques and sentiment analysis tools, the project will quantify the overall tone of the discourse surrounding climate change, providing insights into how the topic is presented and perceived in a widely referenced information source.

## Objectives
1. **Data Extraction**: Fetch the HTML content of the Wikipedia page on "Climate change".
2. 
3. **Text Preprocessing**: Clean and preprocess the text to remove noise such as reference numbers, extra whitespace, and digits.
4. 
5. **Text Tokenization**: Split the preprocessed text into sentences for detailed analysis.
6. 
7. **Sentiment Analysis**: Use NLTK's SentimentIntensityAnalyzer to perform sentiment analysis on the text.
8. 
9. **Aggregation of Sentiment Scores**: Compute and normalize the aggregated sentiment scores to determine the overall tone.
10. 
11. **Result Presentation**: Present the aggregated sentiment scores for negative, neutral, positive, and compound sentiments.

## Methodology
1. **Web Scraping**: Use Python's `urllib` and `BeautifulSoup` libraries to scrape the Wikipedia page.
2. 
3. **Text Preprocessing**: Employ regular expressions and NLTK methods to clean and prepare the text for analysis.
4. 
5. **Sentiment Analysis**: Utilize NLTK's VADER (Valence Aware Dictionary and sEntiment Reasoner) to analyze the sentiment of each sentence in the text.
6. 
7. **Data Aggregation and Normalization**: Calculate the average sentiment scores to obtain a comprehensive understanding of the overall sentiment.

## Tools and Technologies
- **Programming Language**: Python
- 
- **Libraries**: NLTK, urllib, BeautifulSoup, re, collections
- 
- **NLTK Resources**: stopwords, punkt, vader_lexicon

## Expected Outcomes
- A clear understanding of the sentiment expressed in the Wikipedia article on climate change.
- 
- Quantitative data on the proportion of negative, neutral, and positive sentiments within the article.
- 
- Insights into the overall tone and perception of climate change as presented on Wikipedia.

## Application
The findings from this project can be useful for educators, researchers, policymakers, and the general public to understand the framing of climate change in popular information sources. It can also serve as a foundation for further studies on the impact of sentiment in online information dissemination.
