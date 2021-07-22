<!-- omit in toc -->
# Test digital

*a revoir* Salut à toi jeune apprenti. Voici un petit test pour évaluer tes compétences et déterminer si tu es aptes à rentrer dans une initiation chez Sirius

*wip* Google is your ami

## Les fondations

1. Va sur la bureau.
2. Crée un dossier que tu nommeras de ton **"nom-prénom"** (ex: "Scala-Jeremy")
3. Ouvre le dossier
4. Crée un nouveau **document texte** à l'intérieur du dossier  que tu nommeras **"index.txt"**
5. Ouvre ce document. :bulb: Tu dois utiliser un double-click.
6. Écris, dans ce document, quelques phrases pour te présenter. Tu peux nous donner ton parcours, tes passions, tes vacances idéales,...
7. Sauvegarde-le. :bulb: Utilise le raccourcis **ctrl+s** ou le menu "Fichier".
8. Ferme ensuite le document. :bulb: Utilise le raccourcis **ctrl+w** ou le menu "Fichier" devrait t'aider.

## L'apprentissage

Réalisons ta première "page web".

1. Ouvre de nouveau le document **"index.txt"** avec le bloc-note. (:bulb: utilise le click-droit et choisis "ouvrir avec...")
2. Copie-colle le texte suivant à la suite de ta présentation

```html
<html>
  <head>
    <title>Je suis un titre</title>
  </head>
  <body>
    <div>
      <p></p>
    </div>
  </body>
</html>
```

1. :scissors: Coupe ta présentation et colle là entre ```<p>``` et ```</p>```

Exemple:

```html
<p>Salut. Je suis votre formateur pour ces 2 prochains mois.</p>
```

4. Remplace **Je suis un titre** par ton pseudo ou ton nom.
5. Sauvegarde le document et ferme-le.
6. Renomme ton fichier en **index.html**
7. Ouvre-le dans un navigateur. :bulb: Double-click dessus.

Bravo, tu viens de réaliser ta première page web en HTML

## Allez plus loin

Maintenant on va embellir un peu tout ça.

1. Renomme le fichier **index.html** en **index.txt** et ré-ouvre le. 
2. Copie/colle ce bout de code entre ```<head>``` et ```</head>``` et en dessous de ```<title>```

```html
    <style>
      * {
        margin: 0;
      }
      body {
        background-color: #03071E;
        display: flex;
        align-items: center;
        justify-content: center;
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

2. Maintenant que tout est en couleur, peut-être que ce n'est pas à ton goût. Alors essaye donc de changer le **background-color** (couleur de fond) et la **color** (couleur) du texte.

:toolbox: Tu peux utiliser [ce lien pour avoir des idées de couleurs](https://www.w3schools.com/html/html_colors_hex.asp).

3. Ajoutons maintenant une image. Copie/colle le code suivant en dessous de ton texte.

```html
<img src="http://gph.is/294SopV" alt="dogge">
```

4. Centrons cette image. Rajoute le code suivant avant le ```</style>```

```css
img {
        margin:auto;
        display: block;
      }
```

Voilà le résultat:

![example-center-img](img/example-css-center.png)

Si tu veux, et que tu as compris, tu peux changer l'image aussi. Trouve un gif rigolo qui te représente sur :toolbox: [Giphy](www.giphy.com)