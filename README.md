# 🐕 OPTER WOOFS

**Plateforme de mise en relation entre associations d'aide à l'adoption de chiens et adoptants potentiels**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue.svg)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-20.x-green.svg)](https://nodejs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16.x-blue.svg)](https://www.postgresql.org/)

---

## 📖 À propos

OPTER WOOFS est une application web moderne qui facilite le processus d'adoption de chiens en créant une passerelle numérique entre :
- **Les associations** et refuges qui recherchent des familles aimantes pour leurs chiens
- **Les adoptants** qui souhaitent accueillir un nouveau compagnon

### 🎯 Objectifs du projet
- Simplifier la mise en relation adoptants/associations
- Centraliser les offres d'adoption
- Faciliter la gestion des demandes
- Promouvoir le Parc Des Woofs

---

## ✨ Fonctionnalités principales

### Pour les Adoptants
- 🔐 Création de profil adoptant
- 🔍 Recherche de chiens disponibles
- 📝 Formulaire de demande d'adoption
- 💬 Système de messagerie avec les associations
- 📊 Suivi des demandes en cours

### Pour les Associations
- 🏢 Profil association/refuge
- ➕ Ajout et gestion des chiens disponibles
- 📋 Gestion des demandes d'adoption
- ✅ Validation/refus des adoptions
- 📈 Tableau de bord statistiques

### Fonctionnalités communes
- 🌐 Accès au site du **Parc Des Woofs**
- 📱 Interface responsive (mobile, tablette, desktop)
- 🔔 Système de notifications
- 🖼️ Galerie photos des chiens

---

## 🛠️ Stack Technologique

### Frontend
- **React 18.x** avec TypeScript
- **Vite** (bundler moderne et rapide)
- **TailwindCSS** (styling)
- **React Router** (navigation)
- **Axios** (HTTP client)
- **React Query** (state management)

### Backend
- **Node.js 20.x**
- **Express.js** (API REST)
- **TypeScript**
- **Prisma ORM** (gestion base de données)
- **JWT** (authentification)
- **Multer** (upload de fichiers)

### Base de données
- **PostgreSQL 16.x**

### DevOps & Tools
- **Git** & GitHub
- **ESLint** & **Prettier** (code quality)
- **Jest** & **React Testing Library** (tests)
- **Docker** (containerisation)

---

## 📁 Structure du projet

```
opter-woofs/
├── frontend/               # Application React
│   ├── public/            # Assets statiques
│   ├── src/
│   │   ├── components/    # Composants réutilisables
│   │   ├── pages/         # Pages de l'application
│   │   ├── hooks/         # Custom React hooks
│   │   ├── services/      # API calls
│   │   ├── utils/         # Utilitaires
│   │   ├── types/         # Types TypeScript
│   │   └── App.tsx        # Point d'entrée React
│   └── package.json
│
├── backend/               # API Node.js/Express
│   ├── src/
│   │   ├── controllers/   # Logique métier
│   │   ├── models/        # Modèles Prisma
│   │   ├── routes/        # Routes API
│   │   ├── middleware/    # Middlewares
│   │   ├── services/      # Services métier
│   │   ├── utils/         # Utilitaires
│   │   └── server.ts      # Point d'entrée serveur
│   ├── prisma/
│   │   └── schema.prisma  # Schéma de base de données
│   └── package.json
│
├── docs/                  # Documentation
│   ├── api/              # Documentation API
│   ├── database/         # Schémas BDD
│   └── user-guides/      # Guides utilisateur
│
├── .gitignore
├── README.md
├── CONTRIBUTING.md
└── LICENSE
```

---

## 🚀 Installation & Démarrage

### Prérequis
- Node.js >= 20.x
- PostgreSQL >= 16.x
- Git

### Installation

```bash
# Cloner le repository
git clone https://github.com/elisaconsales-stack/opter-woofs.git
cd opter-woofs

# Installer les dépendances frontend
cd frontend
npm install

# Installer les dépendances backend
cd ../backend
npm install
```

### Configuration

```bash
# Backend - Créer le fichier .env
cd backend
cp .env.example .env

# Configurer la base de données dans .env
DATABASE_URL="postgresql://user:password@localhost:5432/opter_woofs"
JWT_SECRET="votre_secret_jwt"
PORT=3000
```

### Démarrage

```bash
# Démarrer le backend (depuis /backend)
npm run dev

# Démarrer le frontend (depuis /frontend)
npm run dev
```

L'application sera accessible sur `http://localhost:5173`

---

## 📊 Roadmap

### Phase 1 : MVP (v0.1) ✅ En cours
- [x] Setup initial du projet
- [ ] Authentification utilisateurs
- [ ] Profils adoptants & associations
- [ ] Liste des chiens disponibles
- [ ] Formulaire de contact basique

### Phase 2 : Core Features (v0.2)
- [ ] Système de demandes d'adoption
- [ ] Messagerie interne
- [ ] Upload de photos
- [ ] Recherche avancée de chiens
- [ ] Notifications

### Phase 3 : Advanced Features (v0.3)
- [ ] Tableau de bord statistiques
- [ ] Intégration Parc Des Woofs
- [ ] Système de favoris
- [ ] Export de données
- [ ] Multi-langues (FR/EN)

### Phase 4 : Polish & Deployment (v1.0)
- [ ] Tests complets
- [ ] Optimisation performances
- [ ] Documentation complète
- [ ] Déploiement production

---

## 🤝 Contribution

Les contributions sont les bienvenues ! Consultez [CONTRIBUTING.md](./CONTRIBUTING.md) pour plus d'informations.

### Workflow Git
1. Fork le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Commit les changements (`git commit -m 'Add AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

---

## 📝 License

Ce projet est sous licence MIT. Voir [LICENSE](./LICENSE) pour plus de détails.

---

## 👥 Équipe

- **Créateur** : [@elisaconsales-stack](https://github.com/elisaconsales-stack)

---

## 📧 Contact

Pour toute question : [Ouvrir une issue](https://github.com/elisaconsales-stack/opter-woofs/issues)

---

## 🙏 Remerciements

- Toutes les associations qui œuvrent pour le bien-être des chiens
- La communauté open-source

---

**Fait avec ❤️ pour nos amis à quatre pattes 🐾**
