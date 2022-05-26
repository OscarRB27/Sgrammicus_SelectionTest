# *Sgrammicus*_SelectionTest

The purpose of this repository is to compile the different results and files that correspond to a chapter of my research project, which corresponds to the possible detection of outlier SNPs, candidates for selection in the lizard *Sceloporus grammicus*.

The division that follows the repository is as follows: five main folders called **Analysis**, **Blogs**, **Data**, **Report** and **Scripts**.

- The **Analysis** folder contains five folders whose names are: BayeScan, BayPAss, Clusters_DAPC, Env_Vars and Her_Fst. These folders contain the different graphs and results obtained in the analyzes carried out for this project. The Clusters_DAPC, Env_Vars and Her_Fst folders only contain one folder called Figures which contains the graphs of the analyses. The BayeScan and BayPass folders contain, in addition to the Figures folder, two extras. One called Results that is divided into three folders: Sg_All, Sg_P6 and Sg_P5, which contains files resulting from the analysis and tables of results of each of the programs. The division of these folders results from the different ways of executing the programs. All = taking all the sampling sites, P6 = taking only the sampling sites for P6, and P5 = taking only the sampling sites for P5. The second folder is called Program, which contains the executable to run the program and the scripts that are required to analyze each one.

- The **Blogs** folder contains two .txt files that contain the commands and parameters to run BayeScan and BayPass. These commands are written to run the scan as All, P6, and P5.

- The **Data** folder contains six folders, which contain the different types of databases used in the analyses. BayeScan = Databases All, P6 and P5. Env_Data, contains the data of all the abiotic variables (Env_Data) of the landscapes, as well as the coverage (Cov_Data.txt) of the different patches of soil types. In addition, there are records of the abiotic variables separated by sites (P6For, P6Agr, P5For, P6Agr) and localities (P5 and P6). Loci_Data = the SNP database used. Loci_Info = containing the position, chromosome and ID information of each loci. Pop_Info = containing the membership site information for each sample. The BayPass folder contains three folders: Input_Loci, which contains the loci = All, P5, and P6 databases, Input_Vars, which contains the variables databases, and Data loci, which contains general loci information.

- **Report** folder, which contains a .txt file indicating the link to this repository. It also contains the memory and presentation of this work.

-**Script** folder, which contains all the scripts made to execute the different analyses. These are numbered and have code names according to the analysis for which they were made. These files are in two formats .Rmd and .html.

Finally, this README is at the same level as the five main folders and contains all the information about the organization of this repository.

Postscript:

I hope that this new publication will be useful for the future and that it will alleviate the frustration of performing genomic analyses, which are often a headache.

Greetings!!! :D