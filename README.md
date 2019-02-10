# html_tutorial- linkek és képek

## fájlok előkészítése

csinálj egy új mappát, nevezd el úgy: html_2, és csinálj benne egy index.html és egy style.css fájlt, ugyanúgy, ahogy a master branchben le van írva.

```html
<!DOCTYPE html>
<head>
  <link rel="stylesheet" href="./style.css">  
</head>
<body>
  <h1></h1>
</body>
```

## link készítése 

htmlben linket az <a> taggel csinálunk. Próbáld ki az index.html-ben:
  
 ```html
  <a>my link</a>
``` 
Így még nem mutat sehova a link, hiába kattintasz rá. Ezt úgynevezett html attribútummal tudjuk megtenni, amit minden html tagnek adni lehet.
A htmlben a linket általában "href"-nek nevezik, az attribútuma a "href" attribútum. Próbáld ki!

 ```html
  <a href="www.google.com">my link</a>
``` 
Ha azt akarod, hogy új lapon indítsa a linkedet:

 ```html
  <a href="www.google.com" target="_blank">my link</a>
``` 
Ha gondolod, google-val keress rá arra, hogy "html attributes", és rengeteg anyagot fogsz találni.

## link formázása

A link így kéken, aláhúzva nem túl szép. A style.css fájlban meg lehet formázni: 

