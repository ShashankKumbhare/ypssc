## Transmembrane-alpha-helix-calculator

It calculates the percentage coverage in alpha-helix part of of transmembrane proteins of yeast

## Usage

- To use this program for you calculation you need to install R and R studio in your computer .

- To download R and get installation instruction, go to https://cran.r-project.org/bin/windows/base/ and to download R studio go to https://rstudio.com/products/rstudio/download/ 

- Use the default settings for installation of R and Rstudio.

- After installation of R and Rstudio, download the program along with the files that comes with it and copy them to your “Documents” folder of your computer. Open Rstudio and open the file “Transmembrne alpha helix calculator”. After opening it, choose the first line in the program and run it. This line will install the packages that you need to use the program and only needs to be executed only one time. After installation of packages, the program is ready to use.

- In addition to the program, you need two different files in the same folder. One of the files is the structural information of transmembrane proteins in yeast and the other file is results of analysis of your sample from MaxQuant. The first file is the results of structural analysis of transmembrane proteins in yest that has been performed in http://www.cbs.dtu.dk/services/TMHMM/

- The second file is the the peptides.txt wich is normally produced after a regular analysis in MaxQaunt.
The file in the peptides contains many columns for many samples; for each sample you need to keep the following  columns and delete the rest. Keep “Sequance, “start.position”, “End Position” and “ Experiment …” which contains the peptide information regarding a specific sample.

- After preparing the peptides files as explained above, you can run the whole R program and it should produce the results for you in the same folder.
