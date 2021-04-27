# Revised Reproduction Package for 'Methods Matter: P-Hacking and Publication Bias in Causal Analysis in Economics' by Abel Brodeur, Nikolai Cook, and Anthony Heyes (2020)

yaml, matrix_to_txt, preliminaries have to be installed by manually downloading the files from the github repos, and then installing those files into your PLUS directory with the commands below


- change PLUS directory to local directory with `sysdir set PLUS \\Client\C:\Users\myzha\Documents\Stata\ado`
- download required files from github repo (needs `stata.toc`, `yaml.ado`, `yaml.pkg`, `yaml.sthlp`) and place them in a folder
- enter `net install yaml, force from (\\Client\C:\Users\myzha/Downloads/stata-misc-master)`. files should be downloaded to your PLUS directory. type `which yaml` to confirm


- `net install matrix_to_txt, force from (\\Client\C:\Users\myzha/Downloads/gslab_stata-master/gslab_misc/ado)`
- `net install preliminaries, force from (\\Client\C:\Users\myzha/Downloads/gslab_stata-master/gslab_misc/ado)`


need to install dataout: `ssc install dataout`

solution devised from https://github.com/UrbanInstitute/education-data-package-stata readme


.do file output manually moved into `raw output`. they must be manually edited to achieve figures in paper
