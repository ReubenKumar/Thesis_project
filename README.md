# Thesis_project
The code used for my thesis project

order of scripts:
data_split.Rmd        (split data into two subsets one subset for traing the MOFA model, one for training the random forest model)
RNA_preprocessing.Rmd        (preprocessing the RNA dataset)
mutation_preprocessing.Rmd        (preprocessing the mutational dataset)
methylation_preprocessing.Rmd        (preprocessing the methylation dataset)
cna_preprocessing.Rmd        (preprocessing the CNA dataset)
MOFA_models.Rmd        (identify the optimal MOFA model, build the optimal MOFA model, factor characterisation)
extract_features.Rmd        (extract informative features from the MOFA model in relation to the treatment response covariate)
GSEA.Rmd        (gene set enrichment analysis using interesting features from the MOFA model)
pathway_enrichment.Rmd        (pathway enrichment analysis using interesting features from the MOFA model)
Random_Forest.ipynb        (Build and evaluate random forest model using the features extracted from the MOFA model)

