# PR-OD-P1-lego-detection

## Algorithme de Détection d'Objet de Légos
Bienvenue dans le projet d'Algorithme de Détection d'Objet de Légos! Cet algorithme utilise le modèle pré-entrainé VGG16 ainsi qu'une méthode de tiling pour détecter et classifier différents types de légos à partir d'une image d'un tas de légos.

## Fonctionnalités Principales
Utilisation de VGG16: J'exploite le puissant modèle VGG16, pré-entrainé sur un grand ensemble de données, comme base pour mon algorithme de détection d'objets de légos.

Méthode de Tiling: Mon algorithme découpe l'image d'un tas de légos en tuiles plus petites, ce qui facilite l'identification des objets individuels.

Classification des Légos: Après avoir découpé l'image en tuiles, mon algorithme classifie chaque tuile en fonction du type de légos qu'elle contient. J'ai entraîné mon modèle pour reconnaître cinq classes de légos différentes, avec une classe spéciale pour les tuiles sans légos ("other").

Visualisation des Prédictions: Une fois que les prédictions sont effectuées, mon algorithme reconstruit l'image initiale en assemblant les tuiles tout en ajoutant une bordure colorée autour de chaque tuile en fonction de la classe prédite. Cela offre une visualisation claire des prédictions sur l'image complète.

## Performance
L'algorithme a été entraîné sur un ensemble de données comprenant 200 tuiles, avec cinq classes différentes (dont une pour les tuiles sans légos). Lors de l'évaluation sur un échantillon de test représentant 20% des données, mon algorithme a atteint une précision de 0.61, démontrant ainsi sa capacité à détecter et classer les légos.

## Utilisation
Pour utiliser cet algorithme, suivez ces étapes :

Assurez-vous d'avoir Python installé sur votre système.
Installez les bibliothèques nécessaires répertoriées dans le fichier requirements.txt.
Téléchargez le modèle VGG16 pré-entrainé.
Utilisez l'algorithme de tiling et de classification (Lego_detection.ipynb) pour :
- découper une image de tas de légos en tuiles 
- prédire la classe de chaque tuile.
- assembler les tuiles en une seule image et visualisez les prédictions.

## Contributions
Les contributions sont les bienvenues! Si vous avez des suggestions d'amélioration, des rapports de bugs ou des idées pour de nouvelles fonctionnalités, n'hésitez pas à ouvrir une issue ou à soumettre un pull request.

Merci d'avoir choisi mon algorithme de détection d'objets de légos. J'espère qu'il vous sera utile dans vos projets!