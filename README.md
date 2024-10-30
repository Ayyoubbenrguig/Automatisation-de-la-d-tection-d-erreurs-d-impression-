
# Détection d'Anomalies en Impression pour Sacs en Papier Kraft - Projet de Stage

## Contexte du Projet

Chez **Tecpap**, une entreprise spécialisée dans la fabrication de sacs en papier kraft pour des clients comme Carrefour, McDonald's et Adidas, l'impression personnalisée est essentielle pour répondre aux exigences de chaque marque. Cependant, ce processus d'impression est sujet à des erreurs, ce qui peut entraîner des produits non conformes. Les erreurs d'impression, bien que souvent mineures, peuvent affecter la qualité perçue par le client et nécessitent une vérification minutieuse et coûteuse.



<align="center">img src="Tecpap.jpg" alt="Atelier de tecpap" width="500"/>



### Problématique

Actuellement, la détection des erreurs d'impression repose majoritairement sur une **inspection humaine**, ce qui entraîne des coûts élevés et une efficacité limitée, en particulier pour des volumes de production importants. Les erreurs comme les décalages de couleur, les imprécisions dans le positionnement du logo, et d'autres défauts visuels, échappent parfois au contrôle manuel.

**Objectif** : Mettre en place un **système de détection d'anomalies automatisé** basé sur la vision par ordinateur pour identifier et classer les produits en sacs conformes et non conformes, réduisant ainsi la nécessité d'une intervention humaine constante.

## Mission

Pour résoudre ce problème, notre mission consiste à :

1. **Collecter et préparer un ensemble de données** d'images d'impressions sur sacs en papier kraft, comprenant des exemples d'impressions conformes et non conformes.
2. **Développer et entraîner un modèle de classification d'images** capable d'identifier les erreurs d'impression, en utilisant des algorithmes de **machine learning** et de **deep learning**.
3. **Évaluer et optimiser les performances du modèle** afin de garantir un niveau de précision élevé en conditions réelles.
4. **Intégrer le modèle au sein de la chaîne de production**, permettant une détection en temps réel des défauts d'impression sur les lignes de production.

## Données

Les données utilisées dans ce projet comprennent :
- **Images de sacs imprimés** : Capturées directement sur la chaîne de production, les images incluent des impressions de logos et autres éléments graphiques spécifiques aux clients.
- **Labels** : Les images sont étiquetées comme "conformes" ou "non conformes" pour permettre l'entraînement et l'évaluation du modèle.

**Remarque** : La quantité de données était initialement limitée, ce qui a nécessité l'utilisation de techniques d'**augmentation de données** pour créer un ensemble de données équilibré.

## Outils et Technologies

Voici les principaux outils et technologies utilisés dans ce projet :

- **Langage** : Python
- **Bibliothèques pour le Deep Learning** : TensorFlow, Keras
- **Modèles de Classification** : CNN (Convolutional Neural Network), ResNet, VGG16, Autoencoders
- **Vision par Ordinateur** : OpenCV pour le prétraitement et l'augmentation des images
- **Environnement de Développement** : Jupyter Notebook
- **Visualisation des Données** : Matplotlib, Seaborn
- **Gestion des Données** : Pandas pour la manipulation des données et préparation
- **Version Control** : Git et GitHub pour le suivi du projet

## Résultats Attendus

L'objectif est de parvenir à un modèle capable de :
- Identifier les impressions non conformes avec une précision élevée.
- Réduire le besoin d'interventions humaines pour l'inspection de la qualité des impressions.
- Permettre une intégration facile dans la chaîne de production de Tecpap pour un contrôle de qualité en temps réel.

## Structure du Projet

Le projet est structuré comme suit :

- **data/** : Contient les données d'images d'entraînement et de test.
- **notebooks/** : Notebooks Jupyter pour l'exploration des données, le prétraitement et l'entraînement du modèle.
- **src/** : Code source pour les modules de traitement d'images, entraînement et évaluation des modèles.
- **models/** : Modèles entraînés et paramètres enregistrés.
- **results/** : Résultats et visualisations d'évaluation du modèle.
- **README.md** : Documentation du projet.

## Ressources

- **Documentation de TensorFlow** : [https://www.tensorflow.org/](https://www.tensorflow.org/)
- **Documentation d'OpenCV** : [https://opencv.org/](https://opencv.org/)
