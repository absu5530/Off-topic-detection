# Off-topic detection
Implemented semantic vector extraction and similarity methods such as tf-idf similarity, Latent Semantic Analysis and Document Embeddings to detect off-topic responses using Random Forests/Gradient Boosted Trees on various datasets, achieving F1 scores of >0.9

LSA and document embeddings gave the best results, with prompt-specific off-topic responses performing better than response sets with broader definitions of off-topic. Models were compared by accuracy, F1 score and Matthews Correlation Coefficient.

Refer to the Jupyter Notebook `Off-topic 20detection using measures% of semantic similarity.ipynb` for modeling and a detailed analysis.
