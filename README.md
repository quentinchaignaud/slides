# Slides

Ce repository contient les différentes slides utilisées pour mes cours ou mes vidéos Youtube. Elles se trouvent dans le dossier /slides. Il est basé sur la librarie (reveal.js)[https://revealjs.com/]

## Installation

Clonez le repo et installez les dépendances :

```bash
https://github.com/quentinchaignaud/slides.git
```

```bash
cd slides && npm i
```

## Utilisation 

Pour charger un diapo, il suffit de renseigner le chemin du fichier dans le fichier index.html, à la ligne 22.

```html
<section 
  data-markdown="<chemin-du-markdown>" 
  data-separator="^\n\n\n" 
  data-separator-vertical="^\n\n">
</section>

```

Puis le lancer :

```bash
npm run start
```

## Licence

Les slides sont libres d'utilisation, sous licence MIT. Pour la librarie, se référer à (reveal.js)[https://revealjs.com/].