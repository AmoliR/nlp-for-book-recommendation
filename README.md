![](images/books-recommender-banner.jpg)

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter&color=green)](https://github.com/AmoliR/nlp-for-book-recommendation/blob/main/book_recommendation.ipynb) [![GitHub latest commit](https://img.shields.io/github/last-commit/AmoliR/nlp-for-book-recommendation)](https://GitHub.com/AmoliR/nlp-for-book-recommendation/commit/) [![GitHub commits](https://badgen.net/github/commits/AmoliR/nlp-for-book-recommendation/main?icon=github&color=green)](https://github.com/AmoliR/nlp-for-book-recommendation/commits/main)

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://github.com/AmoliR/nlp-for-book-recommendation) [![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://github.com/AmoliR/nlp-for-book-recommendation/blob/main/model.ipynb) [![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://github.com/AmoliR/nlp-for-book-recommendation/blob/main/eda.ipynb) [![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://github.com/AmoliR/nlp-for-book-recommendation/blob/main/eda.ipynb) [![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/AmoliR/nlp-for-book-recommendation/blob/main/book_recommendation.ipynb)

# Content-Based Filtering: NLP Based Book Recommender Using BERT-Embeddings

- Content based filtering is one of the two common techniques of recommender systems. intelligible from the name, it uses the content of the entity (to be recommended) to find other relevant recommendations similar to it. In simpler terms the system finds the keywords or attributes related to the product that the user likes, later uses this information to recommend other products having similar attributes. 
- For a book recommendation system, given a book name the recommender will suggest books that are similar to it. The choice is made considering concise information of the book such as its theme, author, series, and summary of the description. 

## Book Recommendation Engine
- The succinct data of keywords that is provided to the recommender system is generated using NLP techniques such as word embeddings.  Keywords that most describe the book are extracted from the book description using BERT-embeddings, this word collection is further reduced using the frequentist feature extraction method TF-IDF that ranks the words based on their frequency in the book and the corpus.     
- Once the numeric vector representation of all the books is generated, each word vector is compared against the other vector and similar vectors (books) are found using cosine similarity.  

![architecture](images/book_recommendation_system.svg) 
<center><b> Book Recommendation Engine </b></center>

---
## References
- [Goodreads Book Datasets With User Rating 2M, n.d.](https://www.kaggle.com/datasets/bahramjannesarr/goodreads-book-datasets-10m?select=book1000k-1100k.csv)
- [GitHub - MaartenGr/KeyBERT: Minimal keyword extraction with BERT, n.d.](https://github.com/MaartenGr/KeyBERT)
- [GitHub - emonson/altair-vis-python: Visualization in Altair with Python workshop, n.d.](https://github.com/emonson/altair-vis-python)