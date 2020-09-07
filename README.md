# CRLTS
Customer Request Learning Team-Suite, by AOEC 2020
The version is work in progress but has the fundamental concept!

Files that are part of the repository:
(a) This repository includes CRLTS.py a program using Python and Anaconda 
(b) This repository contains a CRLTS-Project-Summary.pdf file
(c) This repository contains a old_service_request_x.xlsx file that is used to create
a old_service_request_x.csv file

(d) Though needed the repository does not include the GoogleNews-vectors-negative300.bin due to
its big size in GB

Libraries used:
The source code uses specific libraries to load data, perform computation and display output are
(a) Pandas – Data acquisition library
(b) numpy – Array processing library
(c) nltk.data and nltk.corpus – Natural language processing library
(d) gensim and gensim.models – for text analytics and clustering, where the Word2Vector function is used
(e)  gensim.models.keyedvectors – to import keyed vectors
(f) matplotlib – for visualizing clusters
(g) sklearn.cluster – to import DBSCAN for clustering
(h) sklearn.metrics.pairwise – to import cosine-similarity to find out request description similarity

