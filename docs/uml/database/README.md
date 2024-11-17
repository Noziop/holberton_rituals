# Diagrammes de Base de Données 🎲

Ce répertoire contient les diagrammes Entity-Relationship (ER) définissant la structure de la base de données du système Holberton Rituals.

## 📁 Structure

### Tables Principales (`/tables`)
- `core.mmd` : Tables fondamentales
  - Users, Students, Cohorts
  - Métriques étudiants
  - Préférences notifications

- `config.mmd` : Configuration système
  - Permissions et rôles
  - Paramètres système
  - Règles de gamification

- `feedback.mmd` : Système de feedback
  - SOD feedback
  - StandUp participation
  - PLD évaluations

- `schedule.mmd` : Gestion planning
  - Tirages au sort
  - Créneaux rituels
  - Organisation groupes

### Diagrammes Globaux
- `schema.mmd` : Vue d'ensemble de la base
- `relations.mmd` : Relations entre tables
- `indexes.mmd` : Index et optimisations

## 🔑 Conventions

### Nommage
- Tables : snake_case, pluriel
- Clés primaires : `id`
- Clés étrangères : `table_singulier_id`
- Index : `idx_colonne`

### Types de Données
- Identifiants : `int`
- Texte : `varchar` / `text`
- Dates : `timestamp` / `date`
- Booléens : `boolean`
- Énumérations : `enum`

### Relations
- One-to-One : ||--||
- One-to-Many : ||--o{
- Many-to-Many : }o--o{

## 🛠 Contraintes Communes

- `NOT NULL` : Champs requis
- `UNIQUE` : Valeurs uniques
- `DEFAULT` : Valeurs par défaut
- `ON DELETE CASCADE` : Suppression en cascade
- `CHECK` : Validations personnalisées

## 📊 Index et Optimisations

Voir `indexes.mmd` pour les détails sur :
- Index primaires
- Index secondaires
- Index composites
- Index uniques

## 🔄 Relations

Voir `relations.mmd` pour :
- Relations entre modules
- Contraintes d'intégrité
- Cascades de suppression

## ⚠️ Propriété Intellectuelle

© 2024 Fassih Belmokhtar. Tous droits réservés.
