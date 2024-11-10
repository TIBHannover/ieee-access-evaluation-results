# Evaluation

This is repository that contains data used in the evaluation of the [OnDeT](https://service.tib.eu/vdp/sandbox/ondet) tool. All queries are executed against OnDeT [SPARQL endpoint](http://ols4ing21.service.tib.eu:3030/#/dataset/test/query). If the SPARQL endpoint is not accessible for any reason, please load all data located in the *prov-o-ontology* folder into your own triple store. 

## PROV-O ONTOLOGY EVALUATION
Foder *prov-o-ontology* folder contains the following files:

* **extended-prov-o.ttl**: Extended the PROV-O ontology. 
* **all_diff.nq**: Axioms that have been changed to the [io-extracted](https://raw.githubusercontent.com/OpenEnergyPlatform/ontology/master/src/ontology/imports/iao-extracted.owl) ontology and detected by the COnto-Diff tool.
* **semantic-diff-contodiff-iao-extracted.ttl**: Individual assertions that desribe semantic differences between two versions of the [io-extracted](https://github.com/OpenEnergyPlatform/ontology/tree/dev/src/ontology/imports) ontology hosted in a GitHub repository.
* **differences-between-two-ontology-versions.sprql**: A SPARQL query that can be executed agains a SPARQL endpoint after loading the the aforementioned ontologies.
* **differences-between-two-ontology-versions-query-rsults.cvs**: The reult of the SPARQL query. 

## ONDET KG EVALUATION 

The *ondet-kg-evaluation* folder contains SPARQL queries and thier results that are used in the OnDeT KG evaluation. Each SPARQL query in this folder is related to a competency question used in the *ONDET KG EVALUATION* section. 

## THE EVALUATION OF THE ONDET TOOL 
The *ondet-tool-evaluation* folder contains the SPARQL queries and their results that are used in the OnDeT tool evaluation. Each SPARQL query in this folder is related to a competency question used in the *THE EVALUATION OF THE ONDET TOOL* section. 

