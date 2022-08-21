**iDrosophila1: A genome-scale metabolic network model of Drosophila melanogaster**

**Contributors:** Muberra Fatma Cesur, ‪Kiran Raosaheb Patil‬, Tunahan Cakir‬

The latest version of iDrosophila1 is shared here, which is a genome-scale metabolic network model for Drosophila melanogaster. The reconstruction process of iDrosophila1 is detailed below:

![Figure](https://github.com/SysBioGTU/iDrosophila/blob/main/Figures/Flowchart_GitHub.jpg)

*Common curation steps* refers to the revisions (name standardization, the curations of metabolic redundancy, stoichiometric consistency, and missing/incomplete components), which were commonly applied to the orthology-based draft Drosophila model and Drosophila-specific KEGG-MetaCyc network in the reconstruction process. Note that each model component was carefully examined in the model curation step.
The metabolic content of iDrosophila1 model is summarized in the following table. In addition, the model contains eight intracellular compartments (cytosol, nucleus, golgi apparatus, mitochondria, mitochondrial intermembrane space, endoplasmic reticulum, lysosome, and peroxisome).

| **Organism                               | Reactions         | Metabolites | Genes**|   
|------------------------------------------|-------------------|-------------|--------|
| Drosophila melanogaster                  | 8,230             | 6,990       | 2,388  |   
|------------------------------------------|-------------------|-------------|--------|   
| 			**ATPM Reaction**              |			**Biomass Reaction**          |  
|------------------------------------------|------------------------------------------| 
| HMR_3964 (fixed to 8.55 mmol ATP g-1h-1) | 				Biomass_formation         |   


**Model Installation**

•	The model is shared in MATLAB .mat format, which is compatible with COBRA Toolbox model structure. Download the model from GitHub page or directly clone the repository (using GitBash or downloading the zipped files by left-clicking the 'Code' drop-down menu) to your local drive.

•	As follows, use MATLAB load() and save() functions to load and save the model in .mat format.

		cd ./code
		model = load(‘iDrosophila1.mat’);   % loading
		save('iDrosophila1.mat');   % saving

