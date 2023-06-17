# Text-Analysis-of-CNN-News-Articles
This repository contains the code for a text analysis project that focuses on CNN news articles. The project includes web scraping, data preprocessing, and natural language processing techniques to extract insights from the articles. The code is written in Python and uses popular libraries such as BeautifulSoup and NLTK.

1. Dataset Selection: The initial step involves selecting the dataset, which in this case is CNN's news articles. The dataset serves as the foundation for analysis and provides the raw material to extract valuable insights.

2. Web Scraping with Beautiful Soup: To gather the news articles, the Beautiful Soup library is employed. It gracefully navigates through the HTML structure of the CNN website, extracting the relevant information and storing each article as an individual text file. This process ensures the availability of a comprehensive and diverse dataset.

3. Data Cleaning: With the dataset acquired, the cleaning process commences. It involves removing any irrelevant information, such as HTML tags, special characters, and punctuation marks, while preserving the integrity of the textual content. This ensures that the subsequent analysis is based on accurate and meaningful data.

4. Text Tokenization using NLTK: Next, the NLTK (Natural Language Toolkit) library is employed for text tokenization. It skillfully breaks down the cleaned text into individual words or tokens, allowing for a granular analysis of the textual content. This process lays the foundation for further analysis, such as sentiment analysis.

5. Sentiment Analysis: Sentiment analysis is performed to gauge the sentiment expressed in each news article. This process determines whether the sentiment conveyed is positive, negative, or neutral. By understanding the sentiment, valuable insights can be gained about public opinion, trends, and biases present in the articles.

6. Sentiment Score Calculation: In addition to determining the sentiment, a sentiment score is assigned to each article. This score quantifies the intensity of the sentiment, allowing for a more nuanced analysis. It provides a numerical representation of the sentiment, facilitating comparisons and trend analysis across articles.

7. Readability Score Calculation: Apart from sentiment analysis, the readability of each article is also assessed. Readability scores measure the ease with which readers can comprehend the text. These scores take into account factors such as sentence length, word complexity, and syntactic structure. By analyzing the readability scores, the accessibility and target audience of the articles can be understood.

8. Saving Results to an Excel File: To ensure the findings are organized and easily accessible, the sentiment, sentiment score, and readability score for each article are saved in an Excel file. This allows for further analysis and visualization of the data, promoting a comprehensive understanding of the CNN news articles.
