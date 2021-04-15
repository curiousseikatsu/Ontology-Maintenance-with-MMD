# Ontology-Maintenance-with-MMD
Ontologies contain an abundance of concepts, are frequently structured as hierarchies, and can cover different domains of knowledge. Polysemous concepts need to be disambiguated for annotation purposes, for example, a concept such as _depression_ has a different meaning in the fields of psychology and economics. On this repository, we provide a notebook that allows the computation of the _maximum mean discrepancy_ to indicate whether sets of concepts sharing the same meaning should be merged. This method is a novel approach to ontology maintenance because it provides an objective metric that supports the decision-making of subject matter experts during the concept evaluation process. Our objective is thus to assist ontology maintenance, in particular the organization of concepts, through an analysis framework that gives insights into the polysemy of concepts. 

The code is published together with our full research paper during the [DeepOntoNLP Workshop at the European Semantic Web Conference 2021](https://sites.google.com/view/deepontonlp-eswc2021/home):

* [Supporting Ontology Maintenance with Contextual Word Embeddings and Maximum Mean Discrepancy]()

## Getting Started

The code in this repository lets you run the following task:

* Compute maximum mean discrepancy between two distributions 

## Installation

### Prerequisites

* Python ≥ 3.6
* **45GB RAM** required minimum memory size

## Using the MMD Score for ontology maintenance
To compute the MMD score, a pair-wise computation that requires 1000 samples of SciBERT embeddings per synonym, use the following notebook:

* [MMD Score](https://github.com/curiousseikatsu/Ontology-Maintenance-with-MMD/blob/main/MMD_Ontology_Maintenance.ipynb)

## Contributors and acknowledgments

The experiments for this research project were conducted by Natasha Shroff (University of Amsterdam), the project experimentation was led and supported by Dr. Pierre-Yves Vandenbussche (Elsevier Labs) and Dr. Véronique Moore (Elsevier Amsterdam). The MMD score pipeline used for this research was created by Dr. Pierre-Yves Vandenbussche. This project was supervised by Prof. Paul Groth from the University of Amsterdam. Moreover, we received weekly feedback from a team of NLP specialists at Elsevier; Janneke van de Loo, Philip Tillman and Jan-Jaap Meijerink have attended the sessions and provided their useful input to the project. 
