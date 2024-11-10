# OnDeT evaluation results

This is repository that cotanins data used in the evaluation of [OnDeT](https://service.tib.eu/vdp/sandbox/ondet) tool. All queries are executed against OnDeT [SPARQL endpoint](http://ols4ing21.service.tib.eu:3030/#/dataset/test/query). If the SPARQL endpoint is not accessible because of any reason, please load all data located from *prov-o-ontology* into your own triple store. 

## OnDeT KG evaluation 

Folder *ondet-kg-evaluation* contains SPARQL queries and thier results that are used in the evaluation of OnDeT KG. Each SPARQL in this folder addresses one competency question from *ONDET KG EVALUATION* section. 

## OnDeT tool evaluation 
The *ondet-tool-evaluation* folder contains SPARQL queries and their results that are used in the evaluation of OnDeT tool. Each SPARQL in this folder addresses one competency question from *THE EVALUATION OF THE ONDET TOOL* section. 

## PROV-O ontology
Foder *prov-o-ontology* contains the following files:

* extended-prov-o.ttl: Extended the PROV-O ontology. 
* all_diff.nq: Change operations have been made on the [io-extracted](https://raw.githubusercontent.com/OpenEnergyPlatform/ontology/master/src/ontology/imports/iao-extracted.owl) that are detected by COnto-Diff tool.
* Individual assertions for semantic differences between two versions of the [io-extracted](https://github.com/OpenEnergyPlatform/ontology/tree/dev/src/ontology/imports) ontology hosted on a GitHub repository.
* differences-between-two-ontology-versions.sprql: A SPARQL query that can be executed agains a SPARQL endpoint after loading aformentioed ontologies.
* differences-between-two-ontology-versions-query-rsults.cvs: The reulst of the SPARQL query. 