# Calendrier des Événements de Cybersécurité en France

## À propos du projet

Ce projet vise à répertorier tous les événements de cybersécurité se déroulant sur le territoire français. La liste des événements est continuellement mise à jour et offre une ressource précieuse pour les professionnels, les étudiants, et toute personne intéressée par le domaine de la cybersécurité en France.

## Accéder au Calendrier

Le calendrier est accessible et téléchargeable au format iCal en suivant ce lien : [Calendrier des Événements de Cybersécurité](https://alexandredubois.github.io/cybersecurity-events/)

Si vous voulez bénéficier des mises à jour dans votre agenda, il suffit de rajouter un calendrier à partir d'un lien internet et de coller celui-ci : https://alexandredubois.github.io/cybersecurity-events/calendar.ics

## Comment contribuer et ajouter/modifier un événement ?

Si vous souhaitez contribuer à ce projet en ajoutant ou modifiant un événement, voici la marche à suivre :

1. Clonez le dépôt GitHub : [Cybersecurity Events Repo](https://github.com/alexandredubois/cybersecurity-events)
2. Naviguez vers le fichier des événements : [events.yml](https://github.com/alexandredubois/cybersecurity-events/blob/main/docs/_data/events.yml)
3. Éditez le fichier `events.yml` pour ajouter ou modifier les informations concernant l'événement.
4. Créez une Pull Request (PR) pour soumettre vos modifications.

## Format du fichier `events.yml`

Il suffit de mettre à jour ce fichier pour que le site et le calendrier iCal soit actualisé.
Seules l'évènement avec une date précise aparaissent dans le calendrier iCal. Ceux dont la date n'a pas encore été déterminée (TBD) n'apparaissent que sur la page web.
Le fichier `events.yml` suit une structure spécifique. Voici un exemple avec la description des champs :

```yml
events:
  - Year: "Année de l'événement"
    Name: "Nom de l'événement"
    StartDate: "Date de début (format AAAA-MM-JJ, si la date n'est pas encore connue, inscrire TBD)"
    EndDate: "Date de fin (format AAAA-MM-JJ, si la date n'est pas encore connue, inscrire TBD)"
    Maybe: "Mois où l'évènement à généralement lieu (à ne valoriser que si la date n'est pas encore connue)"
    Location: "Lieu de l'événement"
    Type: "Type d'événement (Conférences, CTF, Exhibitors, etc.)"
    SubDetails: "Détails supplémentaires"
    Website: "Lien vers le site web de l'événement"
  - Year: "2023"
    Name: "Purple Pill Challenge"
    StartDate: "2023-10-13"
    EndDate: "2023-10-13"
    Location: "Nanterre (92) - At Paris YNOV Campus!"
    Type: "Conférences and CTF"
    SubDetails: "Start at 4pm, Conferences from 4pm to 8pm, CTF afterwards"
    Website: "https://www.purplepillchallenge.fr/"
  ...
