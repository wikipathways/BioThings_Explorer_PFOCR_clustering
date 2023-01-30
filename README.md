# PFOCR for prioritization of  BioThings Explorer (BTE) TRAPI results
This repo is for [PFOCR for prioritization / clustering GitHub issue #538](https://github.com/biothings/BioThings_Explorer_TRAPI/issues/538). 
The goal is to use PFOCR to do prioritization and/or grouping of trapi results using the following strategy:

1. initially explore the idea using Jupyter notebooks to post-process trapi results for sample queries
2. if the results from 1. are good, move the processing from the Jupyter notebooks into the JS code (probably in query_graph_handler). This code could run in conjunction with the actual calling of the APIs to get records, and potentially also in part afterwards to supplement the trapi results
3. if the results from 2. are good, we can explore how to extend the ideas to the UI

# Work so far
This repo is build from the initial exploration done by Anders Riutta. Anders' notebooks: https://github.com/wikipathways/pathway-figure-ocr/tree/master/notebooks
