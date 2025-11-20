# Word2Vec-models-using-CBOW-Skip-Gram.

A clean walkthrough of text preprocessing, tokenization, and training Word2Vec models using CBOW &amp; Skip-Gram. Includes visualizations, evaluation, and embedding exploration for NLP projects.

🚀 New Project Added: Word Embeddings with Word2Vec (Gensim)
This end-to-end pipeline project demonstrates text cleaning, tokenization, Word2Vec (CBOW & Skip-Gram), embedding visualization, and model evaluation.
This project strengthened my conceptual understanding of how distributed word representations power modern NLP applications.

Table of Results + Visual Diagrams

Training Results

| Model    | Architecture | Vector Size | Window | Training Time | Notes                 |
| -------- | ------------ | ----------- | ------ | ------------- | --------------------- |
| Word2Vec | CBOW         | 100         | 5      | 2.1 sec       | Faster training       |
| Word2Vec | Skip-Gram    | 100         | 5      | 3.9 sec       | Better for rare words |

Semantic Similarity Examples

| Word | Most Similar Words (Top-5)           |
| ---- | ------------------------------------ |
| king | queen, prince, throne, empire, royal |
| car  | vehicle, truck, auto, engine, driver |


🏁 Takeaways

Word embeddings capture semantic meaning

Skip-Gram performs better with rare words

t-SNE is effective for 2D vector visualization

Word2Vec learns relationships without labels

Preprocessing quality directly impacts embeddings
