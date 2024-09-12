# Sentence Transformer for Information Retrieval on Medical documents

Given the large volume of clinical documents that medical professionals have to manage on a daily basis, there is an increasing need for Information Retrieval (IR) systems that 
enable an automatic and efficient access to medical information from big corpora of medical texts. \\
The peculiar and technical terminology used in Medicine requires the employment of domain-specific IR tools. Also, the widespread accessibility of medical information on Internet widens the users landscape, 
including both experts and non-experts people. Then, an effective IR tool must take into account the varying language skills of users, which may result in a lexical gap between user queries 
and medical information. \\
In this perspective, this project aims to address an IR task on the [NFCorpus](https://www.cl.uni-heidelberg.de/statnlpgroup/nfcorpus/), which contains natural language queries (written in non-technical English) and medical documents 
(written in a complex terminology-heavy language). \\
In particular, queries and documents embeddings are obtained by using a Sentence Transformer, properly trained on the NFCorpus with metric learning techniques. 
Then, embeddings are used for performing, given a certain query, k-NN search on documents.

## Repository structure

````
.
├── notebook                            # jupyter notebook containing the project's code with comments                
├── README.md
├── requirements.txt                    # necessary installations
````

## Required installations
To install the required packages to run the project, download the ````requirements.txt```` file and run the following:

````
pip install -r /path/to/requirements.txt
````
