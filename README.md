# CONCEVEZ UNE APPLICATION AU SERVICE DE LA SANTE PUBLIQUE

## Deuxième projet de ma formation de Data Scientist

## Contexte

<p align="center">
  <img src="logo_sante_publique.png" alt="Texte alternatif">
</p>

L'agence "Santé publique France" a lancé un appel à projets pour trouver des idées innovantes d’applications en lien avec l'alimentation. Vous souhaitez y participer et proposer une idée d’application.

## Préambule
Ce projet a été réalisé en langage Python dans des notebooks Jupyter.

## Les données
Le jeu de données Open Food Facts est disponible soit sur le site officiel (https://world.openfoodfacts.org/), soit à ce lien en téléchargement: https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-scientist/P2/fr.openfoodfacts.org.products.csv.zip. Les variables sont définies à cette adresse: https://world.openfoodfacts.org/data/data-fields.txt.

Les champs sont séparés en quatre sections:
1. Les informations générales sur la fiche du produit: nom, date de modification, etc...
2. Un ensemble de tags: catégorie du produit, localisation, origine, etc...
3. Les ingrédients composant les produits et leurs éventuels additifs.
4. Des informations nutrionnelles: quantité en grammes d'un nutriment pour 100 grammes du produit.

## Missions
1. Traitement du jeu de données en:
   - Réfléchissant à une idée d’application.
   - Repérant des variables pertinentes pour les traitements à venir, et nécessaires pour l'idée d’application.
   - Nettoyant les données en :
       - Mettant en évidence les éventuelles valeurs manquantes, avec au moins 3 méthodes de traitement adaptées aux variables concernées.
       - Identifiant et en quantifiant les éventuelles valeurs aberrantes de chaque variable.
2. Production de visualisations tout au long de l'analyse afin de mieux comprendre les données et réalisation d'une analyse univariée pour chaque variable intéressante, afin de synthétiser son comportement.
3. Confirmation ou infirmation des hypothèses à l’aide d’une analyse multivariée, ainsi que la réalisation de tests statistiques appropriés pour vérifier la significativité des résultats.
4.  Justification de l'idée d’application: identification des arguments justifiant la faisabilité (ou non) de l’application à partir des données d'Open Food Facts.

## Contenu du dépôt
1. Le notebook de nettoyage des données: notebook_1_nettoyage.ipynb.
2. Le notebook d'analyses exploratoires des données comprenant les analyses uni- et multivariées, une réduction dimensionnelle non-supervisé (Analyse en Composantes Principales (PCA ou ACP) ainsi que de l'apprentissage supervisé: notebook_2_exploration.ipynb. 
3. Le support de présentation pour la soutenance sous format pdf: support_presentation_3.pdf.
4. La liste des librairies nécessaires à la réalisation du projet: requirements.txt.
5. Le logo de la société sous format .png: logo_sante_publique.png.

## Compétences acquises ou montée en compétences
1. Montée en compétence dans le nettoyage des données et dans l'analyse exploratoire des données.
2. Analyses statistisques et matrice des corrélations.
3. Réduction de nombre de variables de façon non-supervisée (ACP).
4. Premier pas dans l'apprentissage supervisé.

## Auteur
**Coline Plé**
