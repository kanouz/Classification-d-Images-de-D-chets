# ♻️ Classification d'Images de Déchets

Ce projet utilise le **Deep Learning** pour identifier et classifier automatiquement différents types de déchets. L'objectif est de faciliter le tri sélectif et de contribuer à une meilleure gestion de l'environnement via l'intelligence artificielle.

## 🌟 Présentation
Développé dans le cadre du module **Apprentissage Automatique et Visualisation (S6)**, ce projet met en œuvre un modèle de classification d'images capable de distinguer les catégories de déchets (ex: plastique, papier, métal, verre).

## 📊 Dataset & Prétraitement
* **Source :** Utilisation de datasets d'images de déchets (format .jpg/.png).
* **Techniques :** Redimensionnement des images, normalisation et augmentation de données (Data Augmentation) pour améliorer la précision du modèle.

## 🧠 Modèle & Algorithmes
Le projet explore l'utilisation de réseaux de neurones :
* **Architecture :** Réseaux de Neurones Convolutionnels (CNN).
* **Frameworks :** TensorFlow / Keras ou PyTorch.
* **Optimisation :** Utilisation de fonctions de perte adaptées à la classification multi-classe.

## 📊 Résultats et Interface
Voici un aperçu des performances du modèle et de l'interface utilisateur :

### Test du modèle
Exemple de prédiction sur une image de déchet :
![Exemple de test](./image/EXEMPLE_ESSAYE_MODELE.png)

### Performance
Analyse de la précision via la matrice de confusion :
![Matrice de confusion](./image/CONFUSION_MATRIX.png)

### Application
Aperçu de l'interface de dépôt de fichiers (Drag & Drop) :
![Interface](./image/INTERFACE_DRAG&DROP.png)

## 🛠️ Installation et Utilisation
1. **Cloner le projet :**
   ```bash
   git clone [https://github.com/kanouz/Classification-d-Images-de-D-chets.git](https://github.com/kanouz/Classification-d-Images-de-D-chets.git)
