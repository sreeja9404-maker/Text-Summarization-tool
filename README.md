# Text-Summarization-tool

COMPANY: CODTECH IT SOLUTIONS
NAME: SREEJA R
INTERN ID: CT06DR3163
DOMAIN: ARTIFICIAL INTELLIGENCE
DURATION: 6 WEEKS
MENTOR: NEELA SANTHOSH

DESCRIPTION OF THE PROJECT:

                     Text Summarization Using NLP

This project focuses on automatic text summarization using Natural Language Processing.
Text summarization helps in reducing long text into a short and meaningful summary.
It saves time and helps users understand important information quickly.

The project uses an extractive summarization approach.
In extractive summarization, important sentences are selected from the original text.
No new sentences are created in this method.

The input text is first cleaned using regular expressions.
Special characters, numbers, and extra spaces are removed.
This improves the quality of the text for processing.

The cleaned text is then divided into sentences using sentence tokenization.
Each sentence is further divided into words using word tokenization.
Common words such as “is”, “the”, and “and” are removed using stopwords.

After preprocessing, the frequency of each word is calculated.
Words that appear more frequently are considered more important.
The word frequencies are normalized to avoid bias.

Each sentence is given a score based on the important words it contains.
Sentences with higher scores are considered more meaningful.
The top-scoring sentences are selected using an efficient selection method.

The selected sentences are combined to form the final summary.
The summary length can be controlled by the user.
The output is a short version of the original text with key information.

# TECHNOLOGIES USED:
Python is used as the main programming language.
NLTK is used for tokenization and stopword removal.
Regular expressions are used for text cleaning.
The collections module is used for counting word frequencies.
The heapq module is used to select top sentences efficiently.

This project is simple, efficient, and easy to understand.
It is useful for summarizing articles, documents, and reports.

# OUTPUT:

<img width="818" height="91" alt="Image" src="https://github.com/user-attachments/assets/ae6efa95-2f8e-4a94-bde2-fd011d6a408f" />
