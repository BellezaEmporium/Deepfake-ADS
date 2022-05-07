# Deepfake-ADS
Algorithmes pour rapport ADS sur la reconstruction faciale à l'aide des Deepfakes.

## Pré-requis

CelebA : https://www.kaggle.com/jessicali9530/celeba-dataset (un autre dataset tel que NVidia FFHQ peut être utilisé, à votre guise)
Tensorflow (j'utilise la version GPU)
Python 3

Les modèles ont été tournés sur un Acer Nitro 5, Intel Core i7-9750H, NVidia GeForce 1660Ti. Les durées d'entraînement indiquées peuvent varier en fonction
des performances des machines

## Améliorations possibles

- Plus grand batch size
  - Contrainte : ressources limitées
- Plus d'entraînement
  - Contraintes : attention au surapprentissage / peut durer très longtemps
