# pdf-comparison
---

# Document Similarity Analysis with spaCy

This script provides a comprehensive analysis of the similarity between two PDF documents using the spaCy library. It evaluates the similarity based on the overall content, bigrams (2-word combinations), trigrams (3-word combinations), and sentence structures.

## Features:

1. **Document Similarity**: Computes the overall similarity between two documents based on their content.
2. **Bigram Analysis**: Evaluates the similarity between documents based on 2-word combinations.
3. **Trigram Analysis**: Evaluates the similarity between documents based on 3-word combinations.
4. **Sentence-level Similarity**: Computes the similarity between documents at the sentence level using fuzzy matching.

## Requirements:

- Python 3.6 or higher
- spaCy library
- PyPDF2 library
- spaCy English model (`en_core_web_md`)

## Setup:

1. Install the required libraries:
   ```bash
   pip install spacy PyPDF2
   ```

2. Download the spaCy English model:
   ```bash
   python -m spacy download en_core_web_md
   ```

## Usage:

1. Run the script:
   ```bash
   python document_similarity_script.py
   ```

2. When prompted, provide the paths to the two PDF documents you want to compare.

3. The script will then analyze the documents and print out the similarity results based on the overall content, bigrams, trigrams, and sentence structures.

## Customization:

- If you have a custom list of stop words or want to add/remove words from the default list, you can modify the `custom_stop_words` list in the script.

## Note:

- The script uses spaCy's built-in stop words to filter out common words that don't contribute significantly to the content's meaning. This ensures a more focused comparison based on the non-stop words in the documents.

---

You can save the above content in a file named `README.md` and place it in the same directory as the script. This will provide users with a clear understanding of what the script does and how to use it.
