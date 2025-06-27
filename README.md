
# 🛡️ Contrôle Automatisé des Arrêts de Travail – Projet INNOV

## 🎯 Objectif du projet

Selon le **rapport 2023 de la Cour des comptes**, entre **6 à 8 milliards d’euros de fraudes** aux prestations sociales sont constatées chaque année, et seulement **1,6 milliard est recouvré** par l’État.

👉 Ce projet propose la création d’une **application web de contrôle automatisé** de certains documents de santé, en particulier les **avis d'arrêt de travail**, afin de faciliter le travail des agents de l’Assurance Maladie et lutter contre les fraudes.

## 🧠 Types de fraudes ciblées et solutions proposées

### 📌 Constat actuel :
- Contrôles manuels très limités, souvent aléatoires.
- Des fraudes passent entre les mailles du filet.

### ✅ Notre solution :
- Vérification automatique de **plusieurs champs du formulaire Cerfa** :
  - Correspondance entre **l’identité du médecin**, son numéro RPPS, l’adresse de son cabinet et la structure.
  - Concordance entre **le NIR (numéro de sécurité sociale)** et **le nom/prénom du patient**.
  - **Cohérence géographique** entre le domicile du patient et le lieu d’auscultation.
  - **Alertes** sur les diagnostics imprécis.

### 📩 En cas d'anomalie détectée :
- Envoi d’une **notification aux agents** de l’Assurance Maladie pour contrôle approfondi.

## 🧪 Méthodologie proposée

1. Enquête terrain auprès des caisses d'assurance maladie.
2. Analyse des processus de contrôle existants.
3. Développement d’un algorithme de contrôle automatique.
4. Mise en place des conditions légales d’exploitation des données sensibles.
5. Déploiement d’une **architecture logicielle simple et réplicable**.
6. **Tests en conditions réelles** dans des caisses pilotes.
7. Améliorations, puis **commercialisation** si validation.

## 🛠️ Stack technique

- **React** + **TypeScript**
- **Vite**
- **Tailwind CSS**
- **ESLint**

## ⚙️ Structure du projet

```
INNOV1.3.1/
├── src/
│   ├── components/
│   │   ├── AlertModal.tsx
│   │   ├── AnalysisResults.tsx
│   │   └── HistoryModal.tsx
│   ├── utils/
│   ├── App.tsx
│   ├── index.css
│   ├── main.tsx
│   ├── types.ts
│   └── vite-env.d.ts
├── .bolt/
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.ts
├── tsconfig.app.json
├── tsconfig.json
├── eslint.config.js
└── README.md
```

## 🚀 Comment exécuter le projet localement

### ✅ Prérequis

- **Node.js** ≥ 18.x
- **npm** ≥ 9.x

### 📦 Étapes

```bash
git clone https://github.com/cherifAZ34/PrestaSociales.git
cd NOM-DU-REPO
npm install
npm run dev
```

👉 Accès local : [http://localhost:5173](http://localhost:5173)

## 📌 Statut du projet

- ✅ Architecture technique définie
- ✅ Premiers composants et maquettes créés
- 🧪 En attente de tests avec des données réelles
- 🚧 Phase de validation juridique sur l’exploitation des données

## 📜 Licence

Projet réalisé dans un cadre de **recherche et innovation**.  
Toute utilisation des données sensibles doit respecter le RGPD et les régulations en vigueur.
