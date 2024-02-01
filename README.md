# Projet-10-Detectez-de-faux-billets-avec-R-ou-Python

![image](https://github.com/BM-Aurelie78/Projet-10-Detectez-de-faux-billets-avec-R-ou-Python/assets/153644306/0721c593-7157-4f90-94b8-1e59e272510d)


### I. Contexte et but du projet
L’ONCFM (Organisation nationale de lutte contre le faux-monnayage) est une organisation publique ayant pour objectif de mettre en place des méthodes d’identification des contrefaçons des billets en euros. 
Il faut donc mettre en place un algorithme capable de différencier automatiquement les vrais des faux billets à partir de ses caractéristiques dimensionnelles.

### II. Source des données
1. Le fichier "billets.csv" contenant des informations sur les six informations géométriques sur un billet :
- length : la longueur du billet (en mm) ;
- height_left : la hauteur du billet (mesurée sur le côté gauche, en mm) ;
- height_right : la hauteur du billet (mesurée sur le côté droit, en mm) ;
- margin_up : la marge entre le bord supérieur du billet et l'image de celui-ci (en mm) ;
- margin_low : la marge entre le bord inférieur du billet et l'image de celui-ci (en mm) ;
- diagonal : la diagonale du billet (en mm).

Ces informations seront utiliser par l’algorithme.

2. Le fichier "billets_production.csv" sera utiliser pour tester l'efficacité de l'algorithme.

### III. Outil(s) utilisé(s)

Python 

### IV. Nettoyage et préparation des données

1. Vérifier si les types de données des variables sont cohérents et si les valeurs sont manquantes.
2. Effectuer une régression linéaire multiple pour remplacer les valeurs manquantes

### V. Analyse exploratoire des données

À partir du fichier  "billets.csv" contenant les dimensions de plusieurs billets, concevoir un algorithme capable de déterminer si chaque billet est vrai ou faux en se basant 
uniquement sur ses dimensions.

L' autre fichier nommé "billets_production.csv" servira à tester l'algorithme en fonction du format type du fichiers de billets

Il faut mettre en concurrence deux méthodes de prédiction : 
- une régression logistique classique ; 
- un k-means, duquel seront utilisés les centroïdes pour réaliser la prédiction. 
Cet algorithme se devra d’être naturellement le plus performant possible pour identifier un maximum de faux billets au sein de la masse de billets analysés chaque jour. 

Pour une évaluation optimale des modèles, nous souhaitons avoir une analyse des nombres de faux positifs et faux négatifs via une matrice de confusion.

### VI. Résultats/constats

Pour la régression logistique

### VII. Recommandations




### 9. Limitations


### 10. Références
