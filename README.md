# Evolutionary-Bioinformatics
Evolutionary relationships of a hypothetical archaeal protein using a standard comparative phylogenomic pipeline.

# Objective: To analyze the evolutionary history and relationships of a hypothetical archaeal protein by identifying homologs and constructing a phylogenetic tree

# Summary: 
1. Query Selection: Hypothetic Archaeal protein was obtained from NCBI database.
2. Homologus Identification: NCBI BLASTp was used against the non-redundant protein database, and 20 homologous sequences were retrieved.
3. Multiple Sequence Alignment: All selected sequences were aligned using T-Coffee to identify conserved and variable regions
4. Data Cleaning: The alignment was manually curated to remove partial and redundant sequences. After filtering, 17 high-quality protein sequences were retained for downstream analysis.
5. Phylogenetic tree: A maximum-likelihood phylogenetic tree was constructed using IQ-TREE based on the 17 curated sequences. The resulting tree was midpoint-rooted for visualization.

# Tools Used:
1. NCBI BLASTp
2. T-Coffee / MAFFT (MSA)
3. IQ-TREE (Phylogenetic inference)
4. iTOL (Tree visualization)
