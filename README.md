# IA PRATIQUE — Page de vente

Page de vente de l'ebook **IA PRATIQUE** de Gaston N3 (un seul fichier HTML, sans dépendance).

## Mettre en ligne avec GitHub Pages
1. Crée un dépôt GitHub et envoie `index.html` (et `README.md`).
2. Dépôt > **Settings** > **Pages** > Source : **Deploy from a branch**, branche `main`, dossier `/ (root)`.
3. Après quelques minutes, ta page est en ligne à l'adresse `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`.

## Fichiers
- `index.html` : la version à publier (tes chiffres réels).
- `apercu-demo.html` : aperçu du design avec chiffres d'exemple (compteur qui monte, chrono qui boucle). À garder pour toi, ne pas publier.

## Tes chiffres (dans `index.html`, cherche `var OFFER=`)
```js
var OFFER={sales:160, reviews:20, deadline:null, counterUrl:""};
```
- `sales` : ton VRAI nombre de ventes (mets le bon chiffre).
- `reviews` : le nombre d'avis affichés.
- `deadline` : date de fin de l'offre, ex. `"2026-10-31T23:59:59"` (le chrono n'apparaît que si elle est renseignée).

## Mettre à jour les ventes SANS modifier le site (Google Sheets)
1. Crée une feuille Google Sheets avec, en A1, ton nombre de ventes (ex. `160`) et, en B1 (facultatif), la date de fin de l'offre au format `2026-10-31T23:59:59`.
2. Fichier > Partager > Publier sur le Web > choisis la feuille et le format **CSV** > Publier, puis copie le lien.
3. Colle ce lien dans `counterUrl:"..."` dans `index.html`.

À chaque vente, tu changes seulement le nombre dans la feuille depuis ton téléphone : la page se met à jour toute seule.

Contact WhatsApp : 06 862 17 44 (variable `link`).
