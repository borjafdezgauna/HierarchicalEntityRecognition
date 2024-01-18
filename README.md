# Hierarchical Entity Recognition

In this repository, we have uploaded the scripts used to preprocess the data, train and evaluate the models used for the paper "Hierarchical Entity Recognition".

To test the models with any of the sample files:

1. Install spacy following the steps in <https://spacy.io/usage>

2. Run the system to predict Hierarchical Entities in one of the test files. For example:

    cd scripts
    python -m predict-her ..\models ..\samples\jobs.txt (on Windows)
    python -m predict-her ../models ../models/jobs.txt (on Linux/MacOS)