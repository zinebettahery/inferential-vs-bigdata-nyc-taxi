# 📊 Inferential Statistics vs Big Data Analytics  
### NYC Yellow Taxi Trip Records (2022–2024)

## 🧠 Contexte du projet
Dans un contexte de **données massives de mobilité urbaine**, ce projet vise à comparer deux approches analytiques couramment utilisées en Data Analytics :

- **Statistiques inférentielles** basées sur un **échantillon (1 %)**
- **Analyse Big Data** exploitant la **population complète (100 %)**

L’objectif est d’évaluer la **fiabilité**, les **limites** et les **impacts métier** de chaque approche à partir des données réelles des **NYC Yellow Taxi Trip Records**.

---

## 👤 User Story
> En tant que **Data Analyst** travaillant sur des données de mobilité à grande échelle, je dois choisir entre une approche par échantillonnage ou une approche Big Data afin de produire des analyses fiables, adaptées aux contraintes techniques et aux besoins métier.

---

## 🎯 Objectifs
- Comparer des **indicateurs clés** calculés sur un échantillon vs la population complète
- Évaluer la **représentativité** de l’échantillon
- Mesurer l’**impact des outliers**
- Identifier les **avantages et limites** de chaque approche
- Produire une **restitution claire et pédagogique** (notebook + slides)


---

## ❓ Questions analytiques traitées
- Prix moyen des courses (`fare_amount`)
- Distance moyenne (`trip_distance`)
- Durée moyenne des courses
- Proportion des courses avec `tip > 0`
- Distribution temporelle (heure / jour / semaine)
- Comparaison des tarifs par zones géographiques
- Analyse des **outliers** (courses très longues ou très chères)
- Ratio `tip / fare` selon le type de paiement

---

## 📐 Méthodologie
1. **EDA** : compréhension des données et nettoyage
2. **Statistiques inférentielles** sur un échantillon (1 %)
3. **Analyse Big Data** sur la population complète
4. **Comparaison** des résultats (proportions, moyennes, distributions)
5. **Analyse critique** des écarts et des biais
6. **Restitution visuelle** et storytelling

⚠️ Les comparaisons sont faites sur des **proportions et des indicateurs**, et non sur des counts absolus, afin de garantir une comparaison statistiquement valide.


---

## 🛠️ Outils & technologies
- **Databricks Community Edition**
- **Apache Spark (PySpark)**
- Python (pandas, matplotlib / seaborn / plotly)
- Canva (slides)
- Git & GitHub

---

## 📊 Résultats clés
- L’échantillon fournit des estimations proches des valeurs réelles pour certains indicateurs globaux
- Des écarts apparaissent sur les distributions fines (zones, heures creuses, outliers)
- L’analyse Big Data garantit des résultats exacts mais avec un coût computationnel plus élevé
- Le choix de la méthode dépend du **contexte métier**, du **volume de données** et des **contraintes techniques**

---

## 👥 Travail en binôme
Projet réalisé dans un cadre pédagogique, en respectant les bonnes pratiques de Data Analysis et de Big Data Analytics.

---

## 📌 Conclusion
Ce projet met en évidence que :
- Les **statistiques inférentielles** sont rapides et efficaces pour des analyses exploratoires
- Les **technologies Big Data** sont indispensables lorsque la précision et l’exhaustivité sont critiques
- Une approche hybride est souvent la plus pertinente en contexte réel



