# Business_intelligence_donnees_sante_public
Analyse statistique multivariée et présentations graphiques interactives sur un jeu de données de santé public

L'agence "Santé publique France" a lancé un appel à projets pour rendre les données de santé plus accessibles. L’agence souhaite faire explorer et visualiser des données, pour que ses agents puissent les exploiter.

Le nettoyage des données :

❒ les valeurs manquantes de chaque colonnes ont été identifiées, quantifiées et traitées. Mise en œuvre des différentes méthodes de traitement des valeurs manquantes, adaptées aux variables concernées (médiane, mise à 0, IterativeImputer, KNN, suppression, …).

❒ pour chaque variable, les outliers d’un point de vue statistique ont été mis en évidence et analysés, afin de s’assurer s’il s’agit de valeurs aberrantes ou atypiques. Les éventuelles valeurs aberrantes ont été identifiées, quantifiées et traitées, en tenant compte du contexte métier

❒ plusieurs fonctions ont été écrites, testées et utilisées pour nettoyer le jeu de données.

❒ la démarche de nettoyage des données est visible dans la structure du document (découpage du document en partie avec des titres clairs et mis en évidence, des commentaires à l’intérieur des parties pour expliciter la démarche, …)

L’analyse statistique multivariée : 

❒ au préalable une analyse univariée est réalisée (en fonction des variables : describe(), boxplot, nuage de points, diagramme de densité, barplot, camembert, …).

❒ différents graphiques d’analyse bi-variée sont présentés et analysés (pairplot ou graphique variables numérique / numérique, graphique variables numérique / catégorielle, graphique variables catégorielle/ catégorielle, heatmap de corrélation).

❒ analyse descriptive expliquée et justifiée sur le jeu de données avec une ACP

❒ analyse explicative expliquée et justifiée sur le jeu de données avec une ANOVA

❒ plusieurs fonctions ont été écrites, testées et utilisées pour effectuer une analyse statistique multivariée.
