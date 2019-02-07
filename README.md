Vector space models and the Indonesian denominal verbs
================
Gede Primahadi Wijaya Rajeg<sup><a itemprop="sameAs" content="https://orcid.org/0000-0002-2047-8621" href="https://orcid.org/0000-0002-2047-8621" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a></sup>, Karlina Denistia, Simon Musgrave

<!-- README.md is generated from README.Rmd. Please edit that file -->
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

This is a repository containing the source [R Markdown](http://rmarkdown.rstudio.com) [Notebook](https://bookdown.org/yihui/rmarkdown/notebook.html) for the statistical analyses accompanying our paper on vector space models and Indonesian denominal verbs (in preparation for a special issue in [*NUSA*](http://www.aa.tufs.ac.jp/en/publications/nusa) titled [*Linguistic studies using large annotated corpora*](https://malindo.aa-ken.jp/call67.html), edited by [Hiroki Nomoto](http://www.tufs.ac.jp/ts/personal/nomoto/) and [David Moeljadi](http://compling.hss.ntu.edu.sg/who/david/)). The Notebook, however, does not provide detailed exposition and discussion for each points. Readers are referred to our paper for details. The following R packages have to be installed and loaded to run all codes in this Notebook:

-   cluster (Maechler et al. [2018](#ref-maechler_cluster_2018))
-   tidyverse (Wickham & Grolemund [2017](#ref-wickham_r_2017))
-   dendextend (Galili [2015](#ref-galili_dendextend_2015))
-   wordVectors (Schmidt & Li [2017](#ref-schmidt_wordvectors_2017))
-   Rling (Levshina [2015](#ref-levshina_how_2015))

How to download/clone the repository and the data
=================================================

1.  Go to the GitHub repo(sitory): <https://github.com/gederajeg/vector_space_model_indonesian>.

2.  Then, find and click the green button saying `"Clone or download"` and then the `"Download ZIP"` option (see the picture below).

    ![Downloading the repository from GitHub](gh_tuts_1_clone.png)

3.  The second step above will download the repo as a folder, by default called `vector_space_model_indonesian-master`. We suggest keep this folder's name. The folder consists of, among others, README files, .bib file, and the R Notebook containing the R codes for producing the analyses in the paper (incl. figures and tables).

4.  Given the large size of the data for version control with Git, we store them separately on figshare (**ADD FIGSHARE DOI**). Visit that figshare repo and please read the information page before clicking the white button saying `"Download all"` (next to the dark pink `"Cite"` button) to download all the data.

5.  The downloaded data will be stored in a folder named with numbers. Please rename the downloaded data folder into `data` and move this `data` folder inside the `vector_space_model_indonesian-master` folder.

How to run the codes in the R Notebook
======================================

1.  Make sure all the required R packages mentioned above are installed in R and you have the latest version of [RStudio](https://www.rstudio.com) (download from [here](https://www.rstudio.com/products/rstudio/download/)).

2.  Next, go to the `vector_space_model_indonesian-master` folder and double-click the `MeNasal.Rproj` file. It will open up an RStudio session associated with data and codes in this project.

3.  Then, open the R Notebook file called `nusa_r_notebook.Rmd` by going to `File` &gt; `Open File ...` (or use <kbd>⌘</kbd>+<kbd>O</kbd> on macOS or <kbd>Ctrl</kbd>+<kbd>O</kbd> on Windows), then select the given `.Rmd` file.

4.  The codes can be run/executed all at once (i) using keyboard shortcut <kbd>⌥</kbd>+<kbd>⌘</kbd>+<kbd>R</kbd> on macOS (i.e., <kbd>Option</kbd>+<kbd>Cmd</kbd>+<kbd>Enter</kbd>) or <kbd>Alt</kbd>+<kbd>Ctrl</kbd>+<kbd>R</kbd> on Windows, (ii) or by navigating to the drop-down `Run` button and select `Run All` as shown below.

    ![Running the notebook](gh_tuts_2_run_notebook.png)

    After running all the codes, reader may preview the notebook in HTML format by clicking on the `Preview` button or by using keyboard shortcut <kbd>⌘</kbd>+<kbd>⇧</kbd>+<kbd>K</kbd> (i.e., <kbd>Cmd/Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>K</kbd>).

5.  Alternative to the run-all option in (4) above, reader may wish to run the code chunk-by-chunk. The code-chunk is indicated by grey-shaded area in the Notebook (see the picture below).

    ![Running the code chunk](gh_tuts_3_run_nbook_chunk.png)

    Place the cursor in each chunk and then use keyboard shortcut <kbd>⌘</kbd>+<kbd>⇧</kbd>+<kbd>Enter</kbd> (i.e., <kbd>Cmd/Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Enter</kbd>) to run the codes in the given chunk. Another way is to click the green arrow button (see the picture above).

References
==========

Galili, Tal. 2015. Dendextend: An R package for visualizing, adjusting, and comparing trees of hierarchical clustering. *Bioinformatics*. doi:[10.1093/bioinformatics/btv428](https://doi.org/10.1093/bioinformatics/btv428).

Levshina, Natalia. 2015. *How to do Linguistics with R: Data exploration and statistical analysis*. John Benjamins Publishing Company.

Maechler, Martin, Peter Rousseeuw, Anja Struyf, Mia Hubert & Kurt Hornik. 2018. *Cluster: Cluster Analysis Basics and Extensions*.

Schmidt, Ben & Jian Li. 2017. *wordVectors: Tools for creating and analyzing vector-space models of texts*. <http://github.com/bmschmidt/wordVectors>.

Wickham, Hadley & Garrett Grolemund. 2017. *R for Data Science*. Canada: O’Reilly. <http://r4ds.had.co.nz/> (7 March, 2017).
