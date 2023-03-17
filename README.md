# Personality-Analysis-Based-On-Lexical-Features

Personality Analysis based on Lexical Features is a system trained on an array of features
extracted from a collection of labeled essays. This is built to produce a subset of labels
that the model predicts for an input essay.
Extracting the lexical features, prediction is based on the big-five personality traits:
Extraversion, Conscientiousness, Openness, Agreeableness, Neuroticism

The main objective was to extract lexical features from a dataset which contained essays written
by various authors. Based on these features we predicted the Big 5 personality traits along with
their accuracy.
The traits and their implications are:
● Neuroticism - People of this category are often tensed and depressed
● Extraversion - People of this category are energetic and they like people’s company
● Openness - People of this category are creative and non-judgemental
● Conscientiousness - People of this category are focused to their work
● Agreeableness - People of this category are kind and good natured


Our system comprises of:
The baseline model, which includes Word2Vec- the primary feature.
This was used to calculate the sum and average of all the words in the text.
The texts from the essays were tokenized in order to get the syllables (vowel sound).
The grid search method, which is a process of scanning data to configure optimal parameters for
a given model.
Herein, the text from the files were converted into lowercase and binarized corresponding to the
Big Five traits.
TF-IDF vectorization technique was used for retrieving information in order to represent how
important a specific word or phrase is to a given document.
Based on the above models, we worked on a dataset composed of essays written by authors, to
retrieve the accuracy based on the Big 5 Personality Traits.

Using MLP classifier, the essays were extracted from the dataset, trained and the predictions
were made. We were able to predict the personality traits from the essays written by authors with
60% accuracy.
