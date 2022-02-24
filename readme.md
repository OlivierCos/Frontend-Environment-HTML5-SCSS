# <div style="foo">Description du projet :<div> 
 > Ohmyfood! est une entreprise de commande de repas en ligne. Le concept permet aux utilisateurs de composer leur propre menu et  réduire leur temps d’attente dans 4 restaurants de Paris. Une page d'accueil est également développée.

***

- 🛠️ Assurer la cohérence graphique d'un site web

🛠️ Utiliser un système de gestion de versions pour le suivi du projet et son hébergement

🛠️ Mettre en œuvre des effets CSS graphiques avancés (SCSS)

🛠️ Mettre en place son environnement Front-End

🛠️ Mettre en place une structure de navigation pour un site web

## Le développement
### Sass
* Réalisé à l'aide de Node.js 
* Télécharger le dossier node selon votre système d'exploitation sur https://nodejs.org/fr/download/
* Pour initialliser un projet, tapez sur Node:
```
$ npm init
```
* Pour l'utilisation du préprocesseur Sass : 
```
$ npm install –save sass
```
* Pour l'utilisation du préprocesseur Autoprefixer (afin de rajouter automatiquement les webkits des différents navigateurs webs) : 
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