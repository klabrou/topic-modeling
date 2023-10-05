# Topic Modeling from PDF/txt files

Python scripts for extracting text from PDF and TXT files, followed by text preprocessing using NLP methods and topic modeling of the preprocessed texts. Topic modeling can be used to perform preliminary data analysis to identify key themes and topics present in a corpus of text. Code based on [tutorial]([https://towardsdatascience.com/topic-modeling-with-bert-779f7db187e6]) by [Maarten Grootendorst]([https://medium.com/@maartengrootendorst]).

### Key Functionalities:

#### Text Extraction:

- Extracts text from files in a specified directory.
- Handles both PDF and TXT file formats.

#### Text Preprocessing:

- Stopword removal
- Lemmatization


#### Topic Modeling:

- BERTopic model is used for identifying topics within the preprocessed text.
- UMAP is used for dimensionality reduction of text embeddings.

The code returns the 10 most representative words and the number of documents associated with each topic.



#### Tools:

- NLTK: NLP Library Used for natural language preprocessing tasks like stopword removal and lemmatization.
- PyPDF2: Library for extracting text from PDF files.
- [BERTopic]([https://towardsdatascience.com/topic-modeling-with-bert-779f7db187e6]): Topic modeling technique that leverages transformers and c-TF-IDF to create dense clusters allowing for easily interpretable topics whilst keeping important words in the topic descriptions.
- UMAP: Algorithm used for dimensionality reduction 
