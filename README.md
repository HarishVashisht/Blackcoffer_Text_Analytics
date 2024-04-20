# Text analysis 
code is at tect analytics file


## Overview

This Python script is designed to perform automated text analysis on web content retrieved from URLs listed in an Excel file. The analysis includes sentiment analysis, readability metrics, and other linguistic features to provide insights into the nature of the content.



## Link for dataset and information  :-
https://drive.google.com/drive/folders/1ltdsXAS_zaZ3hI-q9eze_QCzHciyYAJY?usp=drive_link
## Features

- **Sentiment Analysis:** The script calculates positive and negative scores, polarity score, and subjectivity score to gauge the sentiment of the content.
  
- **Readability Metrics:** Various readability metrics such as average sentence length, percentage of complex words, Fog Index, average number of words per sentence, and more are computed to assess the readability of the text.

- **Word and Syllable Counts:** The tool calculates word count, complex word count, syllable per word, and average word length to analyze the linguistic complexity of the content.

- **Personal Pronouns:** It identifies and counts personal pronouns in the text, providing insights into the narrative style.

## Usage

1. Install the required libraries using `pip install -r requirements.txt`.
2. Ensure you have the input data in the specified format (Excel file with URLs).
3. Run the script `web_content_analysis.py`.
4. The script will process each URL, perform the analysis, and store the results in the specified output format.

## Dependencies

- `BeautifulSoup`: For web scraping and parsing HTML content.
- `requests`: For making HTTP requests to retrieve web content.
- `nltk`: For natural language processing tasks such as tokenization and sentiment analysis.
- `pandas`: For handling data structures and Excel file operations.

## Files Included

- `web_content_analysis.py`: The main Python script for web content analysis.
- `requirements.txt`: List of required Python libraries.
- `Output Data Structure.xlsx`: Sample Excel file with URL data and placeholders for analysis results.
- `positive-words.txt` and `negative-words.txt`: Lists of positive and negative words used for sentiment analysis.
- `StopWords_*.txt`: Text files containing stop words for different categories (e.g., generic, geographic) used in text cleaning.

## output of this project:-
![Screenshot (18)](https://github.com/HarishVashisht/Blackcoffer_Text_Analytics/assets/151710004/bea5da40-09a5-41c1-b209-b20dbe42416b)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Author

- [Harish](harish.shanu009@gmail.com)

Feel free to contribute, report issues, or suggest improvements by creating a pull request or raising an issue in the repository.

---

