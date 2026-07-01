# Maroc 2030 — Diplomatie sportive digitale

Cartographie interactive de la stratégie à cinq piliers (Chapitre 9, Partie III), construite fidèlement à partir du contenu du document `PARTIE_trois__1_.docx` : vision, graphe de dépendances entre piliers, fiches détaillées par pilier (actions, KPI, chefs de file), doctrine, calendrier 2026–2032, gouvernance, tableau de bord global 2026–2035 et modèle théorique.

Fichier unique, aucune dépendance externe (D3.js est inclus localement dans `d3.min.js`) — s'ouvre directement en local ou se déploie tel quel.

## Déployer sur GitHub Pages

1. Créez un nouveau dépôt GitHub (ou utilisez-en un existant).
2. Ajoutez `index.html` et `d3.min.js` à la racine du dépôt (ou dans un dossier `/docs`).
3. Poussez le commit :
   ```bash
   git init
   git add index.html d3.min.js README.md
   git commit -m "Cartographie stratégie Maroc 2030"
   git branch -M main
   git remote add origin https://github.com/<votre-utilisateur>/<votre-repo>.git
   git push -u origin main
   ```
4. Dans le dépôt GitHub : **Settings → Pages → Source**, choisissez la branche `main` et le dossier `/ (root)` (ou `/docs` si vous avez utilisé ce dossier).
5. Le site sera disponible à `https://<votre-utilisateur>.github.io/<votre-repo>/` après quelques minutes.

## Développement local

Ouvrez simplement `index.html` dans un navigateur, ou servez le dossier :
```bash
python3 -m http.server 8000
```
puis visitez `http://localhost:8000`.
