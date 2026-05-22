# LP Tracker — Démo Groupe SEB

Application de pilotage des Programmes de Fidélité (LP) — démo front-end (profil Chef de Secteur).

## Ce que montre cette démo

- Formulaire de visite complet en 9 étapes (parcours CS terrain)
- Affichage contextuel des données magasin (meubles livrés, CA, performance vs S-1)
- Questions conditionnelles (ruptures → liste produits)
- Capture photo (avant / après intervention)
- Récapitulatif avant envoi + simulation envoi bilan
- Badge hors-ligne
- Responsive mobile / tablette / ordinateur

## Déploiement

Ce repo est déployé sur Netlify. Un seul fichier statique `index.html`, aucune dépendance serveur.

## Structure

```
index.html     → application complète (HTML + CSS + JS inline)
netlify.toml   → config redirection Netlify
```

## Prochaines étapes

- Connecter l'authentification Microsoft SSO
- Brancher la base de données magasins réelle (fichier Excel → API)
- Module Dashboard (profil DR et ADV)
- Module Anomalies / Messagerie
- Export Excel des visites
