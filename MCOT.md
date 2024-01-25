# Titre
Génération de terrain de jeux aléatoire en respectant des critères de qualités
## Motivations pour le choix du sujet
Ayant une passion pour les jeux vidéos, je souhaite appronfondire mes connaissances sur les technologies en rapport avec les jeux vidéos. Et c'est à ce moment là où j'ai su que dans un jeux vidéo appelé no man's sky, théoriquement il y a un monde plus grand en terme d'espace que la terre et même qu'il est théoriquement infini. Ainsi, ça a attiré ma curiosité, et après plusieurs recherches j'ai décidé d'explorer
cette technologie et cette algorithme pour mon TIPE.

## Ancrage du sujet au thème de l'année
Mon thème rentre dans la catégorie des jeux, avec surtout le domaine du jeux vidéo.

## Positionnement thématique (par ordre de priorité décroissante)

1.Informatique : Pratique et théorique (théorie de l'information)
2.Mathématiques : Probabilités
3. Physique: Physique théorique (Entropie de shannon)


## Mots-clés (par ordre de priorité décroissante)

1.Génération Procédurales (WFC)
2. Search based implémentation
3.Entropie de shannon
4. Probabilités
5  Théorie de l'information


## Bibliographie commentée (max 650 mots)

La génération aléatoire est un sujet d'étude d'informatique qui affecte de nombreux domaines et de nombreux programmes, impactant toutes les activités numériques.
Le domaine des jeux vidéos, activités prenant de plus en plus de place dans le numérique,fait l'object d'une attention particulière des développeurs et des cherchers. C'est dans ce dernier que se développe des techniques numériques innovante, dont particulièrement Wave fonction collapse.

On appelle Wave fonction collapse un algorithme de génération procédurales, destinées à la création de terrain de jeux aléatoires. Ce dernier va, comme le nom l'indique, agir comme une vague en traitant les données les plus faciles à analyser en premier, pour accumuler plus de données sur celles qui sont difficiles à traiter. Ainsi, on retrouve l'analogie de la vague car chaque données dépend de ces voisins, et un changement entraine une réaction en chaînes. [1][2]

Le terrain de jeux sur un jeux vidéo est son principal pillier. De plus, de nos jours, la tendance est vers un open world n'ayant point de limite. En effet, certaines licenses ont développé des techniques suffisante pour avoir une carte presque infini, comme à titre d'illustration No Man's Sky oû il faudrait 744 milliars d'années pour explorer l'entièreté du jeux vidéo. Modéliser cette technique de génération procédural permet donc de comprendre la prouesse technique et le potentiel de cette algorithme. [4]

Une approche théorique de l'algorithme peut être réalisé par l'étude de l'entropie de shanon, qui modélise la priorité des données pour les traitées. [1][8]

Du fait de la complexité de l'implémentation en 3 dimension, les premières utilisations de cette simulation numérique à été fait en 2 dimensions. Cette simplification permet un avantage, qui est la simplification du calcul d'entropie. En effet, en deux dimensions, les relations entre les images sont seulement en fonction de 4 composantes directionnel: haut, bas, droite et gauche. De plus, la cohérence physique n'a pas besoin d'être respectés. 
Cette modélisation 2D à été réalisé avec des Tétrominos, qui ont l'atouts de pouvoir constituer facilement un pavage. [3]

Cependant, pour confirmer l'efficacité de notre réalisation, il est nécessaire de pouvoir déterminer des critères de qualités pour analyser et verifier la pertinence de notre génération procédurales. Ces critères peuvent être en fonction de l'accescibilités, la difficulté, les possibilités d'actions ou les possibilités de porgressions. [1] [4]














## Problématique retenue (max 50 mots)
Comment générer un important espace de jeu, tout en conservant une logique et une certain qualité?

## Objectifs du TIPE (max 100 mots)

2. Implémentation de l'algorithme WFC avec l'utilisation des Tétrominos.
3. Mise en place de critère de qualités (Création d'une base probabiliste pour étudier la pertinence de notre terrain de jeux)
4. Vérifier sur plusieurs générations la pertinence de l'algorithme WFC au vu de nos critères

## Références bibliographiques (2 à 10 références)

1. Thèse de Raphaël Bailly : Génération procédurale de niveaux de jeu alliant approche constructive et optimisation. https://theses.hal.science/tel-03971457 [1]
2. Mxgmn (pogrammation github) : https://github.com/mxgmn/WaveFunctionCollapse [2]
3. The coding train ( tutoriel d'implémentation WFC) https://www.youtube.com/watch?v=rI_y2GAlQFM [3]
4. Michael Cook (automate pour générer un terrain de jeu sous forme de Cave) [4]
6. Robert Heaton (https://robertheaton.com/2018/12/17/wavefunction-collapse-algorithm/) [6]
7. Mateusz Bugaj 
https://medium.com/swlh/wave-function-collapse-tutorial-with-a-basic-exmaple-implementation-in-python-152d83d5cdb1 [7]
8. Techno-science : https://www.techno-science.net/definition/10716.html [8]
10. 
11. 

