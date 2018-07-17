# html_tutorial

## fájlok előkészítése

Csinálj egy mappát, tetszőleges névvel. A mappában jobb klikk + új szöveges fájl létrehozása, nyomj entert- eredmény: új fájl.txt

Ha a mappádban látszik a fájlkiterjesztés (a fájl.txt-ben a txt a kiterjesztés), akkor a következő mondatot ne vedd figyelembe.

Ha nem látszik a pont utáni kiterjesztés, nyomj egy jobbklikket valahova a mappába, mappa beállításai menüpontra menj, és gondoskodj róla, hogy az "ismert fájltípusok kiterjesztésének elrejtése" opció **ne legyen benyomva**. Ha ez a beállítás be van csekkolva, úgy nem lehet kiterjesztéseket módosítani.

Az új fájl.txt-re ekkor nyomj két lassú bal kattintást, vagy egy jobbklikk+ átnevezést, és nevezd el index.html-nek. Ekkor láthatod, hogy a fájl ikonja megváltozik.

Ezután csinálj egy másik fájlt is, és nevezd el style.css-nek.


## html fájl tartalma

A html fájlban ennek mindenképp benne kell lennie:

```html
<!DOCTYPE html>
<head>
  <link rel="stylesheet" href="./style.css">  
</head>
<body>
  <h1></h1>
</body>
```

A html tagekről tudni kell, hogy általában van egy nyitó, és egy záróelem. Kacsacsőrök közt van a tag neve, és a záróelemben az első kacsacsőr után van egy /. De vannak olyan tagek is, aminek nincs záróeleme, mint pl. a link tag.

A link tagben a ./style.css az egy hivatkozás a style.scs fájlodra. A ./ része az azt jelenti, hogy "ugyanebben a mappában"- ez a relatív fájlelérési út.

A <head></head> tagek közt ún. metainformációk vannak, amik közvetlenül nem láthatóak, de az oldal működése szempontjából fontosak. Ilyen pl. a sytle.css stílus lapra mutató <link> tag.

A <body></body> tagek között van minden szemmel látható tartalom.

Próbáld meg, hogy a <h1></h1> közé beírsz bármit, elmented a fájlt, és utána megnyitod dupla klikkel böngészőben (ha már meg van nyitva, akkor csak frissíts rajta egyet).

A <h1></h1> tag egy főcím tag, ezért nagy betűmérettel látható, amit a tagek közé írtál.

## css fájl tartalma

Most nyisd meg a style.css-t, és írd bele ezt:

```html
body {
  background-color: pink;
}
```

Mentés és az oldal frissítése után láthatod, hogy a body (azaz az egész látható oldal) háttere rózsaszín lett. Próbáld ki pink helyett még milyen színek vannak. 

https://www.google.com/search?safe=off&client=ubuntu&hs=5qE&channel=fs&ei=ZFJOW-mfKsaakwXWx5vIDg&q=color+code+picker&oq=color+code+picker&gs_l=psy-ab.3..0i7i30k1l2j0i67k1j0i7i30k1l7.3792.3792.0.4090.1.1.0.0.0.0.124.124.0j1.1.0....0...1c..64.psy-ab..0.1.122....0.eIupfALDP88

Ezen a linken található egy színválasztó alkalmazás. Próbáld meg, mi történik, ha tetszőles színkódot (#-tel együtt) másolsz a "background-color:" után.

A .css fájl stíluslap fájl, ebben definiálod a különböző html elemek viselkedését és kinézetét. A body { ... } után írd ezt: 

```html
h1 {
  color: blue;
}
```

Ments és frissíts. Az előző linken található színválasztó segítségével használhatsz tetszőleges színt.
A color: blue; alá írd ezt, ments és frissíts:

```html
text-align: center;
```

Próbáld ki, mi történik, ha "center" helyett "right"-ot írsz!

A text-align tulajdonság alá írt ezt- egy px egy pixelt jelent. Próbálj ki különböző méreteket.

```html
font-size: 100px;
```

Vége az első órának;)

