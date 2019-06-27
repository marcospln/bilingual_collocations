Bilingual collocations data sets
--------------------------------

_Marcos Garcia, Marcos García-Salido, Margarita Alonso-Ramos_

_Version 1.0: June 25, 2019_

This folder contains the gold-standard data and the output of the evaluated systems of the following paper:

  * _Weighted compositional vectors for translating collocations using monolingual corpora_. In Proceedings of the International Conference ‘Computational and Corpus-based Phraseology’ (Europhras 2019) (forthcoming).

'gold' folder contains the English-Portuguese (en-pt) and English-Spanish (en-es) gold-standard data sets for 'adj-noun' and 'verb-obj' collocations.

Folders 'top1' and 'top3' contain the output translations for the different systems evaluated. There is an 'en-pt' and an 'en-es' subfolder in both 'top1' and 'top3'.

Each file includes the source collocation in English in the first column, and different translations in Portuguese or Spanish after that. Columns are separated by semicolons (;), and every collocation is lemmatized and printed in a 'base,collocate' format separated by a comma (,). The output of the systems also have a floating-point number after the collocate, which is the confidence value of the translation.
