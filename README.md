# From Materials and Methods:
Bioinformatic analysis of MazF cut site abundance in EDGe genome. In order to predict the relative abundance of the UACMU motif per gene, as compared to chance, the coding sequences (CDS) of L. monocytogenes EDGe (accession no. NC_003210.1) were run through a custom python script based on the formula described in Zhu et al., 2009:

P=∑_(i=0)^K▒〖p^i 〖(1-p)〗^(L-4-i) 〗   (L-4)!/i!(L-4-i)!

Briefly, the probability (p) of the UACMU motif occurring in a CDS was calculated using the length (L) and base composition, which equals (%U’s)2(%A’s)2(%C’s) + (%U’s)2(%A’s) (%C’s)2. Thus, the expected number of motifs in each CDS equals p(L-4). If K is the actual number of motifs found in a CDS, then P equals the probability of a CDS containing K or fewer motifs.

Zhu, Ling, et al. "Staphylococcus aureus MazF specifically cleaves a pentad sequence, UACAU, which is unusually abundant in the mRNA for pathogenic adhesive factor SraP." Journal of bacteriology 191.10 (2009): 3248-3255.
