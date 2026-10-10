# CPEB 2027 — outils pour les collectivités

Outils gratuits pour anticiper la **contribution des collectivités prévue par le projet de loi de finances 2027 (CPEB)** : comparaison avec le DILICO 2025-2026, poids sur l'épargne, prospective 2027-2029, registre des mesures du PLF et fiche élus d'une page.

- **`epci.html`** : intercommunalités à fiscalité propre et leurs communes membres.
- **`communes.html`** : toutes les communes (contribution par scénarios tant que les montants communaux ne sont pas publiés).
- **`index.html`** : page d'accueil, avec le tutoriel vidéo.

## Utilisation

Ouvrez la page publiée (GitHub Pages) ou téléchargez un fichier HTML et ouvrez-le dans un navigateur récent (Chrome, Edge, Firefox).
Rien à installer, aucun compte : **les données saisies restent dans le navigateur** de l'utilisateur.
Une connexion Internet n'est utile que pour le fond de carte IGN et la récupération automatique des informations à partir du SIREN ou du code INSEE (geo.api.gouv.fr).

## Données

| Donnée | Source |
|---|---|
| Comptes 2025 | DGFiP, balances comptables (data.gouv.fr) |
| DILICO, reversements, FPIC | DGCL, fichiers de répartition des dotations |
| CPEB 2027 estimée | Intercommunalités de France (octobre 2026) |
| Communes, population, contours | geo.api.gouv.fr ; fond de plan IGN |

Le dossier `modeles/` contient des fiches de saisie vierges et des exemples **entièrement fictifs**.

## Avertissement

Prototype à visée d'alerte et de démonstration, **pas une prévision budgétaire**. Les montants 2027 sont des estimations sur un projet de loi et évolueront avec le débat parlementaire.

## Licence

Code sous licence MIT (voir `LICENSE`). Bibliothèque Leaflet 1.9.4 intégrée, sous licence BSD-2-Clause.
Proposé par le Département du Loiret. Réalisé avec l'aide de l'IA (Claude).
