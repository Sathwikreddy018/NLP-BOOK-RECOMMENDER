## **Content-Based Filtering: NLP Based Book Recommender Using BERT-Embeddings**

Content-based filtering is a widely used technique in recommender systems that suggests items to users based on the attributes of items they've previously interacted with or expressed interest in. In the context of a book recommendation system, this means if a user likes a particular book, the system will recommend other books that share similar characteristics such as theme, author, series, or a summary of the description.

**Book Recommendation Engine**

Our book recommendation engine leverages Natural Language Processing (NLP) techniques, specifically BERT-embeddings, to identify and extract key information from book descriptions.

Here's how it works:

Keyword Extraction: The system extracts keywords that best describe each book using BERT-embeddings. This advanced NLP model helps capture the semantic meaning of words, providing a richer representation than traditional methods.

Feature Reduction (TF-IDF): To refine these keywords, we apply the TF-IDF (Term Frequency-Inverse Document Frequency) method. TF-IDF ranks words based on their frequency within a given book and across the entire corpus of books, highlighting words that are most relevant and distinctive.

Vector Representation: Once the significant keywords are identified, each book is transformed into a numeric vector representation. This allows us to perform mathematical comparisons between books.

Similarity Calculation (Cosine Similarity): To find similar books, we use cosine similarity. This metric measures the cosine of the angle between two vectors, determining how similar they are in direction. A higher cosine similarity indicates greater similarity between books.

The overall architecture of the book recommendation engine is illustrated below:

<center><b> Book Recommendation Engine </b></center>

## **References**
Goodreads Book Datasets With User Rating 2M, n.d.

GitHub - MaartenGr/KeyBERT: Minimal keyword extraction with BERT, n.d.

GitHub - emonson/altair-vis-python: Visualization in Altair with Python workshop, n.d.












Tools

