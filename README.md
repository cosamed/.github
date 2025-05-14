<!-- Début de la grille d’icônes stack -->
<table>
  <tr>
    <td align="center" width="100">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="48" height="48" />
      <br>Python
    </td>
    <td align="center" width="100">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="ReactJS" width="48" height="48" />
      <br>ReactJS
    </td>
    <td align="center" width="100">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React Native" width="48" height="48" />
      <br>React Native
    </td>
  </tr>
  <tr>
    <td align="center" width="100">
      <img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Laravel.svg" alt="Laravel" width="48" height="48" />
      <br>Laravel
    </td>
    <td align="center" width="100">
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/NestJS_logo.svg" alt="NestJS" width="48" height="48" />
      <br>NestJS
    </td>
    <td align="center" width="100">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Docker_%28container_engine%29_logo.svg" alt="Docker" width="48" height="48" />
      <br>Docker
    </td>
  </tr>
  <tr>
    <td align="center" width="100">
      <img src="https://seeklogo.com/images/J/jupyter-logo-72D1F6D1F5-seeklogo.com.png" alt="Jupyter Notebook" width="48" height="48" />
      <br>Jupyter Notebook
    </td>
    <td></td>
    <td></td>
  </tr>
</table>
<!-- Fin de la grille d’icônes stack -->


# Projet COSAMED

#### État du projet
- :white_check_mark: Fonctionnalités de base implémentées
- :bug: Correction des bugs critiques en cours
- :rocket: Déploiement prévu pour la semaine prochaine

#### Technologies utilisées
- ![Icône Web](https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@main/icons/octicons/browser.svg) Application Web
- ![Icône Mobile](https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@main/icons/octicons/device-mobile.svg) Application Mobile (Android & iOS)
- ![Icône Backend](https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@main/icons/octicons/server.svg) Serveur Backend


#### Guide de Rédaction des Messages de Commit Git pour l’Organisation COSAMED

Ce guide a pour objectif d’harmoniser la manière dont nous rédigeons les messages de commit dans tous les dépôts de notre organisation GitHub. Il s’inspire des bonnes pratiques Udacity, adaptées à notre contexte, pour faciliter la compréhension, la traçabilité et la collaboration au sein de nos équipes.

### Structure du Message de Commit
Un message de commit se compose de trois parties distinctes, séparées par une ligne vide :
```
type: Sujet

Corps (optionnel)

Footer (optionnel)
```

Mais ce n'est pas a tout moment que nous devons utiliser the corps and Footer. Example d'un simple commit:

```
Feat: Ajout d'une fonctionalité avec redis
```

- **type** : indique la nature du changement (voir ci-dessous).
- **Sujet** : résumé clair et concis du changement, en 50 caractères maximum, commençant par une majuscule, sans point final.
- **Corps** : explique ce que fait le commit et pourquoi, pas comment. À utiliser uniquement si nécessaire.
- **Footer** : référence les issues ou tickets liés (ex : Résout : #123).

### Types de Commits
Utilisez l’un des types suivants en début de message, suivi de deux-points et d’un espace :

- __feat__ : ajout d’une nouvelle fonctionnalité
- __fix__ : correction d’un bug
- __docs__ : modification ou ajout dans la documentation
- __style__ : changements de formatage, indentation, espaces, sans impact sur le code
- __refactor__ : modification du code sans ajout ni correction de fonctionnalité
- __test__ : ajout ou modification de tests, sans impact sur le code de production
- __chore__ : tâches de maintenance, mise à jour de configurations, scripts, etc.

### Bonnes Pratiques
- Rédigez les messages au mode impératif : par exemple, Ajoute la gestion des erreurs et non Ajouté ou Ajoute.
- Limitez la longueur des lignes du corps à 72 caractères.
- N’utilisez pas de point à la fin du sujet.
- Séparez toujours le sujet du corps par une ligne vide.
- Expliquez dans le corps pourquoi le changement est fait, pas comment (le code montre le comment).
- Si vous faites référence à une issue, indiquez-le dans le footer, par exemple : Résout : #45

### Recommandations pour le Travail Collaboratif
- Travaillez toujours dans une branche dédiée autre que main (exemple : feature/nom-fonctionnalite, fix/nom-bug) afin de préserver la stabilité de la branche principale.
- Faites des commits fréquents et ciblés, chaque commit doit représenter un changement unique et cohérent.
- Portez une attention particulière aux issues (#numéro) ouvertes dans chaque dépôt : mentionnez-les dans vos commits pour faciliter le suivi.
- Documentez votre code de manière claire et concise pour faciliter la compréhension et la maintenance.
- Assurez-vous que la documentation du dépôt est à jour : tout changement fonctionnel ou structurel important doit être reflété dans les fichiers README ou équivalents.

<hr>

- :white_check_mark: Tâche terminée
- :bug: Correction de bug
- :sparkles: Nouvelle fonctionnalité
- :memo: Documentation
- :rocket: Déploiement
- :warning: Attention / Avertissement
- :lock: Sécurité
- :iphone: Mobile
- :computer: Web