# Backend - OPTER WOOFS

API REST Node.js/Express avec TypeScript et PostgreSQL.

## Structure
- `src/controllers/` - Contrôleurs API
- `src/routes/` - Routes Express
- `src/services/` - Logique métier
- `src/middleware/` - Middlewares
- `src/models/` - Modèles Prisma
- `prisma/` - Schéma et migrations

## Commandes
```bash
npm install           # Installer les dépendances
npm run dev           # Démarrer en développement
npm run build         # Build TypeScript
npm run start         # Démarrer production
npm run test          # Lancer les tests
npx prisma studio     # GUI base de données
npx prisma migrate dev # Créer/appliquer migrations
```

## Technologies
- Node.js 20
- Express.js
- TypeScript
- Prisma ORM
- PostgreSQL
- JWT Authentication
