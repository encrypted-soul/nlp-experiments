The directory location throughout this readme for a given file is the root directory unless specified otherwise.

To test out the code start by creating a python environment and install all the packages mentioned in `requirements.txt` using `pip3 install -r requirements.txt` or an equivalent command. All the code that was run locally used `Python 3.9.6`

The report for the programming task can be found in `docs/report.pdf` and the paper review for BERTScore can be found in `docs/bertscore_review.pdf`

You will need to download the glove 6B model and extract the .zip file for running most of the code - https://nlp.stanford.edu/projects/glove/


### Word similarity scores

The `word_similarity_score_blog.ipynb` file contains an adaption of [this blog](https://songxia-sophia.medium.com/word-embedding-of-brown-corpus-using-python-ec09ff4cbf4f) to tackle the word similarity task on brown corpus.

`word_similarity_score.ipynb` contains the code for the rest of the experiments carried out to build embeddings using both constraints and without constraints.


### Phrase similarity scores

The `phrase_similarity.ipynb` contains the code for most of the non transformer models that were experimented with. The `phrase_similarity_transformer.ipynb` was run on google colab and contains the code for transformer based models.

### Sentence similarity scores

The `sentence_similarity.ipynb` contains the code for most of the non transformer models that were experimented with. The `sentence_similarity_transformer.ipynb` was run on google colab and contains the code for transformer based models.
