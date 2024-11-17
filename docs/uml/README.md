# Documentation UML - Holberton Rituals 📊

Architecture technique détaillée du système de gestion des rituels Holberton School.

## 📁 Structure des Diagrammes

```
uml/
├── class/             # Diagrammes de classes
│   ├── core/          # Système central
│   └── rituals/       # Gestion rituels
├── database/          # Structure BDD
│   ├── tables/        # Définitions tables
│   ├── schema.mmd     # Vue globale
│   ├── indexes.mmd    # Optimisations
│   └── relations.mmd  # Relations
├── usecase/           # Cas d'utilisation
│   ├── staff/         # Actions staff
│   └── student/       # Actions étudiants
└── workflows/         # Flux des processus
    ├── rituals/       # SOD, StandUp, PLD
    ├── volunteer/     # Système volontariat
    ├── gamification/  # Points et badges
    └── notifications/ # Système notifs
```

## 🎯 Rituels Principaux

### SOD (Share or Die)
- **Timing**
  - Fondamentaux : Lundi/Mardi/Jeudi
  - Spécialisation : Vendredi
- **Règles**
  - Pas de présentation récente (-15 jours)
  - Vérifications multiples :
    - Disponibilité étudiant
    - Vacances cohorte
    - Exclusions staff
- **Pondération**
  - Temps depuis dernière présentation
  - Historique participation
  - Assiduité


### StandUp (Mar-Ven, 11:45)
- Sélection Scrum Master
- Critères :
  - Pas SM semaine précédente
  - Expertise projet en cours
  - Présence confirmée
- Support préparation

### PLD (Jeudi)
- Groupes équilibrés
- Distribution expertise :
  - Un expert par groupe
  - Mix de niveaux
  - Historique collaboration
- Support apprentissage

## 🛠 Implémentation Technique

### Base de Données
- Tables principales
- Index optimisés
- Relations cohérentes
- Contraintes d'intégrité

### Classes
- Patterns de conception
- Séparation des responsabilités
- Interfaces claires
- Gestion des exceptions

### Workflows
- Processus détaillés
- Gestion des erreurs
- Notifications intégrées
- Suivi des actions

## 🎮 Gamification Intégrée

- Points par participation
- Badges de progression
- Niveaux d'expertise
- Récompenses volontariat

## 📱 Système de Notifications

- Multi-canal (Slack/Email)
- Préférences utilisateur
- Rappels intelligents
- Escalade urgences

## ⚠️ Propriété Intellectuelle

© 2024 Fassih Belmokhtar. Tous droits réservés.
Ce projet est propriétaire.

## ✨ Notes Techniques

- Diagrammes réalisés avec Mermaid.js
- Conventions de nommage strictes
- Documentation inline
- Tests intégrés
