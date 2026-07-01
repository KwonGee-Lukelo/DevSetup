# Notes sur Git

## Qu'est-ce que Git ?

Git est un système de gestion de versions (Version Control System).

Il permet de suivre l'historique des modifications d'un projet et de collaborer efficacement avec d'autres développeurs.

---

## Pourquoi utiliser Git ?

- Sauvegarder l'historique du projet
- Revenir à une version précédente
- Travailler en équipe
- Gérer plusieurs versions d'une application

---

## Commandes essentielles

### Initialiser un dépôt

```bash
git init
```

---

### Vérifier l'état du dépôt

```bash
git status
```

---

### Ajouter les modifications

```bash
git add .
```

---

### Créer un commit

```bash
git commit -m "feat: initial project setup"
```

---

### Voir l'historique

```bash
git log
```

---

### Vérifier la configuration

```bash
git config --list
```

---

## Workflow Git

```text
Modifier les fichiers
        ↓
git status
        ↓
git add
        ↓
git commit
        ↓
git push
```

---

## Bonnes pratiques

- Faire un commit par fonctionnalité
- Utiliser des messages de commit clairs
- Tester le projet avant chaque commit
- Commiter régulièrement

---

## Ce que j'ai appris

- Initialiser un dépôt Git
- Ajouter des fichiers
- Créer des commits
- Consulter l'historique
- Comprendre le workflow Git
