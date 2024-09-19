I employed the <b>bert-base-uncased</b> model for NLP on the <a href="https://www.kaggle.com/competitions/nlp-getting-started/overview">Disaster Tweets</a> dataset. To monitor the performance of different models, I used the Weights & Biases platform (<a href="https://wandb.ai/daniele-didino/disaster_tweets/overview">link</a>).

<b>bert_base_uncased</b>: This model is pretrained on the English language (uncased, meaning it does not differentiate between uppercase and lowercase letters). It is accessible on  <a href="https://huggingface.co/bert-base-uncased">Hugging Face</a> and was introduced in this <a href="https://arxiv.org/abs/1810.04805">paper</a> (<a href="https://github.com/google-research/bert">repository</a>). BERT is a transformers model trained on a vast corpus of English data in a self-supervised fashion (i.e., pretrained solely on raw texts, without human labeling).

Notebooks:

- <b>EDA.ipynb</b>: Basic exploratory analysis of the dataset.

- <b>colab_1a_embedding_model.ipynb</b>: Embedding model (non-pretrained).

- <b>colab_1b_embedding_model_hp_search.ipynb</b>: Hyperparameter search on the Embedding model.

- <b>colab_2a_bert_base_uncased.ipynb</b>: Bert-Base-Uncased model.

- <b>colab_2b_bert_base_uncased_hp_search.ipynb</b>: Hyperparameter search on the Bert-Base-Uncased model.

- <b>colab_3_embedding_&_bert_base_uncased.ipynb</b>: Integration of the Embedding model and Bert-Base-Uncased model.
