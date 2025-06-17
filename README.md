# *📊 Contexte*
Bob veut prédire la catégorie de prix d’un téléphone (0 à 3) en fonction de ses caractéristiques techniques (RAM, Bluetooth, 4G, etc.).

# *🔍 Étapes principales du script* 

Chargement des données depuis Kaggle.
Prétraitement :
Séparation des variables qualitatives (booléennes) et quantitatives.
Encodage de la variable cible price_range.
Séparation des données en ensemble d'entraînement et de test.
Pipeline de modélisation :
Standardisation des variables quantitatives.
Régression logistique avec recherche d’hyperparamètres via GridSearchCV.
Évaluation du modèle :
Précision, rappel, exactitude.
Matrice de confusion.
Rapport de classification.
Aire sous la courbe ROC.
Sauvegarde du modèle avec joblib.
# *✅ Résultats produits :*

Histogramme des probabilités prédites.
Rapport de classification complet.
Score ROC AUC pour évaluer la performance multiclasse.
Modèle sauvegardé dans modele.pkl.
