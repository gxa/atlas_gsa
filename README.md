# atlas_gsa - Gene set analysis based on fisher exact test

A simple RESTful API to analyse (Fisher-exact) enrichment of user-provided set of Ensembl gene identifiers against differentially expressed genes in each comparison in Expression Atlas. 

Authors: Nuno Fonseca, Robert Petryszak Contact: atlas-feedback@ebi.ac.uk 

The code available here performs Fisher-exact gene set overlap (FDR = 0.1) between the userprovided set of genes in a given organism against the set of differentially expressed genes in each Atlas comparison for that organism. All genes tested for differential expression in a given comparison are treated as background. 


This code is used to perform the analyses available through a RESTful API that was developed to analyse (Fisher-exact) enrichment of user provided set of Ensembl gene identifiers in a given organism against differentially expressed genes in each comparison for that organisms in Expression Atlas.

Documentation on the using the API is available through https://www.ebi.ac.uk/~rpetry/geteam/gsa/gsa_apispec.pdf

Queries through the web interface are availbale in Expression Atlas https://www.ebi.ac.uk/gxa/home/

