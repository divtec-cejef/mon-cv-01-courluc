* Nom des fichiers et dossiers **en minuscules, sans espaces et sans 
  caractères spéciaux** `CSS/Trop Stylé.css` > `css/trop-style.css`
* Créer un dossier pour les icones du site
* Éviter de donner des tailles aux images en HTML, le faire en CSS avec 
  `height` et `width`
* Dans l'entête inclure les polices avant les CSS
* Séparer le contenu `<body>` en trois parties :
```html
<body>
    <header>
        ...
    </header>
    <main>
       ...
    </main>
    <footer>
       ...
    </footer>
</body>
```
* Eviter les lignes de code trop grandes (plus de 100 caractère)
```html
<!-- FAUX -->
<a href="./icone/apple-touch-icon.png"><img src="icone/favicon-32x32.png" alt="photo pour mon cv" title="Cliquez pour agrandir" ></a>
<!-- JUSTE -->
<a href="./icone/apple-touch-icon.png">
    <img src="icone/favicon-32x32.png"
         alt="photo pour mon cv"
         title="Cliquez pour agrandir"
    >
</a>
```
* Ne pas utiliser `<strong>` pour mettre en gras tout les `<li>`
* Pas d'espaces ni de majuscules, ni de caractères spéciaux dans les id ou
    class, utiliser des `-` ou  `_` à la place. `class="épéeRouge"` > `class="epee-rouge"`
* On peut ajouter l'objet de l'e-mail `<a href="mailto:steve.fallet@divtec.ch?subject=tutu">` 
* Pour les images d'arrière-plan, mettre l'url ou le chemin entre guillemets
```css
/* Faux */
background-image: url(https://img.freepik.com/photos.jpg);
/* Juste */
background-image: url("https://img.freepik.com/photos.jpg");
```


* Il manque des instructions pour le design de base du site
```css
body {
    font-family: Verdana, sans-serif;   /* Police d'écriture de base */
    font-weight: normal;                /* Épaisseur du texte de base*/
    font-size: 1.2rem;                  /* taille du texte de base*/
    line-height: 1.4;                   /* Hauteur de ligne de base, généralement entre 1.3 et 1.7 */
    color: black;                       /* couleur du texte de base*/
    background-color: white;            /* couleur d'arrière plan du site */
}
```
* Dès que l'on change la police d'écriture, il faut préciser l'épaisseur à utiliser
```css
h1 {
    font-family: "Sofia Sans Semi Condensed", sans-serif;
    font-weight: 400;
}
```

* Définir le style des liens, couleur.
```css
a {
    color:red;
}
```
* Proposer un style différent pour les liens survolés
```css
a:hover {
    color:blue;
}
```
* `max-width: 100%` pour toutes les images
```css
img {
    max-width: 100%;
    height: auto;
}
```

