# ML-for-NLP
# Natural Language Processing Pipeline

This repository contains a comprehensive Natural Language Processing (NLP) pipeline implementation using Python. The pipeline demonstrates various fundamental NLP techniques and transformations using popular libraries such as NLTK, scikit-learn, and gensim.

## Features

- Text tokenization (words and sentences)
- Stopwords removal
- Stemming using Porter Stemmer
- Lemmatization using WordNet
- Part-of-Speech (POS) tagging
- Named Entity Recognition (NER)
- Text vectorization techniques:
  - One-Hot Encoding
  - Bag of Words (BoW)
  - N-grams (Bigrams)
  - TF-IDF (Term Frequency-Inverse Document Frequency)
- Word Embeddings using Word2Vec:
  - CBOW (Continuous Bag of Words)
  - Skip-gram models

## Prerequisites

```bash
pip install nltk numpy scikit-learn gensim
```

Required NLTK data packages:
```python
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger_eng')
nltk.download('wordnet')
nltk.download('maxent_ne_chunker_tab')
nltk.download('words')
nltk.download('tagsets')
```

## Usage

The script demonstrates various NLP techniques on a sample text. Each section of the code shows a different NLP transformation:

1. **Text Tokenization**
   - Word tokenization
   - Sentence tokenization

2. **Text Preprocessing**
   - Stopwords removal
   - Stemming
   - Lemmatization

3. **Linguistic Analysis**
   - POS Tagging
   - Named Entity Recognition

4. **Text Vectorization**
   - One-Hot Encoding
   - Bag of Words
   - N-grams (Bigrams)
   - TF-IDF

5. **Word Embeddings**
   - Word2Vec CBOW model
   - Word2Vec Skip-gram model

## Example Output

```python
# Sample text
text = "Natural Language Processing is a fascinating field. It enables machines to understand human language."

# Tokens output
Tokens: ['Natural', 'Language', 'Processing', 'is', 'a', 'fascinating', 'field', '.', 'It', 'enables', 'machines', 'to', 'understand', 'human', 'language', '.']
```

## Contributing

Feel free to submit issues and enhancement requests! Follow these steps to contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- NLTK team for providing excellent NLP tools
- scikit-learn developers for machine learning utilities
- gensim team for word embedding implementations

## Contact

If you have any questions or suggestions, please open an issue in the repository.
