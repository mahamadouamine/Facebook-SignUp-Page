# Formulaire d’inscription Facebook

## Description

Ce projet est une reproduction de la page d’inscription de Facebook.
Il a été réalisé avec HTML et CSS pour apprendre à créer une interface claire, bien organisée et responsive.
Le but est d’imiter la présentation du vrai formulaire tout en comprenant le fonctionnement du code.


## Structure du projet

Le projet est composé de deux fichiers principaux :
index.html→ contient le contenu et la structure du formulaire
style.css → gère la mise en forme, les couleurs, la taille des éléments et le positionnement

Le fichier CSS applique les styles à chaque partie du HTML pour obtenir un résultat soigné et équilibré.


## Contenu du formulaire

1. Titre: "Créer un compte" et "C’est rapide et facile".
2. **Champs utilisateur** :

   * Prénom
   * Nom
   * Numéro de téléphone ou adresse e-mail
   * Mot de passe
3. Date de naissance : trois listes déroulantes pour jour, mois et année.
4. Genre : trois choix (Femme, Homme, Personnalisé).
5. Texte d’informations : indique les règles et conditions d’utilisation.
6. Bouton “S’inscrire” : permet d’envoyer le formulaire (simulation uniquement).


## Mise en page (HTML)

Le HTML utilise des div bien organisées :

* .formulaire-inscription: pour tout le formulaire
* .creation-compte: pour le titre
* .utilisateur, .horizontale, .verticale: pour les champs
* .date-naissance et .options-genre: pour les sélections
* .inscrire: pour le bouton final

Chaque section est séparée et claire pour faciliter la lecture et les modifications.


## Mise en forme (CSS)

Le CSS contrôle tout l’aspect visuel :

* Utilisation de flexbox pour aligner les éléments
* Coins arrondis (border-radius) pour un effet doux
* Couleur principale : bleu clair et blanc
* Effet hover sur le bouton S’inscrire pour le rendre plus dynamique

Les champs ont une grande taille (jusqu’à 75px de hauteur) pour améliorer la lisibilité.


## Version mobile

Grâce à la section @media (max-width: 480px) :

* Le formulaire devient plus petit et lisible sur téléphone
