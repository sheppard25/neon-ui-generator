# Neon UI Generator

Generateur d'interfaces neon gaming - Frames avatar, overlays stream, export SVG

Application Electron + React pour créer des frames d'avatar néon, overlays webcam et éléments UI gaming.

## Installation

```bash
git clone https://github.com/sheppard25/neon-ui-generator.git
cd neon-ui-generator
npm install
```

## Fichier manquant : src/App.js

**IMPORTANT:** Le fichier `src/App.js` est trop volumineux pour être créé via l'interface web GitHub.

Tu dois le créer manuellement dans `src/App.js` avec le code complet du générateur.

Le code complet App.js est disponible dans les discussions de ce projet ou tu peux me demander de te l'envoyer.

## Lancement

```bash
npm start
```

Cela lance React sur `http://localhost:3000` puis ouvre la fenêtre Electron.

## Fonctionnalités

- **Formes:** Cercle, Hexagone, Bouclier, Carré
- **Presets:** Avatar rond streamer, Overlay webcam, Badge hex techno
- **Réglages:** Épaisseur, intensité glow, couleur
- **Ailes cyberpunk:** ON/OFF
- **Double halo:** Cercles concentriques
- **Mode overlay:** Cadre + barre texte pour webcam
- **Export:** SVG prêt pour OBS/Discord
- **Import/Export:** Presets JSON

## Structure

```
neon-ui-generator/
├── package.json
├── public/
│   ├── electron.js
│   └── index.html
└── src/
    ├── index.js
    ├── App.js  (À CRÉER)
    └── App.css
```
