# 📊 Analyse comparative : Statistiques inférentielles vs Big Data  
## NYC Yellow Taxi Trip Records (2022–2024)

## 🧠 Contexte du projet
Ce projet vise à comparer deux approches d’analyse de données appliquées à un jeu de données massif de mobilité urbaine :

- **Statistiques inférentielles** basées sur un **échantillon (1 %)**
- **Analyse Big Data** basée sur la **population complète (100 %)**

Les données analysées proviennent des **NYC Yellow Taxi Trip Records** pour la période 2022–2024 et sont traitées avec **Apache Spark sur Databricks**.

---

## 🎯 Objectifs
- Estimer des indicateurs clés à partir d’un échantillon
- Calculer les valeurs exactes sur la population complète
- Comparer les résultats et évaluer la représentativité de l’échantillon
- Identifier les avantages, limites et cas d’usage de chaque approche

---

## ⚙️ Questions analytiques
- Prix moyen d’une course (fare_amount)
- Distance moyenne d’une course (trip_distance)
- Durée moyenne des courses
- Proportion des courses avec tip > 0
- Distribution temporelle (heure / jour / semaine)
- Comparaison géographique des zones de pickup
- Analyse des outliers (courses longues ou chères)
- Ratio moyen tip / fare par type de paiement (cash vs card)

---


---

## 🧪 Données utilisées
### 🔹 Échantillon (Statistiques inférentielles)
- 1 % des données
- Nettoyage et analyse avec **pandas**
- Calcul d’intervalles de confiance et estimations

### 🔹 Population complète (Big Data)
- Données 2022–2024 (plus de 100 millions de lignes)
- Traitement avec **PySpark**
- Calcul des valeurs exactes

---

## 🛠️ Outils & Technologies
- **Databricks Community Edition**
- **Apache Spark (PySpark)**
- Python (pandas, numpy, matplotlib)
- GitHub
- Canva (slides)

---

## 📈 Méthodologie
1. Compréhension des données (EDA)
2. Nettoyage des données
3. Analyse statistique sur échantillon
4. Analyse Big Data sur population
5. Comparaison des résultats
6. Interprétation métier et critique
7. Restitution via slides

---

## 👥 Travail en binôme
- **Échantillon (statistiques inférentielles)** : *ET-TAHERY ZINEB*
- **Population complète (Big Data)** : *ENNACIRI MAWADA*

---

## ✅ Résultats clés
- L’échantillon fournit des estimations très proches des valeurs réelles
- Les outliers ont un impact limité sur les moyennes globales
- Le Big Data permet une précision maximale mais avec un coût technique plus élevé

---

## 📌 Conclusion
Ce projet met en évidence que :
- Les statistiques inférentielles sont efficaces lorsque les ressources sont limitées
- Le Big Data est pertinent lorsque la précision absolue est requise
- Le choix dépend du contexte métier, du volume de données et des contraintes techniques



