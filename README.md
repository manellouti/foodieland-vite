# 🍽️ Foodieland – Site Vitrine Responsive

> Projet réalisé dans le cadre d’un stage chez **Communik Agency** (Maroc).

## 🎯 Objectif

Créer un **site vitrine statique, responsive et moderne** pour valoriser des recettes culinaires, avec une interface utilisateur soignée, des animations légères, et un affichage fluide sur **desktop, tablette et mobile**.

---

## 🛠️ Stack utilisée

- **HTML5** (structure sémantique propre)
- **CSS3** avec Bootstrap 5 (grille, composants, responsivité)
- **Bootstrap Icons + Font Awesome** (icônes réseaux, food, etc.)
- **Vite** (serveur de dev rapide, bundler moderne)
- **Responsive Design** (mobile-first via media queries)

---

## 📁 Structure du projet

/src
├── /assets → images & icônes (plats, logo, ingrédients, etc.)
├── /css
│ ├── style.css → styles globaux
└── index.html → page principale


---

## 📱 Responsive Design

Le site s’adapte à **toutes tailles d’écran** :

- 💻 **Desktop** : grille en plusieurs colonnes, visuels complets, typographies larges.
- 📱 **Mobile/Tablet** :
  - Réduction des marges/paddings
  - Réorganisation verticale des sections (flex-direction: column)
  - Images redimensionnées automatiquement (`img-fluid`)
  - Sections complexes simplifiées ou ajustées
  - Footer et header totalement centrés

---

## 🔍 Sections clés du site

- **Header** : navigation principale + logo + réseaux sociaux
- **Hero & Recettes** : mise en avant de recettes stylées avec infos (temps, type, auteur)
- **Categories** : section filtrable pour classer les recettes
- **Promo** : message marketing fort avec design illustré
- **Instagram** : grille simulée de posts stylisés
- **Subscribe** : formulaire d’inscription propre et mobile-friendly
- **Footer** : navigation secondaire + signature + réseaux

---

## 🚀 Lancer le projet en local

1. Cloner le repo :

```bash
git clone <url-du-projet>
cd foodieland

2. Installer les dépendances
npm install

3. Lancer le serveur de dev :
npm run dev

4. Accéder à http://localhost:5173


Manel Louti
Juin 2025

