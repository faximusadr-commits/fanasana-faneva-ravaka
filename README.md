# Fanasana Faneva sy Ravaka

Invitation de mariage — Faneva & Ravaka, 13 Novambra 2026.

## Déployer sur GitHub Pages

Ce dossier est prêt à pousser tel quel.

```bash
git init
git add .
git commit -m "Fanasana Faneva sy Ravaka"
git branch -M main
git remote add origin https://github.com/<utilisateur>/<depot>.git
git push -u origin main
```

Puis dans le dépôt : **Settings → Pages → Source: Deploy from a branch**, branche `main`, dossier `/ (root)`. L'invitation sera en ligne sur `https://<utilisateur>.github.io/<depot>/`.

## Contenu

| Fichier | Rôle |
| --- | --- |
| `index.html` | La page servie |
| `support.js` | Moteur de rendu (requis) |
| `assets/` | Illustrations, texture, plans, musique, son de page |
| `.nojekyll` | Empêche Jekyll d'ignorer des fichiers |

## À savoir

- La musique démarre au clic sur le sceau : les navigateurs bloquent la lecture automatique. Le bouton note de musique en haut à droite la coupe ou la relance.
- Le mode sombre s'active seul entre 18 h et 6 h ; le bouton rond en haut à droite le force.
- Le lien « ITINERAIRE GOOGLE MAPS » ouvre l'itinéraire avec le lieu déjà en destination ; l'invité saisit son point de départ dans le champ au-dessus du plan.
- Les réponses RSVP sont enregistrées dans le navigateur de l'invité seulement. Pour les recevoir, il faut brancher un service de formulaire (Google Forms, Formspree) sur le bouton d'envoi.

## Modifier le design

Éditez le fichier source `Fanasana Faneva sy Ravaka v2.dc.html` (à la racine du projet), puis recopiez-le en `deploy/index.html` et poussez.
