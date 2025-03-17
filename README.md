# Federated Learning for Movie Review Classification

## Objectif du projet
Ce projet met en œuvre un **modèle d’apprentissage fédéré** pour la **classification des critiques de films**, basé sur le **Large Movie Review Dataset (IMDB)**. L'objectif principal est de comparer l'approche **d'apprentissage fédéré** à l'approche **d'apprentissage centralisé**, en évaluant leurs performances, leurs implications sur la confidentialité des données et les coûts de communication.

### **Apprentissage fédéré vs Apprentissage centralisé :**
- **Apprentissage fédéré** : Les données ne sont pas centralisées, chaque client entraîne un modèle localement et envoie uniquement les mises à jour du modèle. Cela permet de préserver la confidentialité des données et de mieux gérer la scalabilité.
- **Apprentissage centralisé** : Toutes les données sont envoyées à un serveur central pour l’entraînement, ce qui soulève des problèmes de confidentialité et peut être plus coûteux en termes de communication.

Ce projet permet d'**évaluer l'impact de l’apprentissage fédéré** sur la précision du modèle tout en réduisant les risques associés à la centralisation des données.

---

## ⚙️ Technologies utilisées
- **Python** 
- **Pandas, NumPy** (Manipulation et prétraitement des données)
- **Scikit-learn** (Modèles de classification)
- **TensorFlow / PyTorch** (Apprentissage machine)
- **Flower** (Framework d’apprentissage fédéré)
- **Matplotlib, Seaborn** (Visualisation des résultats)

---

## 🗂️ Données utilisées
📍 **Dataset : Large Movie Review Dataset (IMDB)**  
- **25 000 critiques de films** pour l'entraînement  
- **25 000 critiques de films** pour le test  
- **Objectif** : Prédire si une critique est **positive ou négative**

📎 **Référence du dataset** : [IMDB Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)  

Les critiques sont extraites sous forme de **texte brut** et utilisées pour entraîner un modèle de classification **supervisé**.

---

## 📑 Présentation du projet
Dans le dossier **`docs/`**, tu trouveras un fichier de présentation **`Presentation_Federated_Learning.pptx`** qui fournit une vue d'ensemble détaillée du projet. Cette présentation aborde les aspects suivants :

- **L’apprentissage fédéré** : Une explication complète de la méthode utilisée pour entraîner un modèle de machine learning sans centraliser les données.
- **La comparaison entre l’apprentissage fédéré et l’apprentissage centralisé** : Le projet explore les différences clés entre ces deux méthodes, notamment en termes de confidentialité, d'efficacité et de coûts de communication.
- **Technologies utilisées** : Un aperçu des outils et des bibliothèques employés dans le projet.
- **Les résultats** : Les performances du modèle et l'analyse des bénéfices en termes de confidentialité grâce à l'apprentissage fédéré.

Tu peux consulter et télécharger cette présentation pour mieux comprendre les objectifs et la mise en œuvre du projet.

📎 **Lien vers la présentation** : [Présentation du projet (PPT)](docs/Presentation_Federated_Learning.pptx)

---

## 🚀 Exécution du projet

### 1️⃣ Cloner le dépôt
Clone le projet depuis GitHub en utilisant la commande suivante :
```bash
git clone https://github.com/Layan-iy/Project-3-NLP.git
cd Project-3-NLP
