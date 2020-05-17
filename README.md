# In-depth-NLP
# Parts of Speech Tagging (POS)  
The challenge of correctly identifying parts of speech is summed up nicely in the [spaCy docs](https://spacy.io/usage/linguistic-features):

<div class="alert alert-info" style="margin: 20px"> Processing raw text intelligently is difficult: most words are rare, and it's common for words that look completely different to mean almost the same thing. The same words in a different order can mean something completely different. Even splitting text into useful word-like units can be difficult in many languages. While it's possible to solve some problems starting from only the raw characters, it's usually better to use linguistic knowledge to add useful information. That's exactly what spaCy is designed to do: you put in raw text, and get back a **Doc** object, that comes with a variety of annotations. </div>

In this notebook (POS & NTR) we'll take a closer look at coarse POS tags (noun, verb, adjective) and fine-grained tags (plural noun, past-tense verb, superlative adjective).
