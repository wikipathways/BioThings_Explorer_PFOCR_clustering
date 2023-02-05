# PFOCR for prioritization of  BioThings Explorer (BTE) TRAPI results
This repo is for [PFOCR for prioritization / clustering GitHub issue #538](https://github.com/biothings/BioThings_Explorer_TRAPI/issues/538). 
The goal is to use PFOCR to do prioritization and/or grouping of trapi results using the following strategy:

1. initially explore the idea using Jupyter notebooks to post-process trapi results for sample queries
2. if the results from 1. are good, move the processing from the Jupyter notebooks into the JS code (probably in query_graph_handler). This code could run in conjunction with the actual calling of the APIs to get records, and potentially also in part afterwards to supplement the trapi results
3. if the results from 2. are good, we can explore how to extend the ideas to the UI

# Requirements  
1. URL with TRAPI results (json format)
2. Access to the [Dropbox folder with PFOCR data](https://www.dropbox.com/sh/jofvpvfkx469ebd/AAAccAoqvDv572R7ZGUAvr31a?dl=0).

# Details
This repo is build from the initial exploration done by [Anders Riutta](https://github.com/wikipathways/pathway-figure-ocr/tree/master/notebooks).

**PET_notebook_v1.ipynb** is a Jupyter notebook that addresses the requirements in [issue #538](https://github.com/biothings/BioThings_Explorer_TRAPI/issues/538). 
