# Quiz 3D — Maison (fondations → toiture)

Ce dossier contient une application web simple pour faire un quiz. À chaque bonne réponse, une partie du modèle 3D est révélée.

## Contenu
- `index.html` : l'application (visionneuse 3D + quiz + réglages)
- `assets/1_Maison.glb` : le modèle 3D (GLB)

## Utilisation
1. Placez l'ensemble du dossier sur votre ordinateur.
2. Ouvrez un terminal dans ce dossier et lancez un petit serveur local :
   - Avec Python : `python -m http.server 8000`
   - Puis ouvrez le navigateur à l'adresse : `http://localhost:8000`
3. Dans l'application :
   - Cliquez sur **Noms → Console** pour lister tous les objets nommés du modèle (F12 → Console).
   - Dans **Réglages du modèle**, pour chaque thème, choisissez l'objet du GLB à révéler.
   - Cliquez **Enregistrer le mapping**.
   - Démarrez le **Quiz** et observez la révélation progressive du modèle.

## Remarques
- L'application utilise Three.js depuis un CDN (connexion Internet requise lors de la première utilisation).
- Le mapping est mémorisé dans le navigateur (localStorage).
- Les touches **H**, **A**, **R** permettent respectivement de **masquer**, **afficher** et **recentrer** la vue.
