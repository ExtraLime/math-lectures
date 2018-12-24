# unit-4-NLP-capstone
Using machine learning to cluster and classify math lectures
this repository is for my NLP project.

93 lectures
clustering
training shallow NN
cosine_similarity
 - Note that the analysis will not be applicable to your results if you run the model. You maybe need to adjust ax limits in the plots to see the actual shape of the data after the t-SNE reduction.
 
 The project/presentation of this material is in the **'math_lects'** notebook.
 
 math_sentences - a look at the lectures at the sentence level. Clustered into 34 clusters, i use NMF and LDA to extract topics out of the clusters. The cosine similarities of each sentences are also calculated and a basic similarity serch framework is setup.
 
 math_words - is a look at a word2vec model space using the lectures as the corpus. In this notebook a visualized wordspace of 2 dimensions is created to see how words' cosine similarities correspond with their distance in 2 dimensions

