# Utilisez les données publiques de l'OpenFoodFacts
*La startup Pur Beurre travaille connait bien les habitudes alimentaires françaises.L'équipe a remarqué que leurs utilisateurs voulaient bien changer leur alimentation mais ne savaient pas bien par quoi commencer.Leur idée est donc de créer un programme qui interagirait avec la base Open Food Facts pour en récupérer les aliments, les comparer et proposer à l'utilisateur un substitut plus sain à l'aliment qui lui fait envie.*

## Cahier des charges

### Description du parcours utilisateur
L'utilisateur est sur le terminal. Ce dernier lui affiche les choix suivants :
1. Quel aliment souhaitez-vous remplacer ? 
2. Retrouver mes aliments substitués.

L'utilisateur sélectionne 1. Le programme pose les questions suivantes à l'utilisateur et ce dernier sélectionne les réponses :
* Sélectionnez la catégorie. Plusieurs propositions associées à un chiffre. L'utilisateur entre le chiffre correspondant et appuie sur entrée
* Sélectionnez l'aliment. Plusieurs propositions associées à un chiffre. L'utilisateur entre le chiffre correspondant à l'aliment choisi et appuie sur entrée
* Le programme propose un substitut, sa description, un magasin ou l'acheter (le cas échéant) et un lien vers la page d'Open Food Facts concernant cet aliment.
* L'utilisateur a alors la possibilité d'enregistrer le résultat dans la base de données.

### Fonctionnalités
* Recherche d'aliments dans la base Open Food Facts.
* L'utilisateur interagit avec le programme dans le terminal.
* Si l'utilisateur entre un caractère qui n'est pas un chiffre, le programme doit lui répéter la question,
* La recherche doit s'effectuer sur une base MySql.

### Livrables
* Modèle physique de données (ou modèle relationnel) et utilisant l’outil informatique de votre choix (pas de dessin à main levée !).
* Script de création de votre base de données
* Document texte expliquant la démarche choisie, les difficultés rencontrées et les solutions trouvées et incluant le lien vers votre code source sur Github.
