# EnerBat

![Logo EnerBat](myems-admin/img/enerbat-logo.png)

EnerBat est une plateforme de gestion et d’analyse énergétique destinée aux bâtiments. Elle permet de suivre les consommations, comparer les périodes, interpréter les résultats et préparer les actions d’amélioration.

## Vue d’ensemble

La vue d’ensemble offre une synthèse rapide des données énergétiques du bâtiment.

- suivi des consommations électriques, de chauffage et d’eau
- comparaison des périodes
- visualisation de l’historique
- préparation des actions prioritaires

<p align="center">
  <img src="docs/images/tableau-de-bord.png" width="90%" alt="Vue d'ensemble EnerBat">
</p>

---

## Analyse

La section Analyse permet de mesurer les consommations et de comparer les périodes afin d’identifier les écarts et les tendances.

- période comparée
- électricité moyenne
- évolution
- eau totale
- historique des consommations

<p align="center">
  <img src="docs/images/analyse.png" width="90%" alt="Analyse EnerBat">
</p>

---

## Mes relevés

Cette vue permet d’ajouter et de gérer les relevés mensuels de consommation.

- saisie de l’électricité, du chauffage et de l’eau
- suivi des périodes enregistrées
- export CSV
- suppression des relevés

<p align="center">
  <img src="docs/images/releves.png" width="90%" alt="Mes relevés EnerBat">
</p>

---

## Plan d’action

Le plan d’action transforme les constats en décisions concrètes. Les étapes sont organisées selon une logique de progression : mesurer, comprendre, améliorer, suivre.

- vérifier les compteurs
- étudier les usages
- améliorer l’enveloppe
- mesurer après travaux

<p align="center">
  <img src="docs/images/plan-action.png" width="90%" alt="Plan d’action EnerBat">
</p>

---

## Présentation

**EnerBat** est l’édition française de l’administration EnerBat.

### À quoi sert ce projet ?
Il permet de configurer les bâtiments, les compteurs et les structures de données nécessaires au suivi des consommations d’énergie.

> Note : EnerBat reste identifié comme le logiciel d’origine.

### Documentation et liens
- 📖 [Guide de prise en main](docs/guide-fr.html)
- ⚙️ [État réel du contenu et installation](docs/INSTALLATION_FR.md)

---

## Architecture et parcours

<p align="center">
  <img src="docs/images/parcours-fr.svg" width="90%" alt="Parcours de suivi énergétique">
</p>

<p align="center">
  <img src="docs/images/architecture-fr.svg" width="90%" alt="Organisation des données">
</p>

> Ces schémas sont des illustrations explicatives. Ce ne sont ni des captures d’une application en cours d’exécution, ni des résultats d’audit réels.

---

## État de l’archive

L’archive contient du code d’administration, des bibliothèques et des scripts SQL.

- **Éléments absents :** les modèles HTML du dossier `enerbat-admin/views/`, le serveur `enerbat-api` et l’interface `enerbat-web`.
- **Conséquence :** l’administration ne peut pas fonctionner entièrement à partir de cette archive seule.

---

## Personnalisation française

- le français est imposé au chargement et à la connexion
- les anciennes captures multilingues et liens promotionnels ont été retirés
- un guide local remplace les renvois vers les chaînes vidéo externes
- les identifiants techniques, bibliothèques tierces et structures de base de données sont conservés pour garantir la compatibilité des intégrations
