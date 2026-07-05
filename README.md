# LINIA — Piste 2 : Le Parcours créatif

Prototype statique HTML/CSS/JS qui présente LINIA comme un guide créatif : partir d’une envie, choisir une porte d’entrée, suivre un parcours conseillé, demander conseil, réserver un atelier ou choisir du matériel, offrir/prolonger puis préparer la visite locale.

## Fichiers créés
- `index.html`
- `css/styles.css`
- `js/main.js`
- `assets/placeholders/`
- `assets/brand/`
- `docs/synthese-piste-2.md`
- `docs/credits-images.md`

## Lancer en local
```bash
python3 -m http.server 8000
```
Puis ouvrir `http://localhost:8000`.

## Tester sur smartphone
Connecter ordinateur et smartphone au même Wi-Fi, puis ouvrir l’adresse IP locale de l’ordinateur suivie de `:8000`.

## Publier sur GitHub Pages
Pousser la branche, activer Pages sur la branche voulue, dossier racine.

## Transposition WordPress / WooCommerce
Les sections utilisent des classes compatibles Gutenberg (`wp-section`, `wp-container`, `wp-card-grid`) et des cartes WooCommerce-like (`wc-product-card`, `wc-workshop-card`). Les ateliers pourront devenir des produits virtuels WooCommerce avec stock limité.

## Points à adapter plus tard
Vraies photos définitives, adresse, horaires, produits réels, ateliers réels, fiches parcours, intégration WooCommerce, paiements Stripe/Mollie, Google Maps, formulaires.

## Note images
Les images du prototype sont des SVG locaux textuels dans `assets/placeholders/`. Ce choix évite les blocages de demande d’extraction liés aux fichiers binaires tout en gardant des visuels visibles sur GitHub Pages.

Pour la version finale, ces visuels pourront être remplacés par de vraies photos exportées en WebP/JPEG optimisé.
