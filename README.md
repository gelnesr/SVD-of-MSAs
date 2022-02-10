# SVD-of-MSAs

  This repository contains jupyter notebooks for performing singular value decomposition (SVD) on protein multiple sequence alignments (MSAs).  This procedure is detailed in a manuscript that is being prepared for submission to the journal Protein Science.  As with that manuscript, SVD is performed separately on the homeodomain (HD) family and the RAS family.  The respository contains separate notebooks for each.
  
  For each of the two protein families there is a notebook that performs the core SVD and analysis that most users will want to do for their protein families, named HD_SVD_short.ipynb and Ras_SVD_short.ipynb.  There are also there are expanded notebooks that perform additional analysis such as examining the length and sequence identity relationships to sequence eigenvector 1, effects of residue scrambling on singular values, consensus analysis, and functional annotation of sequences ion SVD space.  These notebooks (HD_SVD_w_figures.ipynb and Ras_SVD_w_figures.ipynb) generate all of the figures in our Protein Science manuscript except for the phylogenetic tree analysis.
  
  We also include sequence alignments and functional annotations for HD and Ras, so that users can run these notbooks using our MSAs.
