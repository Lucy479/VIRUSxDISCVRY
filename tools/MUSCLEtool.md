# {Muscle}
written by: [Lucy Zhou](https://github.com/yourname *optional link*)

[10 minutes] {MUSCLE is a computer program tool for multiple sequence comparison basing on log-expectation. This tool is used to compare nucleotide or protein sequences of viruses and determine for a phelygenetic relationship based on the results.}

**Tutorial Objective**: {We will demonstrate MUSCLE by comparing 14 RNA-dependent-RNA-polymerases amino acid sequences of a few viruses in the Botourmiaviridae family with a amino acid sequence derived from RNA sequences from a human sample.}

## Input / Prerequisites
- [Tool Weblink](https://www.ebi.ac.uk/jdispatcher/msa/muscle) 
- Web access
- A virus family, virus GenBank accession, or SRA accession to search for
- A list of virus rdrp sequence can be found in NCBI website: https://blast.ncbi.nlm.nih.gov/Blast.cgi#2808997 


## Output

{The output can be a fasta, html, cluster W format depending on your needs. Graphs are geenrated based on alignment, as well as a simple phylogenetic tree. Further interpretations on phylogy can be done with exporting data to external softwares}

### 1. Tutorial Instructions
Navigate to the MUSCLE website: https://www.ebi.ac.uk/jdispatcher/msa/muscle

### 2.
Collect the protein sequences from the desired viruses. 
https://blast.ncbi.nlm.nih.gov/Blast.cgi#2808997 

### 3
Enter the protein sequences into the "Input Sequence" window. Be sure to label every sequence.Choose a output of choice and click align. 

### 4
In the output, a graph with the multiple alignment result will show, with similar residues presenting similar color. 

![Alignment result](Lab11/Step4.png)

### 5
Under the tab "Results Viewer", MUSCLE introduced ways that the data can be exported to external software such as Jalview to edit and further analyze the alignment results. The following is an example of Jalview output. 

![Jalview alignment](Lab11/Jalview on MSA copy.png)
![Jalview phylogentic tree](Lab11/Phylogenetic tree based on MSA copy.png)

### 6
Tool output, Input sequences, Alignment data can be downloaded under the "Result File"" tab. 

### Conclusion

That's it! You've used the MUSCLE to align multiple viral rdrp sequences!
By simple input of protein sequences obtained from the NCBI or SRA run into the MUSCLE web browser, the alignment of viral amino acid sequences and phylogenetic relationship can be obtained.

### See Also:

- [Publication Name](https://www.nature.com/articles/s41586-021-04332-2)
- [Additional useful link](https://web.archive.org/web/19991128125537/http://www.geocities.com/Heartland/Bluffs/4157/hampdance.html)
- [10 best practices for writing documentation](https://www.grammarly.com/blog/developer/10-best-practices-writing-documentation/)
- ...