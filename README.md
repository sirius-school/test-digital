<!-- omit in toc -->
# Test Technique

## Sirius School

Avant de commencer ce petit test, est-ce que tu t'es bien pré-inscrit sur notre site web ? Si ce n'est pas le cas visite le site [Sirius School](https://siriusschool.be/). Il est **obligatoire** de te préinscrire sinon nous n'aurons aucun moyen de te contacter.

## Le test peut démarrer

Salut à toi, jeune apprenti. Voici un petit test pour évaluer tes compétences en informatique et déterminer si tu es aptes à rentrer dans une initiation chez Sirius.

- Durée du test: 30 minutes max. :clock1:
- Google est ton ami si tu as des questions :mag_right:
- Quand tu as fini ton test ou que tu es arrivé le plus loin possible, demande pour passer ton entretient avec moi. :eyeglasses: :person_bald:

Pour commencer, il te suffit de suivre à la lettre les instructions suivantes. Prend bien ton temps pour lire chaque phrase correctement et ne pas te tromper.

## Les fondations

1. Va sur le bureau de ton ordinateur.
2. Crée un dossier que tu nommeras de ton **"nom-prénom"** (ex: "Scala-Jeremy").
3. Ouvre le dossier que tu viens de créer.
4. Crée un nouveau **document texte** à l'intérieur du dossier  que tu nommeras **"index.txt"**.
5. Ouvre ce document.
6. Écris, dans ce document, quelques phrases pour te présenter. Tu peux nous donner ton parcours, tes passions, tes vacances idéales,...
7. Sauvegarde-le.
8. Ferme ensuite le document.

## L'apprentissage

Réalisons ta première "page web".

1. Ouvre de nouveau le document **"index.txt"** avec le bloc-note. 
2. Sélectionne et copie-colle (:bulb: avec le click-droit) le code suivant à la suite de ta présentation.

```html
<html>
  <head>
    <title>Je suis un titre</title>
  </head>
  <body>
   <div class="container">
      <div>
        <p></p>
      </div>
    </div>
  </body>
</html>
```

3. Sélectionne et coupe et colle ta présentation entre ```<p>``` et ```</p>```

Exemple:

```html
<p>Salut. Je suis votre formateur pour ces 2 prochains mois.</p>
```

4. Remplace **Je suis un titre** par ton pseudo ou ton nom.
5. Sauvegarde le document et ferme-le.
6. Renomme ton fichier en **index.html**
7. Ouvre-le dans un navigateur.

Bravo, tu viens de réaliser ta première page web en HTML

## Allez plus loin

Maintenant on va embellir un peu tout ça.

1. Renomme le fichier **index.html** en **index.txt** et ré-ouvre le. 
2. Copie/colle ce bout de code entre ```<head>``` et ```</head>``` et en dessous de ```</title>```

```html
    <style>
      * {
        margin: 0;
      }
      body {
        background-color: #03071E;
      }
      .container{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }
      p {
        color: #FFBA08;
        font-family: Impact, sans-serif;
        font-size: 36px;
      }
    </style>
```

Tu devrais avoir quelque chose qui ressemble à ceci si tu renommes de-nouveau le fichier et que tu l'ouvres dans ton navigateur.

![example-css](img/example-css.png)

3. Maintenant que tout est en couleur, peut-être que ce n'est pas à ton goût. Alors essaye donc de changer le **background-color** (couleur de fond) et la **color** (couleur) du texte.

:toolbox: Tu peux utiliser <a href="https://www.w3schools.com/html/html_colors_hex.asp" target="_blank">ce lien pour avoir des idées de couleurs</a>.

4. Ajoutons maintenant une image. Sélectionne et copie-colle le code suivant en dessous de ton texte (:bulb: après ```</p>```).

```html
<img src="https://media.giphy.com/media/vzO0Vc8b2VBLi/giphy.gif" alt="dogge">
```

5. Centrons cette image. Rajoute le code suivant avant le ```</style>```

```css
img {
        margin:auto;
        display: block;
      }
```

Voilà le résultat:

![example-center-img](img/example-css-center.png)

Si tu veux, et que tu as compris, tu peux changer l'image aussi. Trouve un gif rigolo qui te représente sur :toolbox: <a href="http://www.giphy.com" target="_blank">Giphy</a> (utilise la barre de recherche et clique sur "copy link" et choisis "GIF link") ou va sur <a href="http://www.google.com" target="_blank">Google</a> (utilise le click droit et choisis "Copier l'adresse de l'image")

Tu es arrivé jusque là, félicitations ! :tada:	
