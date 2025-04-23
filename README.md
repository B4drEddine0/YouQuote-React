# 📚 Citation Manager API

Bienvenue dans le projet **Citation Manager**, une plateforme web pour consulter, gérer et partager des citations, avec des rôles utilisateur et des fonctionnalités avancées comme les favoris, les filtres, les likes, et plus encore !

## 🚀 Contexte du Projet

Ce projet a pour objectif de créer une application web connectée à une API sécurisée permettant la gestion de citations, avec une interface utilisateur adaptée selon le rôle (Utilisateur ou Admin).

## 🔗 Accès à l'API

L’API est accessible via une URL sécurisée.  
L’authentification se fait par **JWT (JSON Web Token)** pour sécuriser l’accès aux ressources.

---

## 🧩 Fonctionnalités à Implémenter

### 🧑‍💻 Authentification et Gestion des Rôles

- Page d’inscription et de connexion avec gestion du token JWT.
- Affichage conditionnel du contenu selon le rôle de l’utilisateur :
  - **Utilisateur** : Gère uniquement ses propres citations.
  - **Admin** : Accès complet, y compris aux suppressions douces (soft delete).

### 📝 Gestion des Citations (CRUD)

- 📄 Lister les citations (avec filtres par mot-clé, catégorie, ou longueur).
- ➕ Ajouter une nouvelle citation.
- ✏️ Modifier une citation existante.
- 🗑️ Supprimer une citation (suppression douce).
- 🔍 Voir les détails d’une citation (auteur, tags, nombre de likes...).

### 🎲 Citations Aléatoires

- Bouton pour générer une ou plusieurs citations au hasard.

### 📐 Filtrage

- Filtres par :
  - Longueur (nombre de mots),
  - Catégorie,
  - Tags.

### 🔥 Popularité

- Affichage des citations les plus populaires (basé sur les likes).

### 📸 Génération d’Image (Bonus)

- Génération d’une image contenant une citation populaire, prête à être partagée.

### ❤️ Likes et Favoris

- Possibilité de liker une citation.
- Ajouter une citation à ses favoris.
- Accès à une page **Mes favoris**.

### 🗂️ Catégories et Tags

- Attribution de **catégories** et **tags** aux citations.
- Filtres disponibles par catégorie ou tag.

---

## ⚙️ Stack Technique (suggestion)

- **Frontend** : React 
- **Backend** : Laravel
- **Base de données** : MySql
- **Auth** : JWT
- **Styles** : TailwindCSS


---

## 📁 Structure du Projet

```bash
📦 citation-manager
├── 📂 public
├── 📂 src
│   ├── 📂 components
│   ├── 📂 pages
│   ├── 📂 services
│   ├── 📂 utils
│   └── App.js
├── .env
├── package.json
└── README.md
```

---

## ✅ À faire / Suivi

- [ ] Authentification JWT
- [ ] Rôles utilisateur
- [ ] CRUD citations
- [ ] Filtres & recherche
- [ ] Likes & favoris

---

## 🤝 Contribuer

Les contributions sont les bienvenues ! N’hésitez pas à ouvrir une issue ou proposer une pull request.

---

## 📝 Licence

Ce projet est open-source et disponible sous la licence [MIT](LICENSE).
