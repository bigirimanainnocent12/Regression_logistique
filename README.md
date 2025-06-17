# *📊 Contexte*
Bob veut prédire la catégorie de prix d’un téléphone (0 à 3) en fonction de ses caractéristiques techniques (RAM, Bluetooth, 4G, etc.).

# *🔍 Étapes principales du script* 

1. Chargement des données depuis Kaggle.
   
2. Prétraitement :
- Séparation des variables qualitatives (booléennes) et quantitatives.
- Encodage de la variable cible price_range.
- Séparation des données en ensemble d'entraînement et de test.
  
3. Pipeline de modélisation :
- Standardisation des variables quantitatives.
- Régression logistique avec recherche d’hyperparamètres via GridSearchCV.
4. Évaluation du modèle :
- Précision, rappel, exactitude.
- Matrice de confusion.
- Rapport de classification.
- Aire sous la courbe ROC.
- Sauvegarde du modèle avec joblib.
# *✅ Résultats produits :*

- Histogramme des probabilités prédites.
- Rapport de classification complet.
- Score ROC AUC pour évaluer la performance multiclasse.
- Modèle sauvegardé dans modele.pkl.
