# La Caravane, Bétheny (Reims) : refonte du site

Maquette fonctionnelle de lacaravane-reims.fr, en un seul fichier HTML, sans build.

## Voir le site
Ouvrir index.html dans un navigateur, ou activer GitHub Pages (Settings > Pages > branche main, dossier racine).

## Contenu
- index.html : la page complète (HTML, CSS, JS)
- *.jpg : photos de la salle (issues du site actuel, 1600 px max)
- favicon.png

## Réglages (en haut du script, dans index.html)
- FORM_ENDPOINT : URL qui reçoit la demande de devis en POST JSON. Vide, le formulaire ouvre la messagerie du visiteur.
- CONTACT_EMAIL : adresse qui reçoit les demandes.
- TOUR_URL : adresse d'une visite virtuelle 360 intégrable en iframe. Vide, la section est masquée.

## Informations à confirmer avec le client
- Adresse exacte (17 rue des Docks Rémois, 51450 Bétheny)
- Tarifs des formules conviviales (27, 32, 43 €, buffet dès 35 €) et droit de bouchon (7 €)
- Partenaire traiteur affiché (Cuisin'&Soleil)
- Droits d'utilisation des photos (crédit ViZualCréa)
