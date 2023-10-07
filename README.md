# toxic-comment-classification
detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models.

# preprocessing dataset
- removed urls, username, contractions and non-English words.
- used tokenizers to convert the words in the corpus to index values in dict.
- padded the sequence using padding="post".

# bulit bi-directional lstm followed by 2 dense layers.
