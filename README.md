# ConHAN: Contextualized Hierarchical Attention Networks for Authorship Identification

## Abstract

Authorship identification is a common and important task in the field of Natural Language Processing. Defined as the task of predicting the author of a given text, it enables us to accomplish a broad range of tasks, from identifying ghost writers to detecting plagiarism. We show the advantages of using neural network architectures over classic machine learning approaches in terms of accuracy. We first reproduce literature approaches which we benchmark on the Reuters\_50\_50 dataset, and then improve on them by introducing ConHAN, a new deep learning architecture combining pre-trained contextualized embeddings (DistilBERT) and a hierarchical attention architecture. Among all models we tested, the best model achieves an out-of-sample accuracy of 78\%, compared to the literature benchmark of 69\%. Despite a small training size, ConHAN shows promising results on this particular task and we firmly believe it would benefit from a bigger training set. We further analyze our model and discover that ConHAN performs best when predicting authors with simple vocabularies, but it is agnostic to many sentences' grammatical differences.

## Poster

![Page1](https://github.com/VictorJouault/ConHAN-Authorship-Identification/blob/main/ConHAN_Author_Identification_Poster.png)

## Original paper

https://github.com/VictorJouault/ConHAN-Authorship-Identification/blob/main/Paper%20ConHAN.pdf
