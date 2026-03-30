# TP5 - Système de gestion de tâches avec GraphQL

## Schéma de base
Création d'un schéma GraphQL avec un type `Task` contenant les champs `id`, `title`, `description`, et `completed`, ainsi que les queries et mutations de base.

## Étape 11 — Ajout du champ `duration`
J'ai ajouté un champ `duration` de type `Int` dans le schéma et mis à jour le résolveur pour le prendre en compte dans `addTask`.

## Étape 12 — Mutation `changeDescription`
Ajout d'une mutation `changeDescription(id, description)` qui permet de modifier la description d'une tâche existante.

## Étape 13 — Mutation `deleteTask`
Ajout d'une mutation `deleteTask(id)` qui supprime une tâche par son id et retourne la tâche supprimée.
