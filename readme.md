# Description du projet : 
 > Ohmyfood! est une entreprise de commande de repas en ligne. Le concept permet aux utilisateurs de composer leur propre menu et  réduire leur temps d’attente dans 4 restaurants de Paris. Une page d'accueil est également développée.

***

## Le développement
### Dart-sass
* Réalisé à l'aide de SASS avec la lib dart-sass, sans JavaScript. 
* Télécharger le dossier dart-sass selon votre système d'exploitation sur github.
* Exécuter : https://github.com/sass/dart-sass/releases/tag/1.34.0
* Pour la création d'un fichier style.scss et celle d'un fichier css compilé automatiquement : 
$ ./dart-sass/sass sass/style.scss style.css --watch

### Node.js
* Ajout de Node.js pour lancer autoprefixer (afin de créer automatiquement les webkits) et preprocesseur Mediaqueries (afin de regrouper automatiquement les Mediaqueries)
* Télécharger node.js : https://nodejs.org/en/ (fichier LTS)
* Afin de compiler automatiquement autoprefixer et preprocesseur : 
$ npm run autoprefixer:watch
$ npm run sass:watch

***

## Lien github pages : 
https://oliviercos.github.io/OlivierCostel_3_02062021/