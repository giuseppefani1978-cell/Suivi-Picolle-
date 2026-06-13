# Suivi-Picolle-
Suivi tracking de la conso alcool. 
# 🎮 DrinkDex : Le RPG de ta Santé 🍹

**DrinkDex** est une petite application web interactive et ludique (Gamification) conçue pour aider à suivre sa consommation d'alcool et son budget de sortie. Son design rétro inspiré des jeux RPG des années 90 rend le suivi quotidien moins culpabilisant et plus amusant !

## ✨ Fonctionnalités Principales

*   **🛡️ Profil Santé (OMS) :** Calcul personnalisé des recommandations de moindre risque en fonction de ton genre, âge, taille et poids (Calcul de l'IMC intégré).
*   **💰 Tirelire Virtuelle (L'anti-Banque) :** Un budget "soirée" de 15€/jour est alloué. L'argent non dépensé s'accumule dans une tirelire pour récompenser tes économies. Attention à la banqueroute !
*   **🏆 Système de Trophées :** Débloque des badges quotidiens pour encourager les bonnes habitudes ("Sobriété Pure", "Économe", "Top Santé").
*   **📈 Graphique Dynamique :** Visualise ton historique de consommation sous forme de belle courbe grâce à *Chart.js*, avec des filtres par **7 Jours**, **4 Semaines** ou **6 Mois**.
*   **🔒 100% Privé et Hors-Ligne :** Aucune base de données externe. Toutes tes données restent stockées localement sur ton navigateur (`localStorage`). Personne d'autre n'y a accès.

## 🚀 Comment l'utiliser / Hébergement

Ce projet est composé d'un unique fichier `index.html` (HTML/CSS/JS regroupés). 

**Pour l'héberger gratuitement via GitHub Pages :**
1. Crée un nouveau dépôt (repository) sur GitHub.
2. Ajoute le fichier `index.html` et ce `README.md` dans ton dépôt.
3. Va dans les paramètres (**Settings**) de ton dépôt.
4. Dans le menu de gauche, clique sur **Pages**.
5. Sous la section *Build and deployment*, sélectionne la branche `main` (ou `master`) et clique sur **Save**.
6. Au bout de quelques minutes, ton DrinkDex sera en ligne et accessible via une adresse du type `https://ton-pseudo.github.io/ton-depot/` !

**Pour l'utiliser en local :**
*   Télécharge le fichier `index.html`.
*   Double-clique dessus pour l'ouvrir dans n'importe quel navigateur web (Chrome, Safari, Firefox).

## 🛠️ Technologies Utilisées

*   **HTML5 / CSS3 / Vanilla JS** (Aucun framework lourd)
*   **[Chart.js](https://www.chartjs.org/)** pour le rendu du graphique interactif.
*   **[FontAwesome](https://fontawesome.com/)** pour la gestion des icônes (Trophées, Tirelire, etc.).
*   **Google Fonts** (`Press Start 2P` et `VT323`) pour l'ambiance pixel/rétro.

## ⚠️ Avertissement Santé

Cette application est un outil ludique de suivi personnel et **ne remplace pas un avis médical**. 
Les limites calculées dans l'application se basent sur les recommandations indicatives de Santé Publique France (Maximum 2 verres par jour, et pas tous les jours). 
Toutefois, comme le rappelle l'**Organisation Mondiale de la Santé (OMS)** : *« Aucune consommation d'alcool n'est totalement sans risque pour la santé. »*

---
*Fait avec ❤️ et pixels.*
