# Test de compétences en développement front-end

## Consignes 

- Intégrer la landing page dans le respect de la maquette et des normes HTML5/CSS3
- Utiliser le framework Tailwind CSS pour construire les différents éléments de la page
- Créer une palette de couleurs avec Tailwind
- Utiliser les icônes Fontawesome et Linearicons (inclues)

Facultatif : 
- Déclinaison responsive complète ou partielle
- Ajout d'animations

## Informations utiles

La maquette se trouve dans le répertoire /src.
Les images se trouvent dans le répertoire /images.

### Utilisation du framework Tailwind CSS

Il est recommandé de prendre connaissance du fonctionnement général de Tailwind : https://tailwindcss.com/

Pour cet exercice, l'utilisation des classes Tailwind directement dans le fichier index.html est à préconiser (approche utilitaire) : https://tailwindcss.com/docs/utility-first

Pour appliquer des styles de base aux éléments (titres, liens, texte...), le fichier à modifier est tailwind.css. Le fichier style.css sert de "sortie" après la compilation du CSS et ne doit pas être modifié.
https://tailwindcss.com/docs/adding-base-styles

#### Configuration
Tailwind est déjà installé et prêt à fonctionner.

Vous devrez configurer vous même la palette de couleurs dans le fichier tailwind.config.js 

Voici la liste des couleurs à implémenter :
- Bleu : #277DF4
- Jaune : #F4BA3C
- Vert : #6FC854
- La palette de gris par défaut de Tailwind

Support pour la customisation des couleurs : https://tailwindcss.com/docs/customizing-colors

Note : penser à compiler après chaque modification du fichier tailwind.css ou tailwind.config.js.

#### Compilation 
Pour fonctionner, le CSS devra être compilé. Pour cela, vous lancerez le script "build" présent dans le fichier package.json.