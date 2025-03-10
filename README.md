# NLP Lab Repository
This repository is dedicated to my NLP lab in college. It contains Jupyter Notebooks that explore various natural language processing techniques in a structured order.
---

## Overview

This repository includes several notebooks that cover topics such as text preprocessing, feature extraction, similarity measures, and data visualization:

- **StemmingLemmatization.ipynb**  
  *Topics Covered:*
  - Downloading and setting up resources (e.g., NLTK’s 'punkt' and spaCy models).
  - Fetching and tokenizing Wikipedia text using the TreebankWordTokenizer.
  - Applying different stemming algorithms (Porter, Lancaster, Snowball) and lemmatization with both spaCy and NLTK.
  - Comparing outputs and measuring execution times.

- **FrequencyAnalysis.ipynb**  
  *Topics Covered:*
  - Text preprocessing including lowercasing, punctuation removal, tokenization, and stopword removal.
  - Counting word frequencies using Python’s `Counter`.
  - Visualizing word frequency trends through bar charts, word clouds, pie charts, line graphs, histograms, and n-gram (bigram/trigram) analysis.

- **SimilarityMeasure.ipynb**  
  *Topics Covered:*
  - Computing similarity measures using TF-IDF and cosine similarity.
  - Leveraging word embeddings from GloVe and spaCy to calculate cosine similarity, Euclidean distance, Manhattan distance, Jaccard similarity, and Pearson correlation.
  - Detailed explanations and mathematical formulas for each similarity/distance metric.

---

## Flow of Topics

1. **Downloading Resources**  
   Each notebook starts by downloading or verifying the necessary resources to ensure reproducibility.

2. **Tokenization and Text Preprocessing**  
   - *StemmingLemmatization.ipynb* demonstrates the use of tokenizers to split Wikipedia text.
   - *FrequencyAnalysis.ipynb* applies text cleaning techniques and tokenizes sample text for subsequent analysis.

3. **Feature Extraction & Analysis**  
   - Stemming and lemmatization are performed and compared.
   - FrequencyAnalysis.ipynb counts word occurrences and visualizes trends.
   - SimilarityMeasure.ipynb extracts text features and computes various similarity metrics.

4. **Visualization & Performance Comparison**  
   Each notebook includes visualizations—such as charts, graphs, and word clouds—to help interpret the analysis results and performance comparisons.

---

## How to Use

- **Step 1:** Clone or download the repository.
- **Step 2:** Open any `.ipynb` notebook using [Jupyter Notebook](https://jupyter.org/) or [JupyterLab](https://jupyterlab.readthedocs.io/).
- **Step 3:** Follow the cell execution order to observe the techniques in action.
- **Step 4:** Feel free to experiment by modifying the code and exploring additional NLP techniques.

---

## Future Additions

More notebooks and topics will be added as the lab progresses, including:
- Advanced text classification methods.
- Deep learning models for NLP.
- Interactive dashboards for data visualization.

---

Feel free to explore, experiment, and enhance your understanding of NLP through these notebooks. Contributions and suggestions are welcome!

