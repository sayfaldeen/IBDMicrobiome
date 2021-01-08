# IBDMicrobiome README

## Summary
This IPYNB contains code for analysis of gut microbiome data for recent resarch

## Contents
1. DataFiles
	* Contains all the data required to execute the analysis in the IPYNB
2. IBD Microbiome Analysis.ipynb
	* Contains code for analysis conducted for IBD gut microbiome research
		1. Taxonomic analysis
			* Data pre-processing and log-ratio transformation
			* Alpha-diversity analysis (Shannon Entropy)
			* RFC-based identification of important bacterial species
			* Differential abundance analysis
		2. Network analysis
			* Eigenvector centrality analysis
			* Degree analysis
				- Degree and genera
				- Degree and differential abundance status
			* Association analysis (shared and unique edges)
		3. Functional analysis
			* Differential abundance of protein family roles in IBD vs control groups
