# Object Class Instance Extraction

In this repository, we have uploaded the scripts used to preprocess the data, train and evaluate the models used for the paper "Object Class Instance Extraction".

To test the models with any of the sample files:

1. Install spacy following the steps in <https://spacy.io/usage>

2. Run the system to predict Nested Entities in one of the test files. For example:

```
    cd scripts
    
    python -m predict ..\models ..\samples\jobs.txt (on Windows)
    python -m predict ../models ../models/jobs.txt (on Linux/MacOS)
``` 
