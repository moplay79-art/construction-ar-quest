# Construction AR Quest — v0.5 Offline

## Objectif
Après un premier chargement en ligne, l'application est mise en cache localement sur le Quest.

## Test
1. Mettre tous les fichiers de ce dossier à la racine du dépôt GitHub Pages.
2. Ouvrir la page en ligne sur le Quest.
3. Attendre le message « Mode hors ligne préparé ».
4. Fermer puis rouvrir une fois la page en ligne.
5. Couper le Wi-Fi du Quest.
6. Rouvrir la même adresse.
7. Vérifier que l'application s'ouvre et que le chantier/ancrage restent disponibles.

## Important
Cette v0.5 utilise un Service Worker. Le tout premier chargement reste nécessaire via HTTPS. La cible finale la plus robuste reste une PWA WebXR empaquetée / application installée localement sur le Quest.
