### ballistic-trajectory-simulator
# 🧠 Moteur Physique — Simulation de tir balistique

> Projet académique réalisé à l’**UQAC (Université du Québec à Chicoutimi)**  
> 📚 Cours : *Mathématiques et physique dans l’espace numérique*  
> ⏱️ Durée : **4 mois**

Ce projet consiste en la réalisation d’un **moteur physique** permettant de simuler le comportement de *masses solides (cube, pavé et cônes)* composé de particules reliées par des ressorts et des câbles, avec des interactions dynamiques contrôlées par l’utilisateur (puissance de tir, position de la force appliqué sur l'objet, influence de forces externes)

---

## 🎯 Objectifs du projet
- Implémenter un moteur physique simple
- Mettre en pratique des notions de :
  - mécanique
  - forces
  - contraintes (ressorts / câbles)
- Simuler des comportements émergents à partir de règles physiques

---

## 🗂️ Arborescence du projet

Moteur/

├── src/ # Headers et fichiers sources du moteur

├── tests/ # Fichiers de tests

├── bin/ # Exécutable du projet



- **src/** : contient l’ensemble de l’implémentation du moteur physique  
- **tests/** : regroupe les fichiers de tests  
- **bin/** : contient l’exécutable permettant de lancer la simulation

---

## ▶️ Lancer le projet
Un **exécutable est fourni** dans le dossier `bin`.

👉 Il suffit de lancer cet exécutable pour démarrer la simulation.

---

## 🎮 Principe de la démonstration

La simulation repose sur des interactions clavier et souris permettant de modifier dynamiquement le comportement de l'objet voulu.

### 🔹 Positionnement du `curseur`

- L'origine du tir de projectile se trouve au plus bas et au plus à gauche de l'écran (désigné visuellement par un canon, et mathématiquement comme l'origine du repère). Plus le curseur sera éloigné de l'origine, plus la force soumise à l'objet sera importante, et donc sa trajectoire considérable.

### 🔹 Touche `1`
- Positionne la force appliquée au centre de la masse de l'objet - 20px en l'axe Z (occasionne une rotation vers la gauche - réferentiel axe Z)

### 🔹 Touche `2`
- Positionne la force appliquée au centre de la masse de l'objet - 20px en l'axe Y (occasionne une rotation vers la droite - réferentiel axe Y)

### 🔹 Touche `3`
- Positionne la force appliquée au centre de la masse de l'objet - 20px en l'axe X (occasionne une rotation vers la droite - réferentiel axe Z)

### 🔹 Touche `b`
- Sélectionne le cube (boîte) comme projectile simulé.

### 🔹 Touche `c`
- Sélectionne le cône comme projectile simulé.

### 🔹 Touche `p`
- Sélectionne le pavé droit comme projectile simulé.

### 🔹 Touche `z`
- Sélectionne le cube (boîte) comme projectile simulé dans les 3 dimensions (profondeur admise).

### 🔹 Touche `q`
- Sélectionne le cube (boîte) comme projectile simulé avec ajout d'une force diverse externe.




---

## 🧪 Tests
Les fichiers de tests sont disponibles dans le dossier `tests` afin de valider le bon fonctionnement des différentes composantes du moteur.

---

## 📚 Ce que ce projet m’a apporté
- Compréhension concrète des **systèmes physiques simulés**
- Mise en œuvre de modèles mathématiques et physiques appliqués
- Travail sur la **structure d’un projet logiciel** en groupe de 4
- Approfondissement de la logique algorithmique et de la rigueur de code pour éviter les compléxités excessives et libérer des ressources de calcul

---

## 👨‍🎓 Contexte académique
Projet réalisé dans le cadre du cursus en informatique à l’**Université du Québec à Chicoutimi (UQAC)**.
