# Enron Email Datasets

A lot of work has already been formed on the Enron Email Dataset. K. Krasnow Waterman identifies the following datasets in his 2006 report:

| Dataset | Records | Users |
|---------|---------|-------|
| FERC / Aspen | 1,000,000+ | 158 |
| CALO | 517,431 | 151 |
| USC | 252,759 | 161 |
| CMU Intermedate | 619,446 | 158 |
| CMU | 200,399 | 158 |
| UMass | ? | 149 |
| Queens University | ? | ? |

He makes note that different datasets identify different numbers of users. EDRP has identified [158 FERC custodians and 150 CALO users](https://github.com/enrondata/enrondata/blob/master/data/misc/edo_enron-custodians.txt). The FERC list was generated by taking a case insensitive list of the iCONECT ORIGIN column and the CALO list was compiled using a directory listing of the CMU hosted tar file. Looking at the comparison quickly, it appears likely that some of the users that were eliminated from the CALO dataset were misspellings.

In follow up posts, individual datasets will be discussed regarding their applicability for different purposes.