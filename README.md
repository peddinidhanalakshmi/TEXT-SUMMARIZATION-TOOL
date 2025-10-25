# TEXT-SUMMARIZATION-TOOL
COMPANY : CODTECH IT SOLUTIONS

NAME : Peddini Dhana Lakshmi

INTERN ID : CT06DY2357

DOMAIN : Artificial Intelligence

DURATION : 6 WEEKS

# Description

Text summarization is a process of reducing a large piece of text into a shorter version that preserves its main ideas and key information. It is a core application of Natural Language Processing (NLP), allowing computers to automatically generate summaries from lengthy documents, news articles, or research papers.

The primary goal of text summarization is to provide a concise and meaningful summary without losing the context of the original content.

There are two main types of text summarization:

1. Extractive Summarization: Selects important sentences or phrases directly from the original text.


2. Abstractive Summarization: Generates new sentences to convey the same meaning, similar to how humans summarize text.



In this task, we create a Text Summarization Tool using NLP techniques that can automatically summarize lengthy articles or paragraphs and display concise summaries.


---

# Model Implementation Steps

The implementation of a text summarization tool involves the following theoretical steps:

Step 1: Text Collection

The process starts with obtaining the input text, which may be a paragraph, article, or any lengthy document that needs to be summarized.

Step 2: Text Preprocessing

The input text undergoes preprocessing, which includes:

Tokenization: Breaking the text into sentences and words.

Stopword Removal: Eliminating common words such as the, is, in, at etc., which do not contribute to meaning.

Normalization: Converting all words to lowercase and removing punctuation marks.


This step helps in simplifying the text for further analysis.

Step 3: Word Frequency Calculation

Each word's frequency (how many times it appears in the text) is calculated. Words that occur frequently are given higher importance since they contribute more to the meaning of the text.

Step 4: Sentence Scoring

Each sentence in the text is scored based on the sum of the frequencies of the words it contains. Sentences with higher scores are considered more important and are likely to be included in the summary.

Step 5: Summary Generation

The top-scoring sentences are selected and combined to form the final summary. The number of sentences included can be adjusted based on the desired summary length.


---

# Results

After implementing the text summarization model, the tool successfully produces a concise summary of the given lengthy text.
The summarized text retains the essential points and provides an easy-to-read overview of the content.

Input: A lengthy article or paragraph.

Process: The tool analyzes, scores, and selects the most important sentences.

Output: A short and meaningful summary containing only the key information.


This summarization reduces the reading time and helps users quickly grasp the main idea of any document.


---

# Output 
<img width="1806" height="13" alt="Image" src="https://github.com/user-attachments/assets/f07d9d68-0683-48e5-a0c0-e7295ad75f1b" />

