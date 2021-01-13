### index.html tiedoston läpikäynti

Kertoo selaimelle, että kyseessä on html-tiedosto. Esim: css:ää käytetään oikein
```html
<!doctype html> 
```

html on sivun juuri elementti
lang="fi", kertoo, että kyseessä on suomenkieltä. Tärkeätä tietoa, esim koneoppimismallille
````html
<html lang="fi">
```

head sisältää sivuston ei näkyviä, meta, tietoja
charset kohdassa valitaan käytettävä encoodaus, eli miten eri merkkejä käsitellään
rel=stylesheet - kohdassa valitaan ulkoinen tyylitiedosto
name=viewport -kohta liittyy siihen miten sivu näkyy ei laitteissa
```html
<head>
  <meta charset="utf-8">

  <title>THE HTML5-Pohja</title>
  <meta name=”viewport” content=”width=device-width, initial-scale=1.0">

  <link rel="stylesheet" href="css/styles.css?v=1.0">

</head>
```

Varsinainen, käyttäjälle näkyvä osa, sijaitsee body osassa
```html
<body>
  <script src="js/scripts.js"></script>
</body>
</html>
```
