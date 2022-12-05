# Computational-Drug-Discovery-Project

#Explore druggable compounds for Cyclooxygenase-1, Cyclooxygenase-2, Epidermal growth factor receptor erbB1, and acetylcholinesterase

#Developing machine learning models to predict drug potency (IC50) based on 800+ unique compound features using ChEMBL database.

The [*ChEMBL Database*](https://www.ebi.ac.uk/chembl/) is a database that contains curated bioactivity data of more than 2.3 million compounds. It is compiled from more than 85,000 documents, 1.5 million assays and the data spans 15,000 targets and 2,000 cells and 43,000 indications.
[Data as of July 22, 2022; ChEMBL version 31].

#Performed Exploratory Data Analysis for molecular properties based on Lipinski descriptors;
Christopher Lipinski, a scientist at Pfizer, came up with a set of rule-of-thumb for evaluating the **druglikeness** of compounds. Such druglikeness is based on the Absorption, Distribution, Metabolism and Excretion (ADME) that is also known as the pharmacokinetic profile. Lipinski analyzed all orally active FDA-approved drugs in the formulation of what is to be known as the **Rule-of-Five** or **Lipinski's Rule**.

The Lipinski's Rule stated the following:
* Molecular weight < 500 Dalton
* Octanol-water partition coefficient (LogP) < 5
* Hydrogen bond donors < 5
* Hydrogen bond acceptors < 10 

#Built models to predict drug potency using PaDEL descriptor based on 800+ unique molecular fingerprints
Ref: http://www.yapcwsoft.com/dd/padeldescriptor/


#Compared model performance among 39 machine-learning algorithms using Lazy Predict 
Ref: https://pypi.org/project/lazypredict/

