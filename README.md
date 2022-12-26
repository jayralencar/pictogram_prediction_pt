# Predictive Authoring for Brazilian Portuguese Augmentative and Alternative Communication

Individuals with complex communication needs (CCN) often rely on augmentative and alternative communication (AAC) systems to have conversations and communique their wants. Such systems allow message authoring by arranging pictograms in sequence. However, the difficulty of finding the desired item to complete a sentence can increase as the user's vocabulary increases. This paper proposes using BERTimbau, a Brazilian Portuguese version of BERT, for pictogram prediction in AAC systems. To finetune BERTimbau, we constructed an AAC corpus for Brazilian Portuguese to use as a training corpus. We tested different approaches to representing a pictogram for prediction: as a word (using pictogram captions), as a concept (using a dictionary definition), and as a set of synonyms (using related terms). We also evaluated the usage of images for pictogram prediction. The results demonstrate that using embeddings computed from the pictograms' caption, synonyms, or definitions have a similar performance. Using synonyms leads to lower perplexity, but using captions leads to the highest accuracies. This paper provides insight into how to represent a pictogram for prediction using a BERT-like model and the potential of using images for pictogram prediction.

## Execution

### Corpus Construction

### Models finetuning

1. Finetuning captions embeddings: [Word finetuning.ipynb](/Word finetuning.ipynb)

### Models testing
