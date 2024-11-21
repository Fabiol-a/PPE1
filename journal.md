
# Journal de bord PPE1_2024

## [21/11/24] Rattrapages des exercices faits depuis le début de l'année 

Création d'un dépôt Git

## 01-git-intro-exercices

1. **Création du dépôt GitHub** :
   - Chemin du dépot :  `*/desktop/PPE1_S1/PPE1`.
   - Configuré en mode public avec un fichier README initial.
2. **Clone du dépôt** :
   - Commande utilisée :
     ```bash
     git clone https://github.com/Fabiol-a/PPE1.git
     ```
     *Clone le dépôt distant depuis GitHub et crée une copie locale dans un nouveau dossier.*
3. **Vérification locale** :
   - Commandes utilisées pour vérifier l’état et l’historique du dépôt :
     ```bash
     git status
     ```
     *Vérifie l'état du dépôt local (fichiers modifiés, non suivis, ou prêts pour un commit).*
     ```bash
     git log
     ```
     *Affiche l’historique des commits dans la branche actuelle.*

### Résumé
**Progrès réalisés** :
- Dépôt GitHub configuré et cloné avec succès.
- Identité correctement configurée avec `user.name` et `user.email`.
- Conflit sur `journal.md` résolu sans perte de données.

**Problèmes rencontrés** :
- Problème initial de répertoire non valide.
- Conflit avec un fichier dû à des modifications simultanées.

### Notes importantes
- **Synchronisation fréquente** :
  - Avant toute modification, exécuter :
    ```bash
    git pull origin main
    ```
    *Récupère les changements distants pour éviter les conflits.*
- **Vérification régulière** :
  - Utiliser `git status` pour vérifier l’état des fichiers et détecter des conflits potentiels.
