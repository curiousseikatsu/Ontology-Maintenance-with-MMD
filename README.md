# Ontology-Maintenance-with-MMD
Ontologies contain an abundance of concepts, are frequently structured as hierarchies, and can cover different domains of knowledge. Polysemous concepts need to be disambiguated for annotation purposes, for example, a concept such as _depression_ has a different meaning in the fields of psychology and economics. On this repository, we provide a notebook that allows the computation of the _maximum mean discrepancy_ to indicate whether sets of concepts sharing the same meaning should be merged. This method is a novel approach to ontology maintenance because it provides an objective metric that supports the decision-making of subject matter experts during the concept evaluation process. Our objective is thus to assist ontology maintenance, in particular the organization of concepts, through an analysis framework that gives insights into the polysemy of concepts. 


## Using the MMD Score for ontology maintenance
To compute the MMD score, a pair-wise computation that requires 1000 samples of SciBERT embeddings per synonym, use the following notebook:

* [MMD Score](https://github.com/curiousseikatsu/Ontology-Maintenance-with-MMD/blob/main/MMD_Ontology_Maintenance.ipynb)

