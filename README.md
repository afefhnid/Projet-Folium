# Projet Folium (1 journée)

Cadre:

Projet par équipe de deux 

Objectif pédagogique :

1) Requête https://lefooding.com
2) Manipulation de json
3) Nettoyer et formaliser des informations dans un Dataframe
4) Dataviz cartographique (Folium)

Je souhaite réaliser une application qui permettrait de localiser des restaurants dans une 
ville et permettre à l’utilisateur de filtrer les résultats par type de cuisine, par arrondissement 
ou code postal. Ce n’est pas original mais c’est fun;)
En effet, nous savons collecter le retour d’une requête (via la librairie requests de python).
En analysant le jeu de reception et envoi de requete (via le terminal de mon navigateur), je 
peux intercepter la requête contenant le json qui remplit la page .
Je connais notamment un site, assez mal protégé qui pourrait nous fournir ces in
formations

https://lefooding.com

Méthodologie :
0) Récupérer
 une/des liste de restaurants ou bars dont vous pouvez extraire des spécificités
ex : Restaurant thai, bar à vin, bar à coktail, …
Pour chaque établissement, récupérer également ses coordonnées GPS
1) Ranger proprement ces informations dans une BDD de votre choix
2) Utiliser
 Folium (librairie python) et entraînez vous à y placer les établissements scrappés




Question Bonus :
Donner un définition vulgarisée de ces metrics/concepts de statistique:

-probabilité : La probabilité d'un événement est un nombre réel compris entre 0 et 1. Plus ce nombre est grand, plus le risque, ou la chance, que l'événement se produise est grand. 
-moyenne : Quotient de la somme de plusieurs valeurs par leur nombre. total des notes/nb de notes = moyenne de la classe
-médiane: La médiane est la droite joignant un sommet d'un triangle au milieu du côté opposé. En statistiques, la médiane est le nombre qui partage une série statistique en deux parties de même effectif ; critère de position
-espérance:L'espérance mathématique est une valeur statistique, utilisée en économie, notamment dans le domaine des jeux de hasard ou des assurances, qui consiste à faire la moyenne de probabilités pour déterminer si le résultat est équitable.
-Variance
-écart-type
-quantile
-distribution

