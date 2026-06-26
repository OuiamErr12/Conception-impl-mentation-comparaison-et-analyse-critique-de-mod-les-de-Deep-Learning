# Projet de Fin de Module — Deep Learning (EMSI 2025/2026)

* **Étudiante :** Ouiam Erreyyadi
* **Filière :** 4IIR (Ingénierie Informatique et Réseaux)
* **Établissement :** École Marocaine des Sciences de l'Ingénieur (Casablanca)

---

##  Idée Générale du Projet
Ce projet constitue le livrable final du module **Deep Learning**. L'objectif est de concevoir, implémenter et analyser de manière critique trois grandes architectures de réseaux de neurones adaptées à la structure spécifique de trois types de données réelles :

1. **Partie I (Données Tabulaires) :** Classification binaire à l'aide d'un Perceptron Multicouche (MLP) sur le dataset *Breast Cancer*.
2. **Partie II (Données Images) :** Classification spatiale avec un Réseau Convolutif (CNN) inspiré de LeNet-5 sur le dataset *Fashion-MNIST* (incluant des fonctions de convolution et de pooling codées *from scratch*).
3. **Partie III (Données Textuelles) :** Modélisation de séquences (RNN, LSTM, GRU) et Traduction Automatique (Seq2Seq) sur un corpus linguistique issu de *Tatoeba*.

---

##  Structure du Repository

L'ensemble du travail (code source et analyse théorique) est regroupé directement à la racine du dépôt pour un accès rapide :

* **`Projet_DeepLearning_ERREYYADI_OUIAM(1).ipynb`** : Le notebook Jupyter contenant l'intégralité du code source PyTorch, les pipelines de données, les entraînements et les évaluations des modèles.
* **`Rapport_Projet_DeepLearning_ERREYYADI_OUIAM.pdf`** : Le rapport scientifique complet contenant la synthèse théorique, les calculs de dimensions, la documentation des architectures et l'analyse critique des résultats.
* **`README.md`** : Ce fichier guide de présentation et d'instructions.

---

##  Instructions d'Exécution (Comment exécuter le projet)

Pour exécuter le code de ce projet dans les meilleures conditions, suivez ces étapes :

### Étape 1 : Ouverture du Notebook
1. Cliquez sur le fichier **`Projet_DeepLearning_ERREYYADI_OUIAM(1).ipynb`** depuis la liste ci-dessus.
2. Une fois la page ouverte, cliquez sur le bouton **"Open in Colab"** (généralement affiché en haut de la page sur GitHub) pour l'ouvrir directement dans l'environnement Google Colab.

### Étape 2 : Configuration du Matériel (GPU)
Certaines parties (notamment les parties II et III sur les images et les séquences textuelles) nécessitent une puissance de calcul importante.
1. Dans le menu supérieur de Google Colab, allez sur **Exécution** > **Modifier le type d'exécution**.
2. Dans la section *Accélérateur matériel*, sélectionnez **GPU** (le GPU T4 gratuit est parfait).
3. Cliquez sur **Enregistrer**.

### Étape 3 : Installation et Exécution
1. Exécutez la toute première cellule du notebook dédiée à l'installation des dépendances (`!pip install ...`) pour préparer l'environnement.
2. Une fois l'installation terminée, allez dans le menu **Exécution** > **Tout exécuter**, ou lancez les cellules une par une de manière séquentielle.
