# Veille Science des données
*15/11/2022

## Notions mathématiques

### Un vecteur et une matrice.

Un vecteur est un élément d'un espace vectoriel :
possible d'effectuer les opérations d'addition et de multiplication par un scalaire (nombre). L'addition et le produit par un nombre réel se font composante par composante.
Traditionnellement, n-uplet = collection ordonnée de n objets (nombres)
 
Les matrices sont des tableaux d'éléments = vecteur 2D.

https://fr.wikipedia.org/wiki/Vecteur
https://fr.wikipedia.org/wiki/Matrice_(math%C3%A9matiques)



### Variables indépendantes.

Paramètres qui varient sans être influencés par les autres paramètres.

https://www.alloprof.qc.ca/fr/eleves/bv/mathematiques/les-types-de-variables-m1108



### Une probabilité.

L'ensemble de tous les résultats possibles lors d'une expérience aléatoire sera appelé l'univers Ω des possibles.
Chaque résultat possible sera appelé une éventualité ω.
Rapport entre le nombre de cas favorables et le nombre de cas possibles.

https://www.alloprof.qc.ca/fr/eleves/bv/mathematiques/probabilites-m1334



### Espérance, Variance et Écart-Type.

* Espérance : valeur que l'on s'attend à trouver, en moyenne, si l'on répète un grand nombre de fois la même expérience aléatoire. (dés = 3,5)

* Variance : mesure de la dispersion des valeurs d'un échantillon ou d'une distribution de probabilité. (Elle exprime la moyenne des carrés des écarts à la moyenne, aussi égale à la différence entre la moyenne des carrés des valeurs de la variable et le carré de la moyenne.)

* Ecart-type : mesure de la dispersion des valeurs d'un échantillon ou d'une distribution de probabilité. Il est défini comme la racine carrée de la variance ou, de manière équivalente, comme la moyenne quadratique des écarts par rapport à la moyenne.

https://lecluseo.scenari-community.org/1S/Proba/co/G_EspVarAlea.html



### Une corrélation linéaire.

La corrélation entre plusieurs variables est une notion de liaison.
La corrélation linéaire entre variables quantitatives, c’est-à-dire l’ajustement d’une variable par rapport à l’autre par une relation affine (y = a * x + b).

https://fr.wikipedia.org/wiki/Corr%C3%A9lation_(statistiques)
https://www.alloprof.qc.ca/fr/eleves/bv/mathematiques/le-coefficient-de-correlation-lineaire-m1377



### Une moyenne, une médiane, un maximum, un minimum.

* Moyenne : Valeur représentative (sensible aux extrêmes) calculée comme la somme des valeurs d'une série divisée par le nombre de valeurs dans cette série
* Médiane : Autant de valeurs au-dessus qu’au-dessous, divise la série en deux groupes égaux
* Maximum : Valeur plus élevée
* Minimum : Valeur moins élevée

https://www.lelivrescolaire.fr/page/6964894



### Les quantiles

Divisent la distribution en plusieurs secteurs d'intérêt. Habituellement les quartiles :

Q1: 25% des valeurs sont inférieures au premier quartile
Q2 ou médiane: 50% des valeurs sont inférieures au deuxième quartile
Q3 : 75% des valeurs sont inférieures au troisième quartile

https://commentprogresser.com/statistique-parametre-statistiques-moyenne-mediane-etendue-ecart-type.html#moyenne



### Boxplot et Histogramme.

Boxplot : Représentation graphique du profil essentiel d'une série statistique quantitative (voir image, min, max, médiane, quartiles)
Histogramme : Représentation graphique de la répartition d'une variable aléatoire avec des colonnes correspondant chacune à une classe

https://fr.wikipedia.org/wiki/Bo%C3%AEte_%C3%A0_moustaches
https://fr.wikipedia.org/wiki/Histogramme



### Fonction de coût. ++

Fonction qui doit être optimisée = minimisée dans le cas de la fonction erreur de la régression linéraire.

https://en.wikipedia.org/wiki/Loss_function



### Une dérivée. ++

Dérivée d'une fonction (variable réelle) mesure l'ampleur du changement de la valeur de la fonction (valeur de sortie) par rapport à un petit changement de son argument (valeur d'entrée).
En analyse, le nombre dérivé en un « point » (réel) x x d'une fonction f f à variable et valeurs réelles est la pente de la tangente au graphe de f f au point ( x , f ( x ) ).C'est le coefficient directeur de l'approximation affine de f {\displaystyle f} en x x ;



### Descente de gradient. ++

Gradient :  vecteur indiquant comment une grandeur varie dans l'”espace”.

Algorithme d'optimisation différentiable = destiné à minimiser une fonction réelle différentiable définie sur un espace euclidien.

L'algorithme est itératif et procède donc par améliorations successives. Au point courant, un déplacement est effectué dans la direction opposée au gradient, de manière à faire décroître la fonction. Le déplacement le long de cette direction est déterminé par la technique numérique connue sous le nom de recherche linéaire. Cette description montre que l'algorithme fait partie de la famille des algorithmes à directions de descente.



### Équation normale. ++

En statistique, équation matricielle de la forme :

    tAAx = tAb

où

    A est une matrice de réels de dimensions n×p ;
    tA est la matrice transposée de A ;
    x est un vecteur réel inconnu de dimension p ;
    b est un vecteur connu de dimension n.

Elles sont utilisées pour effectuer une régression linéaire par la méthode des moindres carrés. De manière générale, il s'agit de la pseudo-solution du système linéaire

    Ax = b

que l'on ne peut pas résoudre de manière classique lorsque l'on a plus d'équations indépendantes que d'inconnues (n > p, système surdéterminé).

Matrice transposée:
La transposée tA d'une matrice A s'obtient par symétrie axiale par rapport à la diagonale principale de la matrice.

Méthode moindres carrés:
Permet de comparer des données expérimentales, généralement entachées d’erreurs de mesure, à un modèle mathématique censé décrire ces données.

https://www.youtube.com/watch?v=RQYnlgkgsUA

L'ajustement linéaire par la méthode des moindres carrés consiste à déterminer la droite d'ajustement passant par le point " moyen ".

https://fr.khanacademy.org/math/be-5eme-secondaire2h2/x741278364a599ec1:statistiques/x741278364a599ec1:droite-de-regression/a/linear-regression-review



### La loi Normale. ++

Utilisée pour modéliser des phénomènes naturels issus de plusieurs événements aléatoires. Loi de probabilité absolument continue qui dépend de deux paramètres : son espérance, un nombre réel noté μ, et son écart type, un nombre réel positif noté σ.



### Théorème Centrale Limite. ++

Etablit la convergence en loi de la somme d'une suite de variables aléatoires vers la loi normale. Intuitivement, ce résultat affirme qu'une somme de variables aléatoires indépendantes et identiquement distribuées tend (le plus souvent) vers une variable aléatoire gaussienne.

Ce théorème et ses généralisations offrent une explication de l'omniprésence de la loi normale dans la nature : de nombreux phénomènes sont dus à l'addition d'un grand nombre de petites perturbations aléatoires.



### Un test d'hypothèse. AS

En statistiques, un test, ou test d'hypothèse, est une procédure de décision entre deux hypothèses. Il s'agit d'une démarche consistant à rejeter ou à ne pas rejeter une hypothèse statistique, appelée hypothèse nulle, en fonction d'un échantillon de données.



### Chi-Square test. AS

A


### ANOVA. AS

A



### Une valeur propre. ++

A

https://fr.wikipedia.org/wiki/Valeur_propre_(synth%C3%A8se)



### Analyse en composante principale, Analyse factorielle des correspondances et Analyse des correspondances multiples. ++

A

https://fr.wikipedia.org/wiki/Analyse_en_composantes_principales



## Outils et librairies

### Anaconda, Jupyter-notebook.

A



### Librairies Python : Pandas, NumPy, Seaborn, Matplotlib, Plotly, Scikit-Learn, StatsModels, nltk, Pycaret.

A



### Librairies R : dplyr, ggplot2, tidyr, tidyverse, Shiny, plotly, Caret. ++

A



### Définition d'un ETL et exemples.

A



### Une base de données relationnelle.

A



### Power BI et Tableau.

A



## Apprentissage automatique

### La science des données.

A



### L’apprentissage automatique.

A



### L’apprentissage profond.

A



### Deep vs Machine Learning (dans quel cas, on utilise l’un ou l’autre).

A



### La différence entre l'apprentissage supervisé et l'apprentissage non supervisé.

A



### La classification et ses métriques d'évaluation.

A



### La régression et ses métriques d'évaluation.

A



### Le clustering et ses métriques de décision du k optimal et de la qualité des clusters.

A



### Traitement automatique du langage.

A



### La réduction de dimensions. ++

A

https://fr.wikipedia.org/wiki/R%C3%A9duction_de_la_dimensionnalit%C3%A9



### Le features engineering.

A

https://datascientest.com/feature-engineering



### La validation croisée, données d'entraînement, données de validation et données de test.

A

https://docs.aws.amazon.com/fr_fr/machine-learning/latest/dg/cross-validation.html



## Bonus : Aspect métiers

### Data Scientist

A



### Data Analyst

A



### Data Engineer