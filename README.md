## Objectif
Dans ce Lab, mon objectif est d'explorer différentes architectures de réseaux de neurones pour des tâches de vision par ordinateur.
J'ai travaillé sur la classification d'images du dataset *MNIST* en utilisant plusieurs approches : 
*CNN,  modèles pré-entraînés (VGG16, AlexNet)*, ainsi que le *Vision Transformer (ViT)*, implémenté depuis zéro.
L'objectif final est de comparer les performances de ces modèles en termes de précision, score F1, perte et temps d'entraînement.

## Dataset
Le projet utilise le dataset MNIST, qui contient des images de chiffres manuscrits. Chaque image est en niveaux de gris, de taille 28x28 pixels, 
et est étiquetée avec le chiffre qu'elle représente, allant de 0 à 9.

## ## Synthèse
Le **Vision Transformer (ViT)**, implémenté à partir de zéro, présente une *précision plus faible* par rapport aux modèles *CNN* et *VGG16*.
Cela s'explique par la complexité du ViT, qui nécessite davantage de données et d'entraînement pour atteindre des performances optimales.
En revanche, les modèles *CNN* et *VGG16*, souvent pré-entraînés sur des ensembles de données plus vastes, bénéficient d'une meilleure généralisation
, notamment pour des tâches comme la classification d'images.


