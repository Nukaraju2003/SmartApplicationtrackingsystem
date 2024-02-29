# Resume Screening App
This app is built for employers looking for candidates against a particular job description. This app looks into outputing a x% percent similarity score given the resume of the candidate and a job description.



## Intuition:
1. Get [context-aware BERT Embeddings](https://towardsdatascience.com/nlp-extract-contextualized-word-embeddings-from-bert-keras-tf-67ef29f60a7b) or [document doc2vec embeddings](https://cs.stanford.edu/~quocle/paragraph_vector.pdf) for Resume and Job Description.
2. [Hugging Face](https://huggingface.co/sentence-transformers/bert-base-nli-mean-tokens) Library was very useful alongwith doc2vec or nltk
3. Get their [cosine similarity](https://developers.google.com/machine-learning/clustering/similarity/measuring-similarity)

## Workflow:
<img src = "Demo\Workflow.png">

## Interface
<img src = "Demo\Interface.png" height=400>
<img src = "Demo\BERT.png" height=400>
<img src = "Demo\Doc2Vec.png" height = 400 width = 800>

## Usage

```
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```
**Run**: ``` streamlit run app.py```



