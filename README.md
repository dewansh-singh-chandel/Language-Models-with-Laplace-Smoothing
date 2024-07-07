# Perplexity analysis on Language Model

The Project follows the below timeline

**Data Acquisition**: Obtain dataset from specified source.
- **Preprocessing**: Tokenize corpus into sentences using NLTK sentence tokenizer.
- **Data Splitting**: Randomly split corpus into 80% training and 20% validation sets.
- **Model Training and Validation**:
  - Train language models (LMs) including Unigram, Bigram, Trigram, and Quadgram on training set.
  - Validate trained models on validation set and report perplexity scores.
  - Implement LMs from scratch, without using existing NLP libraries.
- **Laplace Smoothing**:
  - Apply Laplace smoothing to trained LMs.
  - Compare perplexity scores before and after smoothing.