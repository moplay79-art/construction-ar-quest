# Construction AR Quest — v0.5.1 Offline

Correctif de la v0.5.

## Correction
La v0.5 contenait une erreur JavaScript qui empêchait `checkSupport()` de s'exécuter.
Le symptôme était exactement : **Détection WebXR…** qui restait affiché sans évoluer.

La v0.5.1 corrige cette erreur et utilise un nouveau nom de cache Service Worker
pour ne pas conserver l'ancienne page cassée.

## Mise à jour GitHub
Remplacer TOUS les fichiers de la v0.5 par ceux de cette v0.5.1 :
- index.html
- sw.js
- manifest.webmanifest
- icon-192.png
- icon-512.png

Après le commit, ouvrir l'URL Quest avec `?v=051` une première fois, par exemple :
`https://...github.io/construction-ar-quest/?v=051`

Cela force le navigateur à demander la nouvelle page.
Une fois la nouvelle version chargée, le cache hors ligne v0.5.1 prend le relais.

## Résultat attendu
La ligne ne doit plus rester sur « Détection WebXR… ».
Elle doit passer à :
`Quest/WebXR MR détecté ✓`
ou afficher une erreur explicite si WebXR n'est pas disponible.
