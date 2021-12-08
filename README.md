[![Review](https://github.com/globalbioticinteractions/degroot2020/actions/workflows/review.yml/badge.svg)](https://github.com/globalbioticinteractions/degroot2020/actions) [![Build Status](https://app.travis-ci.com/globalbioticinteractions/degroot2020.svg)](https://app.travis-ci.com/globalbioticinteractions/degroot2020) [![GloBI](https://api.globalbioticinteractions.org/interaction.svg?accordingTo=globi:globalbioticinteractions/degroot2020&refutes=true&refutes=false)](https://globalbioticinteractions.org/?accordingTo=globi:globalbioticinteractions/degroot2020)

Configuration to help Global Biotic Interactions (GloBI, https://globalbioticinteractions.org) index: 

de Groot, Michiel D., Iris Dumolein, Thomas Hiller, Attila D. Sándor, Tamara Szentiványi, Menno Schilthuizen, M. C. Aime, Annemieke Verbeken, and Danny Haelewaters. 2020. "On the Fly: Tritrophic Associations of Bats, Bat Flies, and Fungi" Journal of Fungi 6, no. 4: 361. https://doi.org/10.3390/jof6040361

The following precedure was followed to prepare the supplemental data for indexing:

1. download https://www.mdpi.com/2309-608X/6/4/361/s1 to ```jof-06-00361-s001.zip```
2. extract ```Table S3 All Laboulbeniales bat fly associations thus far.xlsx``` from ```jof-06-00361-s001.zip```
3. remove lines with decorative text like ```EASTERN HEMISPHERE``` and ```Table S3. Summary of all known Laboulbeniales associated with bat flies so far```
4. make repeated associations explicit by duplicating association information 

for instance:


 Laboulbeniales species | Country | Host species | Bat host | Reference(s)
 --- | --- | --- | --- | ---
Arthrorhynchus acrandros |  Italy | Phthiridium biarticulatum [as Nycteribia (Celepries) biarticulata] | Chiroptera gen. & sp. indet. | Merola A. Interessante ritrovamento di labulbeniologia cavernicola: Arthrorhynchus acrandros n. sp. (con considerazioni sul gen. Arthrorhynchus). Bol Soc Nat Napoli. 1952;60:1-30.
 |  | | | | Balazuc J. Notes sur les Laboulbéniales. III. Rectifications, synonymies et mises au point (suite). Bull. Mens. Soc. Linn. Soc. Bot. Lyon. 1971;40:211-216.

was filled in to be:

 Laboulbeniales species | Country | Host species | Bat host | Reference(s)
 --- | --- | --- | --- | ---
Arthrorhynchus acrandros |  Italy | Phthiridium biarticulatum [as Nycteribia (Celepries) biarticulata] | Chiroptera gen. & sp. indet. | Merola A. Interessante ritrovamento di labulbeniologia cavernicola: Arthrorhynchus acrandros n. sp. (con considerazioni sul gen. Arthrorhynchus). Bol Soc Nat Napoli. 1952;60:1-30.
Arthrorhynchus acrandros | Italy | Phthiridium biarticulatum [as Nycteribia (Celepries) biarticulata] | Chiroptera gen. & sp. indet.| Balazuc J. Notes sur les Laboulbéniales. III. Rectifications, synonymies et mises au point (suite). Bull. Mens. Soc. Linn. Soc. Bot. Lyon. 1971;40:211-216.

5. table was saved as a UTF8 encoded tab-separated file ```laboulbeniales_batfly_associations.tsv```
