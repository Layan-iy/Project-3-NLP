#  Federated Learning for Movie Review Classification

## Objectif du projet
Ce projet implémente un **modèle d’apprentissage fédéré** pour la **classification des critiques de films**, basé sur le **Large Movie Review Dataset (IMDB)**.  
L’apprentissage fédéré permet d’entraîner un modèle **sans centraliser les données**, ce qui améliore la **confidentialité** et la **scalabilité**.  

Plutôt que de transférer les critiques de films vers un serveur central, **chaque client entraîne le modèle localement** et envoie uniquement les mises à jour du modèle.  
Ce principe est **très utilisé en entreprise pour préserver la confidentialité des données** tout en bénéficiant de l’apprentissage machine.

---

## Technologies utilisées
- **Python** 
- **Pandas, NumPy** (Manipulation et prétraitement des données)
- **Scikit-learn** (Modèles de classification)
- **TensorFlow / PyTorch** (Apprentissage machine)
- **Flower** (Framework d’apprentissage fédéré)
- **Matplotlib, Seaborn** (Visualisation des résultats)

---

## Données utilisées
 **Dataset : Large Movie Review Dataset (IMDB)**  
- **25 000 critiques de films** pour l'entraînement  
- **25 000 critiques de films** pour le test  
- **Objectif** : Prédire si une critique est **positive ou négative**

📎 **Référence du dataset** : [IMDB Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)  


Les critiques sont extraites sous forme de **texte brut** et utilisées pour entraîner un modèle de classification **supervisé**.

---

## Exécution du projet
### **Cloner le dépôt**
```bash
git clone https://github.com/Layan-iy/Project-3-NLP.git
cd Project-3-NLP
