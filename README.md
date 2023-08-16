# Airline✈️ Reviews Analysis

This repository contains a Jupyter Notebook demonstrating the process of scraping and analyzing customer reviews of an airline, specifically British Airways. The notebook covers the following steps:

1. **Data Collection:** Scraping customer reviews from [Airline Quality](https://www.airlinequality.com/airline-reviews/british-airways) using BeautifulSoup and Requests library. The reviews are saved in a CSV file.

2. **Data Preprocessing:** Filtering relevant reviews and cleaning the data by removing unnecessary prefixes. The preprocessed reviews are saved in a new CSV file.

3. **Topic Modeling:** Using the Gensim library to perform topic modelling on the preprocessed reviews. Latent Dirichlet Allocation (LDA) is used to identify key topics in the reviews.

4. **Word Frequency Analysis:** Calculating the frequency of words related to the identified topics and creating a bar chart to visualize the results.

5. **Sentiment Analysis:** Using VADER (Valence Aware Dictionary and sEntiment Reasoner) to perform sentiment analysis on the reviews and categorize them into positive, negative, or neutral.

6. **Word Cloud:** Generating a word cloud to visually represent the most frequent words in the reviews.

## Requirements

- Python (version 3.x)
- Libraries: BeautifulSoup, Requests, pandas, nltk, gensim, wordcloud, matplotlib, nltk.sentiment.vader

## Acknowledgments

- Forage & British Airways for providing this virtual experience program for which this project was created.
- [Airline Quality](https://www.airlinequality.com) for providing the review data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to explore the notebook and adapt it to your own use case.

For any questions or improvements, please open an issue or contribute to the repository.
