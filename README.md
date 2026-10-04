# Construction AR Quest — v0.6 Controller / Offline

Version issue des essais réels sur Meta Quest 3.

## Corrections
1. Retour du vrai pas-à-pas :
   - 1er clic : placement + Bases
   - joystick : réglage
   - 2e clic : verrouillage / mémorisation
   - clic suivant : Poteaux
   - clic suivant : Poutres
   - clic suivant : Chevrons / tasseaux
   - clic suivant : Pergola complète

2. Placement sans boutons d'écran en MR :
   - joystick gauche : translation au sol
   - joystick droit gauche/droite : rotation
   - joystick droit haut/bas : hauteur
   - maintenir Grip : mode fin

3. Les boutons HTML sont désactivés en immersion afin d'éviter les blocages rencontrés
   lors du déplacement par boutons.

4. Le mode hors ligne, la mémoire du chantier et l'ancrage persistant sont conservés.

## Mise à jour GitHub
Remplacer tous les fichiers précédents par ceux de ce paquet puis Commit changes.

Première ouverture conseillée :
`...?v=060`

Le nouveau Service Worker utilise un cache v0.6, donc l'ancienne copie v0.5.1 sera remplacée.

## Test Quest conseillé
1. Entrer en MR.
2. Viser le sol + gâchette.
3. Vérifier que seules les bases sont visibles.
4. Déplacer avec le joystick gauche.
5. Tourner / régler la hauteur avec le joystick droit.
6. Maintenir Grip et vérifier que le mouvement devient plus lent.
7. Gâchette pour verrouiller.
8. Gâchette : poteaux.
9. Gâchette : poutres.
10. Gâchette : chevrons/tasseaux.
11. Gâchette : pergola complète.
12. Marcher autour et vérifier l'ancrage.
