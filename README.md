# Web-Scraping

### AIM: 

1. To scrape a HTML page and compare it with a text file to find common words in those two files. 
2. To list the top 15 words used in both the files.
3. To display the meaning of those words. 


### PROCEDURE:

1. Scraped a HTML file ("https://playground.tensorflow.org/") and store it as a text file using the BeautifulSoup Python package. 
(BeautifulSoup is a Python package which is used to parse HTML and XML documents.)

2. Divided the text file into tokens.

3. Performed some simple data preprocessing steps like removing punctuations, changing the case of the words into lowercase, removing stopwords and removing numbers from the list of words. 

4. Read the text file ("ss2.txt") from my local drive, divided it into tokens and performed the previously mentioned data preprocessing steps. 

5. Printed the common words in both files.

6. Printed the top 15 words based on their frequency. 

7. Printed the meaning of the words using the WordNet lexical database for English Language in Python. 
