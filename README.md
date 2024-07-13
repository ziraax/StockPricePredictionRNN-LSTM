# **Prediction du prix d'une action avec les modèles LSTM et RNN**

## **Aperçu du projet**

La prédiction des prix des actions est cruciale dans les marchés financiers, permettant aux investisseurs de prendre des décisions éclairées pour maximiser les profits ou minimiser les pertes. Les techniques d'apprentissage automatique et profond, notamment les réseaux neuronaux récurrents (RNN) et les réseaux LSTM, ont montré leur potentiel pour améliorer la précision de ces prédictions.

## **Objectifs du projet**

Ce projet vise à :

- Comprendre les réseaux neuronaux, en particulier les RNN et LSTM.
- Charger et prétraiter les données historiques des prix des actions.
- Formuler le problème de prédiction des prix comme une série temporelle.
- Explorer comment les RNN capturent les dépendances temporelles.
- Utiliser les LSTM pour capturer les dépendances à long terme.
- Intégrer des données supplémentaires pour améliorer la précision des prévisions.
- Évaluer les modèles sur des critères de performance pertinents.

## **Approche**

1. **Bases des réseaux neuronaux :**
   - Introduction aux réseaux neuronaux et leur fonctionnement.

2. **Chargement des données :**
   - Utilisation de Yahoo Finance pour obtenir les données de prix des actions.

3. **Transformation des données :**
   - Mise à l'échelle et normalisation des données.
   - Création de fenêtres chevauchantes pour l'entraînement.

4. **Réseaux neuronaux récurrents (RNN) :**
   - Construction et entraînement du modèle RNN.
   - Évaluation des performances du modèle.

5. **Réseaux de mémoire à long terme (LSTM) :**
   - Construction et entraînement du modèle LSTM.
   - Évaluation des performances du modèle.

6. **Entrée multivariée et LSTM :**
   - Intégration d'indicateurs techniques comme RSI et EMA.
   - Construction d'un modèle LSTM prenant en compte ces données supplémentaires.
   - Évaluation et comparaison des résultats avec les modèles précédents.

## **Ressources supplémentaires**

Pour plus de détails sur les étapes spécifiques de mise en œuvre et les résultats, veuillez consulter les sections correspondantes dans le code du projet.
