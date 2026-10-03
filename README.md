# Site vitrine Spyke : spykeconseil.fr

Site statique : trois fichiers HTML, une feuille de style, rien à compiler.
Il s'ouvre en double-cliquant sur `index.html`.

## Avant la mise en ligne : à remplir

1. **Le téléphone et l'adresse e-mail**, dans `index.html` (section « Réserver »
   et pied de page) : chercher `00 00 00 00 00` et `contact@spykeconseil.fr`.
2. **Rien d’autre.** Les mentions légales et la politique de confidentialité
   reprennent les informations publiées sur spykeapp.fr (JAZA Mehdi,
   auto-entrepreneur, SIRET 929 238 566 00020). La politique de confidentialité
   a été réécrite pour ce site : il n’y a ici ni compte utilisateur, ni
   paiement, ni accès Gmail, donc rien de tout cela n’est mentionné.
3. **La prise de rendez-vous** : voir ci-dessous.

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
