# Project-2
Github repository of Project 2 for BIMM 143 Bioinformatics Lab


## Introduction

### Research Question

#### Are there nucleotide sequence similarities between cysteine/serine proteases that activate same allergic reaction pathways in humans such as house mite allergen, papain, ragweed pollen allergen, SplA, and if so, what structural similarities can be seen in the protein or the active site by looking at its 3D structure that may explain the function similiarities?

### Background Research

#### A major class of allergens that induce airway stimulation are proteases that come from many different sources. Some of these protease allergens include house dust mite derived proteases Der p 1, ragweed protease allergen Amb a 1.2, papain, and bacteria derived SplA . All of these allergens have shown to activate the type 2 immunity in a similar fashion where they disturb the tight junctions in epithelial cells making the epithelial layer more permeable. It also activates the Protease Activated Receptor 2 by cleaving the receptor that further signals the activation of type 2 immunity (Matsumura, 2011).  Papain has shown to trigger T cell differentiation with a bias towards Th2 cells that initiate type 2 immunity through the PAR2 pathway (Liang et al., 2012). Staphylococcus aureus derived SplA protease has also shown to increase Th2 cells in a similar fashion (Nordengrun et al, 2021). Ragweed allergy has been found to linked with the proteases allergen which is triggered by PAR2 (Hosoki et al., 2017). Moreover, these features were also observed in house dust mite allergen Der p 1 (Reithofer et al., 2017).

### Hypothesis

#### If there are multiple instances of environmental allergens being proteases or having protease-like activity causing similar allergic responses in humans, then there must be either protein sequence or structural homology between these proteins for it to cause allergies in a similar manner in humans.

### Analysis and Data

#### The analysis performed in this project invlude pairwise alignment as well as multiple sequence alignment to check for protein sequence similarities. The result of the pairwise alignment was plotted on a heamap to visualize the score differences between the comparisons, and multiple sequence alignment can be seen through the function MSAprettyprint which nicely organizes results of our MSA.

#### 3D protein measurements were made through bio3d and pyMOL, and structural similiarities near the binding sites of the proteins were measured and visualized through it's 3D structure images. The binding sites were obtained through bio3d, and these residues and nearby residues were checked for structual similarities. These videos have been embedded into this notebook.

#### The datasets were downloaded in UniProt and PDB



## FASTA files

### all are Amino Acid sequence fasta files downloaded from Uniprot, all fasta file names except ragweed protease allergen are the accession number. Ragweed protease allergen accession number is P27760
#### ragweed protease allergen: "PLY1_AMBAR.fasta"
#### Staphylococcus aureus protease allergen splA: "Q2FXC2.fasta"
#### house dust mite protease allergen: "P08176.fasta"
#### papain: "P00784.fasta"
