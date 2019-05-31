# Visual-question-answering-system

# Word Embeddings:
The 'Word embedding model.IPYNB' file contains gensim's word2vec model. This model is used to get vectorized representation of the text in questions and answers. 

# Autoencoder:
The 'autoencoder-QA-3.IPYNB' file contains an autoencoder model. This model is built using LSTM's to generate compressed representations of questions. 

# Text based question answering system:
The 'Q&A on loaded enc-dec.IPYNB' file contains a text only question answering system. This mdoel uses the compressed questions from the autoencoder model to answer text only questions (without image data). 

# Visual question answering system:
The 'imgTextSimple.IPYNB' file contains a visual question answering system. This model is a combination of CNN's and LSTM's. It uses the compressed questions from autoencoder along with images to generate answers to questions based on image data. 

# Reports
The part1 and part2 reports respectively contain further information about the text based and visual question answering models.  
