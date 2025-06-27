# 🛡️ Contrôle Automatisé des Arrêts de Travail
Cycle-Innovation

1. Description du Projet
📌 Objectif

Ce projet vise à détecter automatiquement les fraudes potentielles dans les arrêts de travail, en croisant les informations issues des documents médicaux avec des bases de données (SS, cabinet médical, etc.). Il fait suite aux constats de la Cour des comptes sur les milliards d’euros de fraudes constatées chaque année.
🎯 Fonctionnalités
- Vérification automatique des champs du formulaire Cerfa :
  - Identité du médecin ↔ numéro RPPS ↔ adresse ↔ structure
  - Numéro de sécurité sociale ↔ nom/prénom du patient
  - Adresse de domicile ↔ lieu d’auscultation
  - Détection de diagnostic imprécis
- Alerte en cas d’anomalie vers les agents de l’assurance maladie


🛠️ Technologies utilisées:
    .React + TypeScript
    .Vite
    .Tailwind CSS
    .ESLint

📁 Architecture :
    src/components – Modales et composants principaux
    utils/ – Fonctions utilitaires
    App.tsx – Composant principal
    main.tsx – Point d’entrée

2. Structure du Projet
   /src
  ├─ components/             # Composants React (AlertModal, AnalysisResults...)
  ├─ utils/                  # Fonctions utilitaires
  ├─ App.tsx                 # Composant principal
  ├─ main.tsx                # Point d'entrée React
  ├─ types.ts                # Types TypeScript
  ├─ index.css               # Style global
  └─ vite-env.d.ts           # Types Vite

index.html                  # Template HTML
tailwind.config.js          # Config Tailwind
vite.config.ts              # Config Vite
tsconfig.json               # Config TypeScript
eslint.config.js            # Linter


🚀 3. Comment lancer le projet en local

Prérequis :
- Node.js ≥ 18
-  npm ≥ 9

Etapes: 
# 1. Cloner le repo
git clone https://github.com/TON-UTILISATEUR/TON-NOM-DE-REPO.git
cd TON-NOM-DE-REPO

# 2. Installer les dépendances
npm install

# 3. Lancer le serveur de développement
npm run dev

Ensuite, ouvre le lien affiché dans ton terminal (souvent http://localhost:5173) pour voir l'application
