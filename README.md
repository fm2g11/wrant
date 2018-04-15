# wrant
Writing Assistant

## Prerequisites
You need a `data/books` folders with plain text files, ideally books of the same genre to what you want to check.

## Install

```bash
pip install https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-2.0.0/en_core_web_sm-2.0.0.tar.gz
pip install git+https://github.com/fm2g11/wrant.git
```

## Preprocess Data

```python
from wrant.preprocess import extract_tokens
from wrant.preprocess import extract_verbs_prep
extract_tokens.process()
extract_verbs_prep.process()
```

## Run
```python
./src/ui/server.py
```

Now go to http://localhost:8001
