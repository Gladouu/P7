# [Effectuez une prédiction de revenus](https://openclassrooms.com/fr/paths/65/projects/148/assignment) 

# PROJET EN COURS

#### Compétences évaluées : 

  - Maîtriser les bases de la statistique inférentielle
  - Maîtriser les bases des probabilités
  - Modéliser des données

<br>

## Scénario : 

Vous êtes employé dans une banque, présente dans de nombreux pays à travers le monde. Celle-ci souhaite cibler de nouveaux clients potentiels, plus particulièrement les jeunes en âge d'ouvrir leur tout premier compte bancaire.

Cependant, elle souhaite cibler les prospects les plus susceptibles d'avoir, plus tard dans leur vie, de hauts revenus.
L'équipe dans laquelle vous travaillez a donc reçu pour mission de créer un modèle permettant de déterminer le revenu potentiel d'une personne.
Très bien.

"Quelles informations avons-nous ?" demandez-vous à votre supérieur, qui vous répond : "À vrai dire... quasiment aucune : uniquement le revenu des parents, car nous allons cibler les enfants de nos clients actuels, ainsi que le pays où ils habitent. C'est tout ! Ah oui, une dernière chose : ce modèle doit être valable pour la plupart des pays du monde. Je vous laisse méditer là-dessus… Bon courage !"

Avec aussi peu de données disponibles, cela semble être un sacré challenge !

Ainsi, vous proposez une régression linéaire avec 3 variables :
  - le revenu des parents ;
  - le revenu moyen du pays dans lequel habite le prospect ;
  - l'indice de Gini calculé sur les revenus des habitants du pays en question. 

Ce projet ne traite que de la construction et de l'interprétation du modèle. Vous n'irez pas jusqu'à la phase de prédiction

<br>

## Les données : 
Ce fichier contient les données de la [World Income Distribution](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/data-projet7.csv), datée de 2008.

Cette base de données est composée principalement d'études réalisées au niveau national pour bon nombre de pays, et contient les distributions de revenus des populations concernées.

Vous téléchargerez également les indices de Gini estimés par la Banque mondiale, disponibles à [cette adresse](http://data.worldbank.org/indicator/SI.POV.GINI). Libre à vous de trouver également d'autres sources, ou de recalculer les indices de Gini à partir de la World Income Distribution.

Vous aurez également besoin de récupérer le nombre d'habitants de chaque pays présent dans votre base.

<br>

## Livrables : 

- le code Python ou R  permettant de répondre à l'ensemble de vos missions. Puisqu'il y a beaucoup de questions, faites attention à ce que votre code soit clair, qu'il délimite bien les différentes parties et questions, et qu'il soit correctement commenté 

- les graphiques générés, dans un format image .png ou .jpg 

<br>

## Overview : 

