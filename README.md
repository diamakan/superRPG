# Les Gardiens du Bonnet (Super RPG)

RPG tactique au tour par tour, en vue isométrique 3D (three.js), dans la vallée de Mailleval.

- 6 personnages au choix, 9 classes : chevalier, mage, invocateur, voleur, archer, soigneur, lancier, moine, barde
- Histoire en 5 chapitres, 6 quêtes annexes, terrain d'entraînement répétable
- Jusqu'à 4 personnages dans l'équipe, niveaux et expérience
- Équipement : armes, bonnets et casques, plastrons, gants, chaussures ; boutique
- Sauvegarde automatique sur l'appareil

## Jouer

Une fois GitHub Pages activé (Settings → Pages → Deploy from a branch → `main` / root) :
https://diamakan.github.io/superRPG/

Sur téléphone : ouvrir le lien, puis « Ajouter à l'écran d'accueil » (fonctionne hors connexion).

## Fichiers

- `index.html` : tout le jeu (données, combat, écrans)
- `three.min.js` : moteur 3D three.js r128 (licence MIT)
- `manifest.webmanifest`, `sw.js`, `icon-*.png` : installation en PWA

Après une modification du jeu, changer `VERSION` dans `sw.js`.
