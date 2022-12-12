# Property price in Tunisia
Ce code permet de créer une carte de Tunisie avec des cercles indiquant les prix moyens de l'immobilier dans chaque gouvernorat. Pour commencer, chargez les bibliothèques nécessaires en utilisant la commande library. Ensuite, utilisez les commandes getData et read.csv pour importer la cartographie de la Tunisie et les données sur les prix de l'immobilier. Utilisez les fonctions cbind, coordinates, data.frame, match, et unlist pour extraire les coordonnées des centroides des gouvernorats et les joindre aux données sur les prix de l'immobilier. Utilisez les fonctions bbox et sum pour calculer les rayons des cercles sur la carte, puis tracez la carte en utilisant les fonctions plot et symbols. Ajoutez une légende en utilisant la fonction legend.
## Utilisation
Pour installer les bibliothèques nécessaires, utilisez la commande install.packages suivie du nom de la bibliothèque.

```R
install.packages("dplyr", "maptools", "sp", "shapefiles", "raster")
```
