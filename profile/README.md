<div align="center">

# 🤖 SmartBot-Guild
---
<br>
<br>

[![GitHub Organization](https://img.shields.io/badge/GitHub-42_Academy-purple?logo=github&logoColor=white)](https://github.com/42-academy/.github/blob/main/profile/README.md)
[![GitHub Organization](https://img.shields.io/badge/GitHub-SmartBot_Guild-181717?logo=github)](https://github.com/SmartBot-Guild)
[![GitHub Organization](https://img.shields.io/badge/GitHub-dev_forks_collection-181717?logo=github)](https://github.com/dev-forks-collection)
[![GitHub Organization](https://img.shields.io/badge/GitHub-42_Projects-181717?logo=github)](https://github.com/404)
[![GitHub Organization](https://img.shields.io/badge/GitHub-42_Career_Hub-181717?logo=github)](https://github.com/42-Career-Hub)
[![GitHub Organization](https://img.shields.io/badge/GitHub-42_Learning-181717?logo=github)](https://github.com/42-Learning)
[![GitHub Organization](https://img.shields.io/badge/GitHub-42_DevTools-181717?logo=github)](https://github.com/42-DevTools)

<br>
*Votre collection de bots pour automatiser vos tâches de développement*

</div>

## 🎯 À quoi sert ce hub ?

Ce hub regroupe les meilleurs bots et outils d'automatisation pour vous faire gagner du temps dans vos tâches quotidiennes de développement. Plus besoin de chercher pendant des heures, tout est centralisé ici !


<br><br>

## 🌟 Commencez l'Aventure

<details>
<summary><strong>1. Rejoignez la communauté</strong></summary>

[![Discord](https://img.shields.io/badge/Discord-Vers_le_Cursus_et_l'au_delà-5865F2?logo=discord&logoColor=white)](https://discord.gg/5Ezmt87Suv)

</details>

<details>
<summary><strong>2. Explorez nos ressources</strong></summary>

- 📚 Documentation technique
- 🔧 Outils spécialisés
- 📖 Guides pratiques

</details>
<details>
<summary><strong>3. Contribuez à l'écosystème</strong></summary>

- Partagez votre expérience
- Proposez des améliorations
- Enrichissez la communauté

</details>
<br><br>

## 🤖 Nos Collections

### 1️⃣ Automatisation des Commits Git

**[Conventional Commits Bot](https://github.com/conventional-changelog/commitlint)**
```bash
# Ce bot vous aide à écrire des commits propres et standardisés
npm install -g @commitlint/cli
```
- ✨ **Pourquoi l'utiliser ?** Fini les commits du style "fix stuff" ou "update"
- 📝 **Comment ça marche ?** Il vous guide pour écrire vos commits : type, portée, description
- 💡 **Exemple concret :** Au lieu de écrire "fix bug", il vous fera écrire "fix(login): correct password validation"

### 2️⃣ Configuration Automatique

**[dotfiles Bot](https://github.com/CodelyTV/dotly)**
```bash
# Configure automatiquement votre environnement de développement
bash <(curl -s https://raw.githubusercontent.com/CodelyTV/dotly/master/installer)
```
- 🔧 **À quoi ça sert ?** Configure votre environnement en 2 minutes au lieu de 2 heures
- 🚀 **Que fait-il ?** Installe et configure : git, zsh, vim, vscode, et bien plus
- 📦 **Le plus :** Sauvegarde votre configuration pour la réutiliser sur une autre machine

### 3️⃣ Assistant Discord pour Développeurs

**[DevBot](https://github.com/reactiflux/discord-irc)**
- 🤖 **Son rôle :** Votre assistant personnel pour gérer vos projets sur Discord
- 📚 **Fonctionnalités :**
  ```
  !github status - Vérifie l'état de vos repos
  !deploy project - Lance un déploiement
  !todo - Gère votre liste de tâches
  ```
- 🎯 **Idéal pour :** Les équipes qui utilisent Discord comme outil principal

### 4️⃣ Mise à Jour Automatique des Dépendances

**[Dependabot](https://github.com/dependabot/dependabot-core)**
- 🔄 **Ce qu'il fait :** Vérifie et met à jour automatiquement vos dépendances
- ⚡ **Configuration simple :**
  ```yaml
  # .github/dependabot.yml
  version: 2
  updates:
    - package-ecosystem: "npm"
      directory: "/"
      schedule:
        interval: "daily"
  ```
- 🛡️ **Pourquoi c'est important ?** Maintient votre projet sécurisé et à jour sans effort

### 5️⃣ Tests Automatisés

**[GitHub Actions Bot](https://github.com/actions/starter-workflows)**
- 🧪 **Objectif :** Lance vos tests automatiquement à chaque push
- 📋 **Setup rapide :**
  ```yaml
  # .github/workflows/test.yml
  name: Tests
  on: [push]
  jobs:
    test:
      runs-on: ubuntu-latest
      steps:
        - uses: actions/checkout@v2
        - run: npm test
  ```
- 🎉 **Avantage :** Plus besoin de penser à lancer les tests

## 🚀 Par où commencer ?

1. **Pour débutants :**
   - Commencez par Conventional Commits Bot pour apprendre les bonnes pratiques
   - Utilisez dotfiles Bot pour avoir un environnement pro rapidement
   - Intégrez DevBot à votre Discord

2. **Pour niveau intermédiaire :**
   - Ajoutez Dependabot pour la maintenance automatique
   - Configurez les GitHub Actions pour vos tests

3. **Pour avancés :**
   - Combinez tous les outils
   - Créez vos propres scripts d'automatisation

## 💡 Besoin d'aide ?

- 🤔 **Question courante :** "Comment choisir le bon bot ?"
  → Commencez par identifier votre tâche la plus répétitive !

- 🆘 **Problème d'installation ?**
  → Chaque bot a un guide détaillé dans sa section

- 📚 **Envie d'en savoir plus ?**
  → Rejoignez notre Discord pour l'entraide !
## 👨‍💻 Comment Contribuer

<details>
<summary><strong>1. Créez un Fork</strong></summary>
- Clonez le projet sur votre propre compte GitHub en cliquant sur le bouton "Fork".
- Assurez-vous que votre fork est à jour avec le projet principal pour éviter les conflits.

</details>

<details>
<summary><strong>2. Créez une branche pour votre fonctionnalité ou correction</strong></summary>
- Exécutez `git checkout -b feature/mon-changement` pour créer une nouvelle branche.
- Faites vos modifications et validez-les.

</details>

<details>
<summary><strong>3. Testez vos changements</strong></summary>
- Avant de soumettre une pull request, assurez-vous que tous les tests passent et que votre code est propre et optimisé.
- Utilisez des outils comme `paco` et `norminette` pour vérifier la conformité aux normes de codage.

</details>

<details>
<summary><strong>4. Soumettez votre Pull Request</strong></summary>
- Créez une pull request détaillant vos modifications. Expliquez clairement ce que vous avez ajouté ou corrigé.
- Soyez ouvert à la discussion et aux suggestions d'amélioration.

</details>
<br>

---

<div align="center">

*Simplifiez votre vie de développeur avec les bons outils !* 🚀

[Discord](https://discord.gg/smartbot-guild) • [GitHub](https://github.com/SmartBot-Guild)

</div>
