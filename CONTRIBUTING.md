# Guide de Contribution - OPTER WOOFS

Merci de votre intérêt pour contribuer à OPTER WOOFS ! 🐕

## 🌟 Comment contribuer

### Signaler un bug
1. Vérifier que le bug n'a pas déjà été signalé dans les [Issues](https://github.com/elisaconsales-stack/opter-woofs/issues)
2. Ouvrir une nouvelle issue avec le template "Bug Report"
3. Décrire le bug avec le maximum de détails
4. Ajouter des captures d'écran si possible

### Proposer une fonctionnalité
1. Ouvrir une issue avec le template "Feature Request"
2. Décrire clairement la fonctionnalité souhaitée
3. Expliquer pourquoi elle serait utile
4. Proposer une implémentation si possible

### Soumettre du code

#### Setup développement
```bash
# Fork le projet
git clone https://github.com/VOTRE-USERNAME/opter-woofs.git
cd opter-woofs

# Installer les dépendances
cd frontend && npm install
cd ../backend && npm install

# Créer une branche
git checkout -b feature/ma-super-feature
```

#### Standards de code

**TypeScript**
- Utiliser TypeScript strictement typé
- Pas de `any`, préférer `unknown` si nécessaire
- Documenter les fonctions complexes

**Naming conventions**
- Variables/fonctions : `camelCase`
- Composants React : `PascalCase`
- Fichiers : `kebab-case.tsx` ou `PascalCase.tsx` pour composants
- Constants : `UPPER_SNAKE_CASE`

**Commits**
Suivre la convention [Conventional Commits](https://www.conventionalcommits.org/) :
- `feat:` nouvelle fonctionnalité
- `fix:` correction de bug
- `docs:` documentation
- `style:` formatage, pas de changement de code
- `refactor:` refactoring
- `test:` ajout de tests
- `chore:` maintenance

Exemples :
```
feat: add user profile page
fix: resolve authentication timeout issue
docs: update API documentation
```

#### Tests
- Écrire des tests pour les nouvelles fonctionnalités
- S'assurer que tous les tests passent : `npm test`
- Viser une couverture de code > 80%

#### Pull Request
1. Mettre à jour la documentation si nécessaire
2. S'assurer que les tests passent
3. Pousser votre branche
4. Ouvrir une PR avec une description claire
5. Lier les issues concernées

#### Revue de code
- Soyez patient, les reviews prennent du temps
- Soyez ouvert aux feedbacks
- Répondre aux commentaires de review
- Mettre à jour votre PR si nécessaire

## 📋 Checklist PR

Avant de soumettre votre PR, vérifier :
- [ ] Le code suit les conventions du projet
- [ ] Les tests passent
- [ ] La documentation est à jour
- [ ] Les commits sont bien nommés
- [ ] Pas de conflits avec `main`
- [ ] La PR est liée à une issue

## 🎨 Design Guidelines

- Interface intuitive et accessible
- Responsive (mobile-first)
- Couleurs cohérentes avec le thème chien/adoption
- UX optimale pour adoptants et associations

## 🐛 Debug

### Backend
```bash
cd backend
npm run dev # avec hot-reload
npm run debug # avec debugger Node.js
```

### Frontend
```bash
cd frontend
npm run dev # port 5173
```

### Database
```bash
cd backend
npx prisma studio # GUI pour la BDD
npx prisma migrate dev # migrations
```

## 💬 Questions ?

- Ouvrir une [Discussion](https://github.com/elisaconsales-stack/opter-woofs/discussions)
- Poser une question dans les Issues

## 🙏 Merci !

Chaque contribution compte. Merci de rendre OPTER WOOFS meilleur ! 🐾
