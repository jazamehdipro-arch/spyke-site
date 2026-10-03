# Site vitrine Spyke : spykeconseil.fr

Site statique : trois fichiers HTML, une feuille de style, rien à compiler.
Il s'ouvre en double-cliquant sur `index.html`.

## Avant la mise en ligne

Le contenu est complet. Le téléphone (06 66 88 42 37) et l'adresse e-mail
(contact@spykeapp.fr) sont les vrais, à changer seulement si une ligne ou une
boîte est créée sur le nouveau domaine.

Les mentions légales et la politique de confidentialité reprennent les
informations publiées sur spykeapp.fr (JAZA Mehdi, auto-entrepreneur,
SIRET 929 238 566 00020). La politique de confidentialité a été réécrite pour ce
site : il n'y a ici ni compte utilisateur, ni paiement, ni accès Gmail, donc rien
de tout cela n'y figure.

Reste la prise de rendez-vous, décrite ci-dessous.

## La prise de rendez-vous

Le bloc « Choisir un créneau » attend un outil d'agenda. Tant qu'il n'est pas
branché, il affiche le téléphone et l'adresse e-mail. Un visiteur n'est jamais
bloqué.

Pour le brancher, coller le code fourni par l'outil (Cal.com, Calendly…) à
l'intérieur de `<div id="reservation-embed">` dans `index.html`, en remplaçant le
bloc `<div class="secours">`.

## Mise en ligne

1. Acheter `spykeconseil.fr` chez un bureau d'enregistrement (OVH, Gandi,
   Infomaniak). Aucune option supplémentaire n'est nécessaire : ni hébergement,
   ni « pack site ».
2. Créer un projet sur Vercel à partir de ce dépôt. Aucun réglage : Vercel
   reconnaît un site statique.
3. Dans Vercel, ajouter le domaine `spykeconseil.fr`, puis recopier les deux
   enregistrements DNS indiqués chez le bureau d'enregistrement. Le certificat
   HTTPS se pose tout seul.

Ce site est totalement indépendant de `spykeapp.fr` : un problème ici ne peut pas
toucher la facturation ni l'outil de prospection.
