# Veille Science des données
*15/11/2022 - 17/11/2022*

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

https://fr.wikipedia.org/wiki/D%C3%A9riv%C3%A9e



### Descente de gradient. ++

Gradient :  vecteur indiquant comment une grandeur varie dans l'”espace”.

Algorithme d'optimisation différentiable = destiné à minimiser une fonction réelle différentiable définie sur un espace euclidien.

L'algorithme est itératif et procède donc par améliorations successives. Au point courant, un déplacement est effectué dans la direction opposée au gradient, de manière à faire décroître la fonction. Le déplacement le long de cette direction est déterminé par la technique numérique connue sous le nom de recherche linéaire. Cette description montre que l'algorithme fait partie de la famille des algorithmes à directions de descente.

https://fr.wikipedia.org/wiki/Gradient
https://fr.wikipedia.org/wiki/Algorithme_du_gradient

https://www.youtube.com/watch?v=MJkY-E_0K74
https://www.youtube.com/watch?v=HmAH6Ct1rc4



### Équation normale. ++

En statistique, équation matricielle de la forme :

    tA A x = tA b

où

    A est une matrice de réels de dimensions n × p ;
    tA est la matrice transposée de A ;
    x est un vecteur réel inconnu de dimension p ;
    b est un vecteur connu de dimension n.

Elles sont utilisées pour effectuer une régression linéaire par la méthode des moindres carrés. De manière générale, il s'agit de la pseudo-solution du système linéaire

    A x = b

que l'on ne peut pas résoudre de manière classique lorsque l'on a plus d'équations indépendantes que d'inconnues (n > p, système surdéterminé).

Matrice transposée:
La transposée tA d'une matrice A s'obtient par symétrie axiale par rapport à la diagonale principale de la matrice.

Méthode moindres carrés:
Permet de comparer des données expérimentales, généralement entachées d’erreurs de mesure, à un modèle mathématique censé décrire ces données.

L'ajustement linéaire par la méthode des moindres carrés consiste à déterminer la droite d'ajustement passant par le point " moyen ".

https://fr.wikipedia.org/wiki/%C3%89quation_normale
https://fr.wikipedia.org/wiki/Matrice_transpos%C3%A9e

https://www.youtube.com/watch?v=RQYnlgkgsUA
https://fr.khanacademy.org/math/be-5eme-secondaire2h2/x741278364a599ec1:statistiques/x741278364a599ec1:droite-de-regression/a/linear-regression-review



### La loi Normale. ++

Utilisée pour modéliser des phénomènes naturels issus de plusieurs événements aléatoires. Loi de probabilité absolument continue qui dépend de deux paramètres : son espérance, un nombre réel noté μ, et son écart type, un nombre réel positif noté σ.



### Théorème Centrale Limite. ++

Etablit la convergence en loi de la somme d'une suite de variables aléatoires vers la loi normale. Intuitivement, ce résultat affirme qu'une somme de variables aléatoires indépendantes et identiquement distribuées tend (le plus souvent) vers une variable aléatoire gaussienne.

Ce théorème et ses généralisations offrent une explication de l'omniprésence de la loi normale dans la nature : de nombreux phénomènes sont dus à l'addition d'un grand nombre de petites perturbations aléatoires.



### Un test d'hypothèse. AS

En statistiques, un test, ou test d'hypothèse, est une procédure de décision entre deux hypothèses. Il s'agit d'une démarche consistant à rejeter ou à ne pas rejeter une hypothèse statistique, appelée hypothèse nulle, en fonction d'un échantillon de données.

* Hypothèse nulle :

En statistiques (H0) est une hypothèse postulant l'égalité entre des paramètres statistiques (généralement, la moyenne ou la variance) de deux échantillons dont elle fait l’hypothèse qu'ils sont pris sur des populations équivalentes. Elle est toujours testée contre une hypothèse alternative qui postule soit la différence des données (test bilatéral), soit une inégalité (plus petit que ou plus grand que) entre les données (test unilatéral). 

https://fr.wikipedia.org/wiki/Test_statistique
https://fr.wikipedia.org/wiki/Hypoth%C3%A8se_nulle


### Chi-Square test. AS

A ETUDIER

En statistique, le test du khi carré, aussi dit du khi-deux, est un test statistique où la statistique de test suit une loi du χ2 sous l'hypothèse nulle.

Par exemple, il permet de tester l'adéquation d'une série de données à une famille de lois de probabilité ou de tester l'indépendance entre deux variables aléatoires.


https://fr.wikipedia.org/wiki/Test_du_%CF%87%C2%B2



### ANOVA. AS

A ETUDIER

En statistique, l'analyse de la variance (analysis of variance) est un ensemble de modèles statistiques utilisés pour vérifier si les moyennes des groupes proviennent d'une même population.

https://fr.wikipedia.org/wiki/Analyse_de_la_variance



### Une valeur propre. ++

A

https://fr.wikipedia.org/wiki/Valeur_propre_(synth%C3%A8se)



### Analyse en composante principale, Analyse factorielle des correspondances et Analyse des correspondances multiples. ++

A

https://fr.wikipedia.org/wiki/Analyse_en_composantes_principales



## Outils et librairies

### Anaconda, Jupyter-notebook.

Anaconda permet de faciliter l'installation des bibliothèques pour Python et R.

Distribution libre et open source.

Les versions de paquetages sont gérées par le système de gestion de paquets conda. 

Elle comprend également une interface graphique, Anaconda Navigator, qui est une alternative graphique à l'interface de ligne de commande (CLI).

La grande différence entre Conda et le gestionnaire de paquets pip consiste dans la gestion des dépendances des paquets.


Le Navigateur Anaconda est une interface graphique (GUI) incluse dans la distribution Anaconda, et qui permet aux utilisateurs de lancer des applications,  de gérer les librairies conda ...


Jupyter-notebook est un environnement de programmation interactif basé sur le Web permettant de créer des documents Jupyter Notebook. (langages JUlia PYThon et R !)
Format des documents = JavaScript Object Notation (JSON).


https://fr.wikipedia.org/wiki/Anaconda_(distribution_Python)

https://fr.wikipedia.org/wiki/Jupyter

https://www.youtube.com/watch?v=IT3SCr6xLqM



### Librairies Python : Pandas, NumPy, Seaborn, Matplotlib, Plotly, Scikit-Learn, StatsModels, nltk, Pycaret.

*Mainly opensource*

* Pandas
    When working with tabular data, such as data stored in spreadsheets or databases, pandas is the right tool for you. pandas will help you to explore, clean, and process your data. In pandas, a data table is called a DataFrame.


* NumPy
    Powerful N-dimensional arrays
    Fast and versatile, the NumPy vectorization, indexing, and broadcasting concepts are the de-facto standards of array computing today.

    Numerical computing tools
    NumPy offers comprehensive mathematical functions, random number generators, linear algebra routines, Fourier transforms, and more.


* Seaborn
    Data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.


* Matplotlib
    Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib makes easy things easy and hard things possible. 


* Plotly
    *DASH ? / low-code ?*
    Plotly's Python graphing library makes interactive, publication-quality graphs. Examples of how to make line plots, scatter plots, area charts, bar charts, error bars, box plots, histograms, heatmaps, subplots, multiple-axes, polar charts, and bubble charts. 


* Scikit-Learn
    - Simple and efficient tools for predictive data analysis
    - Built on NumPy, SciPy, and matplotlib


* StatsModels
    Python module that provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration.


* nltk
    *Natural Language Toolkit*
    nltk is a leading platform for building Python programs to work with human language data.


* Pycaret
    PyCaret is an open-source, low-code machine learning library in Python that automates machine learning workflows.


https://pandas.pydata.org/
https://numpy.org/
https://seaborn.pydata.org/
https://matplotlib.org/

https://plotly.com/
https://plotly.com/python/

https://scikit-learn.org/stable/index.html

https://www.statsmodels.org/stable/index.html
https://www.nltk.org/
https://pycaret.org/



### Librairies R : dplyr, ggplot2, tidyr, tidyverse, Shiny, plotly, Caret. ++

* dplyr
    dplyr is a grammar of data manipulation, providing a consistent set of verbs that help you solve the most common data manipulation challenges:

    mutate() adds new variables that are functions of existing variables
    select() picks variables based on their names.
    filter() picks cases based on their values.
    summarise() reduces multiple values down to a single summary.
    arrange() changes the ordering of the rows.

    One of the core packages of the tidyverse in the R programming language, dplyr is primarily a set of functions designed to enable dataframe manipulation in an intuitive, user-friendly way. Data analysts typically use dplyr in order to transform existing datasets into a format better suited for some particular type of analysis, or data visualization.

* ggplot
    ggplot2 is a system for declaratively creating graphics, based on The Grammar of Graphics (book). You provide the data, tell ggplot2 how to map variables to aesthetics, what graphical primitives to use, and it takes care of the details.

* tidyr
    The goal of tidyr is to help you create tidy data. Tidy data is data where:

    Every column is variable.
    Every row is an observation.
    Every cell is a single value.

    Tidy data describes a standard way of storing data that is used wherever possible throughout the tidyverse. If you ensure that your data is tidy, you’ll spend less time fighting with the tools and more time working on your analysis. Learn more about tidy data in vignette("tidy-data").

* tidyverse
    The tidyverse is an opinionated collection of R packages designed for data science. All packages share an underlying design philosophy, grammar, and data structures.

* Shiny
    Shiny is an R package that makes it easy to build interactive web apps straight from R. You can host standalone apps on a webpage or embed them in R Markdown documents or build dashboards. You can also extend your Shiny apps with CSS themes, htmlwidgets, and JavaScript actions. 

* plotly
    *see Python Libraries section*

* Caret
    caret termed as Classification and Regression Training uses many functions for training and plotting classification & regression models. It is one of the most widely used packages among R developers and in various machine learning competitions.

https://dplyr.tidyverse.org/
https://ggplot2.tidyverse.org/
https://tidyr.tidyverse.org/
https://www.tidyverse.org/

https://shiny.rstudio.com/

https://www.geeksforgeeks.org/7-best-r-packages-for-machine-learning/





### Définition d'un ETL et exemples.

Extract, Transform and Load

Simplifie les codes de traitement des données avec une interface visuelle intuitive.
Source et destination : fichier, BDD, service WEB etc...

Cette technologie repose sur :

    des connecteurs servant à exporter ou importer les données dans les applications (ex. : connecteur Oracle ou SAP…) ;
    des transformateurs qui manipulent les données (agrégations, filtres, conversions…) ;
    et des mises en correspondance (mappages).

Beaucoup de connecteurs disponibles ou développables en Java

Par ex : Talend Open Studio

https://www.youtube.com/watch?v=5jQthFuoXao&list=PL1aYsXmhJ1Wd1SNSV1fMci42yw6mdGxYI

https://www.youtube.com/watch?v=UrUiKhJ2EOo

https://fr.wikipedia.org/wiki/Extract-transform-load



### Une base de données relationnelle.

En informatique, une base de données relationnelle est une base de données où l'information est organisée dans des tableaux à deux dimensions appelés des relations ou tables.
Selon ce modèle relationnel, une base de données consiste en une ou plusieurs relations.
Les lignes de ces relations sont appelées des nuplets ou enregistrements.
Les colonnes sont appelées des attributs. 

Une composante N d'un n-uplet est une clé primaire lorsque par nature la valeur de cette composante est différente pour chaque n-uplet d'une relation, et que, pour une valeur donnée, il n'existe qu'un seul n-uplet dans toute la relation dont la composante a cette valeur (absence de redondance).

Une composante N d'un n-uplet est une clé étrangère lorsque les valeurs de cette composante sont des références à une clé primaire. Il y a une situation d'intégrité référentielle lorsqu'à chaque valeur de la clé étrangère A correspond une valeur de la clé primaire référencée B. 

https://fr.wikipedia.org/wiki/Base_de_donn%C3%A9es

https://fr.wikipedia.org/wiki/Base_de_donn%C3%A9es_relationnelle



### Power BI et Tableau.

Visualisation de données, tables et reportings.

https://www.youtube.com/watch?v=TYWSfnWnmJs

https://www.youtube.com/watch?v=uLj2EJwhPRQ



## Apprentissage automatique

### La science des données.

La science des données est l'étude de l’extraction automatisée de connaissance à partir de grands ensembles de données.

Plus précisément, la science des données est un domaine interdisciplinaire qui utilise des méthodes, des processus, des algorithmes et des systèmes scientifiques pour extraire des connaissances et des idées à partir de nombreuses données structurées ou non . Elle est souvent associée aux données massives et à l'analyse des données.

Elle utilise des techniques et des théories tirées de nombreux domaines dans le contexte des mathématiques, des statistiques, de l'informatique, de la théorie et des technologies de l'information, parmi lesquelles : l’apprentissage automatique, la compression de données et le calcul à haute performance. 

https://fr.wikipedia.org/wiki/Science_des_donn%C3%A9es



### L’apprentissage automatique.

L’apprentissage automatique ou machine learning réside dans le fait de rassembler une large quantité d’exemples afin de déterminer les schémas sous-jacents pour ensuite les utiliser afin d’effectuer des pronostics concernant de nouveaux exemples.

Le première phase est la conception de système qu’on appelle aussi phase d’apprentissage ou d’entraînement est l’estimation d’un modèle à partir de l’analyse des données. Cela comprend une estimation d’une densité de probabilité ou la résolution d’une tâche pratique comme la traduction d’un discours.

La seconde phase est une mise en production. Il est possible que des systèmes continuent leur apprentissage même en étant déjà en production. Après la détermination du modèle, on teste la seconde partie de données utile pour la réalisation de la tâche désirée.

https://datascientest.com/apprentissage-automatique



### L’apprentissage profond.

Technique de machine learning reposant sur le modèle des réseaux neurones: des dizaines voire des centaines de couches de neurones sont empilées pour apporter une plus grande complexité à l’établissement des règles.

https://datascientest.com/deep-learning-definition



### Deep vs Machine Learning (dans quel cas, on utilise l’un ou l’autre).

Les modèles de Deep learning ont tendance à bien fonctionner avec une grande quantité de données alors que les modèles d’apprentissage automatique plus classique cessent de s’améliorer après un point de saturation.

(++image)

https://datascientest.com/deep-learning-definition



### La différence entre l'apprentissage supervisé et l'apprentissage non supervisé.

En fonction des informations à disposition durant la phase d’apprentissage, l’apprentissage est qualifié distinctement. Si les données sont étiquetées, on parle d’apprentissage supervisé. Dans le cas où les données ne sont pas étiquetées, il s’agit alors d’apprentissage non supervisé.

https://datascientest.com/apprentissage-automatique



Classification, régression et clustering sont trois catégories d'algorithmes de ML selon le type de données et d'objectif.

https://www.techjunkgigs.com/clustering-classification-and-regression-2/


### La classification et ses métriques d'évaluation.

Algorithme supervisé utilisant des données discrètes.

https://www.techjunkgigs.com/clustering-classification-and-regression-2/



### La régression et ses métriques d'évaluation.

A
https://www.techjunkgigs.com/clustering-classification-and-regression-2/



### Le clustering et ses métriques de décision du k optimal et de la qualité des clusters.



https://www.techjunkgigs.com/clustering-classification-and-regression-2/



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

Dans l'ordre d'utilisation de la donnée :


### Data Engineer

Organise, structure et met à disposition la donnée.


### Data Analyst

Explore et analyse la donnée, tire les informations intéressantes et les affiche (DataViz et BI).


### Data Scientist

Construit des modèles prédictifs.


https://www.youtube.com/watch?v=1pARcazj-Mc