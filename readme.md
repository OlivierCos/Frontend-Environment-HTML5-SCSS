# Description du projet : 
 > Ohmyfood! est une entreprise de commande de repas en ligne. Le concept permet aux utilisateurs de composer leur propre menu et  réduire leur temps d’attente dans 4 restaurants de Paris. Une page d'accueil est également développée.

***

## Le développement
### Sass
* Réalisé à l'aide de Node.js 
* Télécharger le dossier node selon votre système d'exploitation sur https://nodejs.org/fr/download/
* Exécuter!
* Ouvrez un terminal via Node puis, pour initialliser un projet, tapez:
```
$ npm init
```
* Pour l'utilisation du préprocesseur Sass : 
```
$ npm install –save sass
```
* Pour l'utilisation du préprocesseur Autoprefixer (afin de rajouter automatiquement les webkits des navigateurs webs dès l'ajout d'une propriété) : 
```
$ npm install –save postcss-cli autoprefixer
```
### package.json
* Un fichier package.json a été créé lors de l'initiallisation du projet npm. Afin de faire fonctionner les préprocesseurs installés, veuillez rajouter ces scripts dans le fichier .json (pour des feuilles de style appelées style.scss pour sass et style.css pour le langage css):
```
    "sass": "sass sass/style.scss sass/style.css",
    "sass:watch": "sass sass/style.scss sass/style.css --watch",
    "autoprefixer": "npx postcss sass/style.css --use autoprefixer -d ./",
    "autoprefixer:watch": "npx postcss sass/style.css --use autoprefixer -d ./ --watch",
    "dev": "npm run sass:watch & npm run autoprefixer:watch &",
    "build": "npm run sass && npm run autoprefixer"
```

***

## Lien github pages : 
https://oliviercos.github.io/OlivierCostel_3_02062021/