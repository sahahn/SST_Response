This repository contains the code used to replicate "Design issues and solutions for stop-signal data from the Adolescent Brain Cognitive Development [ABCD] study" by Patrick G. Bissett, McKenzie P. Hagen, Russell A. Poldrack (https://www.biorxiv.org/content/10.1101/2020.05.08.084707v3.full). The authors original code can be found at https://github.com/mckenziephagen/ABCD_Stop_Signal. 

This repository contains number of jupyter notebooks which cover different parts of the response analysis.

- Match_Data.ipynb contains our best efforts at replicating the subset of subjects from the ABCD data release that the original authors ended up with, and provides the subset of subjects used in the remainder of these analyses. It contains commentary and detailed explanations as to a few different problems, and references to deleted notebooks in the original author's github history.

- clean_SST (annotated).ipynb and SST_Problems (annotated).ipynb are included as annotated versions of the original authors code (from https://github.com/mckenziephagen/ABCD_Stop_Signal). In these notebooks we both replicate their code as much as possible, and provide comments.

- Additional_Analysis.ipynb and Additional_Analysis_Prep.ipynb contains a number of new analyses. With the prep notebook used to setup the data for Additional_Analysis. This notebook in particular first covers a more systematic comparison of trying to determine which subset of subjects yielded the original authors results, followed by a number of new analysis (including calculating of SSRT). 

- Imaging_Analysis.ipynb contains an analysis done comparing the outputs of different varients of GLM's run on the Stop Signal Data.

- Violators_Imaging_Analysis.ipynb contains another imaging analysis focusing on determining how different "violators" GLM output is to non-violators. 

ABCD data is avaliable publically (after requested, and with the signing of a data use agreement).

If there are any difficulties in reproducing the code within this repository please reach out to sahahn@uvm.edu, or make an issue here.
