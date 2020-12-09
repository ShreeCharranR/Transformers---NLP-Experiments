# 1) CNN

# 2) LSTM & Stacked LSTM


# Transformers for NLP

# 1- Multiple Tasks of NLP


- ***Sentence Classification _(Sentiment Analysis)_***: Indicate if the overall sentence is either positive or negative, i.e. *binary classification task* or *logitic regression task*.
- ***Token Classification (Named Entity Recognition, Part-of-Speech tagging)***: For each sub-entities _(*tokens*)_ in the input, assign them a label, i.e. classification task.
- ***Question-Answering***: Provided a tuple (`question`, `context`) the model should find the span of text in `content` answering the `question`.
- ***Mask-Filling***: Suggests possible word(s) to fill the masked input with respect to the provided `context`.
- ***Summarization***: Summarizes the ``input`` article to a shorter article.
- ***Translation***: Translates the input from a language to another language.
- ***Feature Extraction***: Maps the input to a higher, multi-dimensional space learned from the data.

Pipelines encapsulate the overall process of every NLP process:
 
 1. *Tokenization*: Split the initial input into multiple sub-entities with ... properties (i.e. tokens).
 2. *Inference*: Maps every tokens into a more meaningful representation. 
 3. *Decoding*: Use the above representation to generate and/or extract the final output for the underlying task.


# 2 a- Extractive Summary - BERT & DIstill BERT
# 2 b- Abstarctive Summary - BART


# 3 - NER 

 Data set (https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus)
