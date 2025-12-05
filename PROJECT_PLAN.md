# Plan de Projet — APYL

## Objectifs principaux

- Offrir aux citoyens une plateforme unifiée, claire et sécurisée pour accéder à tous les services essentiels (éducation, carrières, administration, etc.)
- Assurer un parcours utilisateur fluide, simple et personnalisé grâce à l’IA intégrée (Assistant César)
- Utiliser des technologies modernes : Next.js, React, Tailwind CSS, Shadcn/ui, Firebase Auth & Firestore
- Tracer et valider chaque grand avancement, jusqu’au certificat/diplôme en fin de parcours

---

## Étapes/Milestones

1. **Initialisation du projet**
    - Dépôt Next.js prêt, arborescence française, configuration Firebase, base UI
2. **Dashboard central et navigation**
    - Affichage clair : accès rapide, tâches clé-en-main, aperçu des portails
3. **Implémentation progressive des portails (MVP)**
    - Éducation : consultation de résultats, formations, orientation
    - Carrière/Entreprise : CV, offres, création d’activité
    - Administration : documents, certificats
    - Transport, Habitat, Culture, Commerce, Communauté
4. **Assistant IA (César)**
    - Fenêtre de chat contextuelle, suggestions personnalisées
    - Integration avec les formulaires/services
5. **Gestion des utilisateurs**
    - Auth Firebase, premiers profils citoyens, rôles et droits
6. **Certification/diplôme utilisateur**
    - Génération PDF ou badge digital après le parcours complet/niveau atteint
7. **Tests, validation parcours, sécurité**

---

## Dossier-types (proposition)

- `/pages` — pages Next.js : accueil, dashboard, chaque portail sous `/pages/portails/xxxx`
- `/composants` — tous les composants UI réutilisables (boutons, cartes, menus…)
- `/portails` — logique spécifique à chaque portail : éducation, carrière, administration, etc.
- `/contexte` — fichiers de gestion de contexte (auth, user, assistant IA…)
- `/styles` — Tailwind config, styles globaux…
- `/hooks` — hooks personnalisés
- `/utils` — fonctions utilitaires
- `/firebase` — config et méthodes (auth, firestore)
- `/public` — images, logos…
- `/locales` — fichiers i18n, car tout est en français

---

## Bonnes pratiques

- Nommer tous les fichiers, variables, composants… en français
- Documentation pour chaque grande fonctionnalité
- Tests unitaires dès MVP (Jest/Testing Library)
- Traçabilité avec issues GitHub et milestones

---

## Validation

- Chaque milestone = livrable validé (par moi puis par toi)
- Le diplôme/certificat se génère automatiquement pour le citoyen après le parcours

---

## Notes

- Toute suggestion ou changement de priorité se fait via issues ou discussion
- Évolutif : chaque “portail” peut être développé ou branché indépendamment, mais avec navigation et style cohérents

---

> **Prêt à attaquer : une étape à la fois, validation à chaque jalon !**