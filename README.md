In this repository it is possible to finde the raw output of the paper submitted to "Open Research Europe" (ORE) by "Irene Buselli, Luca Oneto, Carlo Dambra, Christian Verdonk Gallego, Miguel García Martínez, Anthony Smoker, Nnenna Ike, Tamara Pejovic, and Patricia Ruiz Martino" entitled "Natural language processing for aviation safety: extracting knowledge from publicly-available loss of separation reports"

In particular the files are:
- Topic_words_CEANITA: words and bigrams describing the 27 LDA topics identified in the CEANITA airprox reports, 12 of which have been considered significant and labelled by experts of the field (and are summarised in Table 3 of the paper). 
- Topic_words_UKAB: words and bigrams describing the 60 LDA topics identified in the UKAB airprox reports, 23 of which have been considered significant and labelled by experts of the field (and are summarised in Table 4 of the paper). Note report 2019207 was not included in the LDA analysis due to the different structure of the text w.r.t. the rest of the corpus.
- LDA_assignments_CEANITA: a matrix with one row per CEANITA report and one column per topic (12), representing how much each topic is estimated to be present in each report (information used to produce Figure 2 in the paper).
- LDA_assignments_UKAB: a matrix with one row per UKAB report and one column per topic (23), representing how much each topic is estimated to be present in each report (information used to produce Figure 3 in the paper). Note that report 2019207 is marked as NA due to its exclusion from the LDA analysis.
- Cluster_groups_CEANITA: for each CEANITA report, the assigned cluster (information used to produce Figure 4 in the paper). Note that reports 057_18 and 112_18 were not included in the clustering analysis due to missing information, and are therefore marked as NA.
- Cluster_groups_UKAB: for each UKAB report, the assigned cluster (information used to produce Figure 5 in the paper). Note that report 2019207 is marked as NA due to its missing values in topic assignments.
- TOKAI_A_CEANITA: the output of the application on CEANITA reports of Algorithm 1, which counts the presence of TOKAI taxonomy factors (part A) in each report. In each column name, letter F means "flight level subject" and letter G "ground level subject", while the + and - symbols stand for positively and negatively oriented (this information is represented in Figure 6 in the paper).
- TOKAI_A_UKAB: the output of the application on UKAB reports of Algorithm 1, which counts the presence of TOKAI taxonomy factors (part A) in each report (note a subsample of the initial corpus is here considered). In each column name, letter F means "flight level subject" and letter G "ground level subject", while the + and - symbols stand for positively and negatively oriented (this information is represented in Figure 7 in the paper).
