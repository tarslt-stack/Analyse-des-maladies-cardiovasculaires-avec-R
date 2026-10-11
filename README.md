# Analyse-des-maladies-cardiovasculaires-avec-R
J'ai voulu comprendre quels profils de patients sont les plus touchés par les maladies cardiovasculaires. Pour ça, j'ai analysé le dataset *Heart Disease* (Cleveland) de l'UCI Machine Learning Repository avec R et RStudio : de l'import des données jusqu'aux graphiques.

## 🛠️ Ce que j'ai utilisé
R, RStudio et les graphiques de base de R (`plot`, `barplot`, `hist`, `boxplot`, `pie`).

## 🔄 Comment j'ai procédé
1. **J'ai importé et préparé les données** :
   - chargement direct depuis l'UCI et renommage des 14 colonnes
   - la variable cible regroupée en deux catégories : maladie (Oui) ou non (Non)
   - suppression des lignes avec valeurs manquantes
   - conversion des variables en qualitatives ou quantitatives, puis recodage en libellés lisibles (ex. « Femme » / « Homme », « Angine stable »...)
2. **J'ai fait des statistiques descriptives** :
   - effectifs et pourcentages pour les variables qualitatives
   - minimum, quartiles, médiane, moyenne, maximum, variance et écart-type pour les variables quantitatives
3. **J'ai créé des graphiques** :
   - diagrammes à barres (sexe, douleurs thoraciques)
   - diagramme circulaire (présence de maladie)
   - histogramme (tension artérielle au repos)
   - boîtes à moustaches (âge, tension), seules ou croisées avec la présence de maladie
   - diagramme à barres croisées (maladie selon le sexe)

## 🚀 Pour tester le projet
1. Installer [R](https://cran.r-project.org/) et [RStudio](https://posit.co/download/rstudio-desktop/)
2. Ouvrir le script `.R` dans RStudio
3. Exécuter le code : les données sont téléchargées automatiquement depuis l'UCI, il n'y a aucun fichier à ajouter

## 📚 Source des données
[Heart Disease Data Set – UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+disease)

## 👋 À propos
Projet réalisé par **<Ton nom>**. N'hésite pas à me laisser un commentaire : [GitHub](https://github.com/...)
