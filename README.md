# Summary

This Universal Dependencies version of LLCT (Late Latin Charter Treebank) consists of an automated conversion of the LLCT2 treebank from the Latin Dependency Treebank (LDT) format into the Universal Dependencies standard.

# Introduction

The Universal Dependencies version of LLCT (Late Latin Charter Treebank) results from an automated conversion of the LLCT2 treebank from the Latin Dependency Treebank (LDT) format into the Universal Dependencies standard. LLCT2 is the second part of three LLCT treebanks, the first part (LLCT1) being available in LDT format (see Korkiakangas, in press) and the third part still under construction. 

LLCT2 contains 521 Early Medieval Latin original documents (charters) written in Tuscia (Tuscany), Italy, between AD 774 and 897. They all represent the legal (documentary) genre. Their language is a non-standard variety of Latin which differs both from Classical and Medieval Latin in terms of spelling, morphology, and syntax. 

For a general overview of the LLCT treebanks, see Korkiakangas (in press):
* preprint: https://researchportal.helsinki.fi/en/publications/late-latin-charter-treebank-contents-and-annotation
* The original annotation follows mainly the Guidelines for the Syntactic Annotation of Latin Treebanks (v. 1.3) (Bamman & al. 2007):
* https://itreebank.marginalia.it/doc/2007_Passa+Bamman+Crane+Raynaud_Guidelines%20Tb.pdf

However, the non-standard features are annotated following an additional set of rules described in Korkiakangas & Passarotti (2011) and in Cecchini & al. (in press):
* https://jlcl.org/content/2-allissues/12-Heft2-2011/16.pdf
* link to Cecchini & al. (in press)

The original data were annotated automatically using the first part of the LLCT treebank, i.e. LLCT1, as the training set and then corrected manually. The underlying text derives from four 19th-century editions: 
1) Memorie e documenti per servire all'istoria del Ducato di Lucca 5:2. Ed. by D. Barsocchini. Lucca: Francesco Bertini, 1837; 
2) Memorie e documenti per servire all'istoria del Ducato di Lucca 5:3. Ed. by D. Barsocchini. Lucca: Francesco Bertini, 1841; 
3) Memorie e documenti per servire all'istoria del Ducato di Lucca 4:1. Ed. by D. Bertini. Lucca: Francesco Bertini, 1818;
4) Memorie e documenti per servire all'istoria del Ducato di Lucca 4:2. Ed. by D. Bertini. Lucca: Francesco Bertini, 1836. 

Their text was manually corrected to meet modern editorial standards (see Korkiakangas, in press). Individual charters can be told apart by sentence identifiers, which refer to their numbers in the modern Chartae Latinae Antiquiores (ChLA) volumes. #!!!!Esempio

TBA A description of how the data was split into training, development, and test sets

# Acknowledgements

The conversion of the LLCT2 into the Universal Dependencies was realized by Flavio Massimiliano Cecchini and Marco Passarotti within the LiLa project (Linking Latin, https://lila-erc.eu/). The original LLCT2 was annotated by Timo Korkiakangas under projects funded by the University of Oslo and the Academy of Finland.

# References

* Bamman, D., Passarotti, M., Crane, G. & Raynaud, S. 2007. Guidelines for the syntactic annotation of Latin treebanks (v. 1.3). 
* Cecchini, F., Korkiakangas, T. & Passarotti, M. (in press). ‘A New Latin Treebank for Universal Dependencies: Charters between Ancient Latin and Romance Languages’, in LREC Proceedings (2020).
* Chartae Latinae Antiquiores: facsimile edition of the Latin charters, 2nd series: ninth century. Ed. by G. Cavallo, G. Nicolaj & al. Dietikon, Zürich: Urs Graf Verlag, 1997–2019.
* Korkiakangas, T. (in press). ‘Late Latin Charter Treebank: contents and annotation’, in Corpora 16 (2021). 
* Korkiakangas, T. & Passarotti, M. 2011. ‘Challenges in annotating Medieval Latin charters’, in Journal of Language Technology and Computational Linguistics 26, 103–114.

# Changelog

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.6
License: CC BY-SA 4.0
Includes text: yes
Genre: nonfiction legal
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Korkiakangas, Timo; Cecchini, Flavio Massimiliano; Passarotti, Marco
Contributing: elsewhere
Contact: flavio.cecchini@unicatt.it, timo.t.korkiakangas@gmail.com, marco.passarotti@unicatt.it
===============================================================================
</pre>

