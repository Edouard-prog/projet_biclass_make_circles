# 🧠 Réseau de Neurones en NumPy

Ce projet implémente **un réseau de neurones artificiel (ANN)** à trois couches, entièrement codé **à partir de zéro avec NumPy**.  
L’objectif est d’apprendre le fonctionnement interne d’un réseau de neurones sans utiliser de frameworks comme TensorFlow ou PyTorch.

---

## 🚀 Fonctionnalités

- Implémentation complète du **forward propagation**
- Calcul du **gradient par backpropagation**
- Fonction de coût basée sur la **log-loss**
- **Mise à jour des poids** avec la descente de gradient
- Visualisation de la **courbe de perte (loss curve)**
- Dataset généré avec `make_classification` (binaire)

---

## 🧩 Structure du modèle

- **Couche d’entrée :** 2 neurones  
- **Couche cachée 1 :** 4 neurones (activation Sigmoïde)  
- **Couche cachée 2 :** 3 neurones (activation Sigmoïde)  
- **Couche de sortie :** 1 neurone (activation Sigmoïde)

---

## 📊 Exemple de résultat

Le réseau apprend à séparer deux classes de points :
- Affiche la **courbe de perte**
- Affiche la **précision finale** sur les données d’entraînement

---
## Execution
python main.py
