# Clustering-Verb-Meanings-in-Italian

This repository contains codes and data for my MA thesis project.

**By now** there are only results concerning a clustering using k-means on the Sketch Engine Embeddings on ItWac (https://embeddings.sketchengine.eu/static/index.html). I used all the verbs from the lowercased lemmatized ones.

K-means was run using the scipy library (https://docs.scipy.org/doc/scipy/reference/generated/scipy.cluster.vq.kmeans.html#scipy.cluster.vq.kmeans), as in the script "k-means-clustering.py".
The .txt files are obtained through the script, varying the k parameter (i. e. the number of clusters) at k = 15, k = 30, k = 40. 
The .spydata file contains variables of the other files- 

Note that the results cannot be replied identically, since in the k-means algorith the initial centroids are estimated randomly. 
