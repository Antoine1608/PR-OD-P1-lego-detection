Détection d'objet (légos)
# Présentation
L'algorithme suivant permet de détecter le nombre et le type de légos sur une image

On crée d'abord un dataset d'entraînement à partir de "tiles" représentant des légos mais également l'absence de légos.

On entraîne un modèle VGG16 en mode transfer learning sur ce dataset

Pour appliquer ce modèle sur une image qui représente un groupe de légos 