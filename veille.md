# Veille Science des données
## Notions mathématiques
### Un vecteur et une matrice.

* From WIKIPEDIA ++

Un vecteur est un élément d'un espace vectoriel :
possible d'effectuer les opérations d'addition et de multiplication par un scalaire (nombre). L'addition et le produit par un nombre réel se font composante par composante.
traditionnellement, n-uplet = collection ordonnée de n objets (nombres)
 
Les matrices sont des tableaux d'éléments = vecteur 2D.

### Variables indépendantes.
Paramètres qui varient sans être influencés par les autres paramètres.

### Une probabilité.
L'ensemble de tous les résultats possibles lors d'une expérience aléatoire sera appelé l'univers Ω des possibles.
Chaque résultat possible sera appelé une éventualité ω.
Rapport entre le nombre de cas favorables et le nombre de cas possibles.

### Espérance, Variance et Écart-Type.
* Espérance : valeur que l'on s'attend à trouver, en moyenne, si l'on répète un grand nombre de fois la même expérience aléatoire. (dés = 3,5)

* Variance : mesure de la dispersion des valeurs d'un échantillon ou d'une distribution de probabilité. (Elle exprime la moyenne des carrés des écarts à la moyenne, aussi égale à la différence entre la moyenne des carrés des valeurs de la variable et le carré de la moyenne.)

* Ecart-type : mesure de la dispersion des valeurs d'un échantillon ou d'une distribution de probabilité. Il est défini comme la racine carrée de la variance ou, de manière équivalente, comme la moyenne quadratique des écarts par rapport à la moyenne.

https://lecluseo.scenari-community.org/1S/Proba/co/G_EspVarAlea.html



### Une corrélation linéaire.
La corrélation entre plusieurs variables est une notion de liaison.
La corrélation linéaire entre variables quantitatives, c’est-à-dire l’ajustement d’une variable par rapport à l’autre par une relation affine (y = a * x + b).


### Une moyenne, une médiane, un maximum, un minimum.
* Moyenne : Valeur représentative (sensible aux extrêmes)
* Médiane : Autant de valeurs au-dessus qu’au-dessous
* Maximum : Valeur plus élevée
* Minimum : Valeur moins élevée


### Les quantiles divisent la distribution en plusieurs secteurs d'intérêt. Habituellement les quartiles :

Q1: 25% des valeurs sont inférieures au premier quartile
Q2 ou médiane: 50% des valeurs sont inférieures au deuxième quartile
Q3 : 75% des valeurs sont inférieures au troisième quartile

https://commentprogresser.com/statistique-parametre-statistiques-moyenne-mediane-etendue-ecart-type.html#moyenne



### Boxplot et Histogramme.
Boxplot : 
Histogramme :
Représentation graphique de la répartition d'une variable aléatoire avec des colonnes correspondant chacune à une classe.


### Fonction de coût.



### Une dérivée.
Dérivée d'une fonction (variable réelle) mesure l'ampleur du changement de la valeur de la fonction (valeur de sortie) par rapport à un petit changement de son argument (valeur d'entrée).
En analyse, le nombre dérivé en un « point » (réel) x x d'une fonction f f à variable et valeurs réelles est la pente de la tangente au graphe de f f au point ( x , f ( x ) ).C'est le coefficient directeur de l'approximation affine de f {\displaystyle f} en x x ;


### Descente de gradient.
Gradient :  vecteur indiquant comment une grandeur varie dans l'”espace”.

Algorithme d'optimisation différentiable = destiné à minimiser une fonction réelle différentiable définie sur un espace euclidien.

L'algorithme est itératif et procède donc par améliorations successives. Au point courant, un déplacement est effectué dans la direction opposée au gradient, de manière à faire décroître la fonction. Le déplacement le long de cette direction est déterminé par la technique numérique connue sous le nom de recherche linéaire. Cette description montre que l'algorithme fait partie de la famille des algorithmes à directions de descente.



### Équation normale.
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

### La loi Normale.
Utilisée pour modéliser des phénomènes naturels issus de plusieurs événements aléatoires. Loi de probabilité absolument continue qui dépend de deux paramètres : son espérance, un nombre réel noté μ, et son écart type, un nombre réel positif noté σ.



### Théorème Centrale Limite.
Etablit la convergence en loi de la somme d'une suite de variables aléatoires vers la loi normale. Intuitivement, ce résultat affirme qu'une somme de variables aléatoires indépendantes et identiquement distribuées tend (le plus souvent) vers une variable aléatoire gaussienne.

Ce théorème et ses généralisations offrent une explication de l'omniprésence de la loi normale dans la nature : de nombreux phénomènes sont dus à l'addition d'un grand nombre de petites perturbations aléatoires.



### Un test d'hypothèse.
### Chi-Square test.
### ANOVA.


### Une valeur propre.

### Analyse en composante principale, Analyse factorielle des correspondances et Analyse des correspondances multiples.

## Outils et librairies

### Anaconda, Jupyter-notebook.

### Librairies Python : Pandas, NumPy, Seaborn, Matplotlib, Plotly, Scikit-Learn, StatsModels, nltk, Pycaret.

### Librairies R : dplyr, ggplot2, tidyr, tidyverse, Shiny, plotly, Caret.

### Définition d'un ETL et exemples.

### Une base de données relationnelle.

### Power BI et Tableau.


## Apprentissage automatique

### La science des données.
### L’apprentissage automatique.
### L’apprentissage profond.
### Deep vs Machine Learning (dans quel cas, on utilise l’un ou l’autre).
### La différence entre l'apprentissage supervisé et l'apprentissage non supervisé.
### La classification et ses métriques d'évaluation.
### La régression et ses métriques d'évaluation.
### Le clustering et ses métriques de décision du k optimal et de la qualité des clusters.
### Traitement automatique du langage.
### La réduction de dimensions.
### Le features engineering.
### La validation croisée, données d'entraînement, données de validation et données
de test.


## Bonus : Aspect métiers

Définissez les métiers de Data Scientist, Data Analyst et Data Engineer. Donnez la
différence entre les trois.
