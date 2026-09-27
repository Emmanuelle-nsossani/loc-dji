# CLAUDE.md — contexte du projet loc-dji

Ce fichier donne le contexte du projet pour les sessions de travail avec Claude Code.

## Produit

Application mobile de location à la journée d'une caméra **DJI Osmo Pocket 3**, remise en main propre à **Paris et en Île-de-France**.

Le projet est personnel et sert aussi de terrain de formation au rôle de Product Owner.

## Cible

Jeunes créateurs de contenu : vidéos entre amis, voyages, réseaux sociaux.

## Formules

| Formule | Contenu | Prix à la journée |
| --- | --- | --- |
| Caméra seule | Caméra + carte SD | À définir |
| Pack créateur | Caméra, batterie externe, micro, trépied, contenu du pack créateur | À définir |

## Paiement (MVP)

- Une **caution** est versée par **virement 2 jours avant** la date de réservation ; elle est rendue au retour de la caméra.
- Le reste est réglé **le jour de la remise**.
- **Pas de paiement en ligne** dans le MVP.

## Organisation du dépôt

- Chaque **user story** est une issue GitHub, créée à partir du modèle `.github/ISSUE_TEMPLATE/user-story.md`.
- Chaque issue est classée par labels :
  - épopée : `epopee:catalogue`, `epopee:reservation`, `epopee:notifications`, `epopee:paiement`, `epopee:analytics`, `epopee:messagerie`, `epopee:identite` ;
  - priorité MoSCoW : `priorite:must`, `priorite:should`, `priorite:could` ;
  - type : `type:user-story`, `type:tache-technique`, `type:bug`.
- Les issues du MVP sont rattachées au jalon **« MVP »**.
- On ne mélange pas le **quoi** et le **comment** : une user story décrit le besoin ; les tâches techniques sont des issues séparées (`type:tache-technique`).

## État technique

La stack technique n'est pas encore choisie. Ne pas écrire de code applicatif tant qu'elle n'a pas été décidée.

## Langue

Tout le contenu du dépôt et des issues est rédigé en **français**.
