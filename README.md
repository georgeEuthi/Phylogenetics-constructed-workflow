Phylogenetics constructed workflow

This repository provides standard workflows for phylogenetic analysis using various tools and packages available in R, Python, and Linux environments. The workflows cover key steps in phylogenetic analysis, from data preparation to tree construction and visualization.
The scripts are inspired by the official guidelines provided by the developers of these tools and have been enhanced with personal additions based on practical experience. I would like to extend my gratitude to the creators of the packages and tools utilized in this workflow. All credit belongs to their original authors. These workflows are shared solely for educational and research purposes.


Phylogenetic studies often involve the use of computational tools to construct and analyze phylogenetic trees. This workflow incorporates a variety of widely used packages and tools to streamline this process:
1) Aligning sequences and formatting data.
2) Tree Construction: Using methods such as Maximum Likelihood (ML), Bayesian Inference, and Neighbor-Joining (NJ).
3) Annotating and visualizing trees for interpretation.
4) Assessing branch support through bootstrapping or posterior probabilities
5) Later one can customize the generated tree in https://itol.embl.de/ (newick format)

A few examples of different tools for Phylogenetics that my standard workflow can be applied:
For R
install.packages("ape")
install.packages("phangorn")
install.packages("ggtree")

For Python
pip install biopython  
pip install ete3  

For Linux:
sudo apt install mafft  
sudo apt install raxml  
sudo apt install mrbayes  

Although each package and programming language uses distinct functions and data formats, the underlying rationale and methodological principles remain consistent across tools.

GUI tools avaliable to use:
In case one wants to use a comperhensive tool for Phylogeentic analysis, without extensive coding but with the help of a user interphase, I propose the following tools:
1) https://www.megasoftware.net/ for MEGA 
2) https://phylipweb.github.io/phylip/ for Phylip

Acknowledgments
Special thanks to the developers and maintainers of the tools and packages utilized in these workflows for their significant contributions to the field of phylogenetics.

Disclaimer
These scripts are intended for educational and research purposes only. All intellectual property rights related to the tools and packages belong to their respective authors.

Happy Coding!
