# Hierarchical Entity Recognition

In this repository, we have uploaded the scripts used to preprocess the data, train and evaluate the models. We also include the models for reference and some samples that can be used to test the models.

To preprocess the models:

    python -m preprocess-training-data <path-to-spacy-json-files>

To train the models:

    python -m train-models <path-to-training-spacy-files> <path-to-test-spacy-files>

To evaluate the models:

    python -m evaluate-models <path-to-test-files>
