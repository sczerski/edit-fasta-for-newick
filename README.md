# edit-fasta-for-newick
This script removes extra header info from fasta file for constructing a tree in newick format.
Note: This script was specifically designed for use with Pacbio OTU and NCBI filtered reads (see: filter-combine-reads)

Input:
1) a multiple sequence alignment file (eg. "otu_45_anaerococcus.aln")

Output:
1) "otu_alignment_w_edited_header.aln" multiple sequence alignment file with edited header information 
