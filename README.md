# Uebung-wmc-010  --  HTML Pfadangaben
## Assignment:

<img width="700" alt="Uebung 10 Angabe" src="https://github.com/IxI-Enki/Uebung-wmc-010/assets/138018029/cf1eda2e-05a2-4df6-abb0-e33ac1d15970">

---------
## *SPOILER*:

### Startpage:
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Startseite</title>
</head>
<body>
    <h1> Startseite </h1>
    <hr>    
    <ul>
        <li> 
            <a href="./meineWebseite/shop/shop.html"> Shop </a>
        </li>
        <li>
            <a href="./meineWebseite/produkte/produkte.html"> Produkte </a>
        </li>
        <li>
            <a href="./meineWebseite/kontakt/kontakt.html"> Kontakt</a>
        </li>
        <li>
            <a href="./meineWebseite/impressum/impressum.html"> Impressum
        </li>
    </ul>
</body>
</html>
```

###  Impressum:
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Impressum</title>
</head>
<body>
    <!-- Überschrift = Seitenbezeichnung und Verlinkungen einfügen! -->
    <h1>Impressum</h1>
    <hr>
    <a href="../../startseite.html"> Zurück zur Startseite</a>
</body>
</html>
```

### Contact:
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kontakt</title>
</head>
<body>
    <!-- Überschrift = Seitenbezeichnung und Verlinkungen einfügen! -->
    <h1>Kontakt</h1>
    <hr>
    <a href="../../startseite.html"> Zurück zur Startseite</a>
</body>
</html>
```

### Shop:
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shop</title>
</head>
<body>
    <!-- Überschrift = Seitenbezeichnung und Verlinkungen einfügen! -->
    <h1> Shop</h1>
    <hr>
    <a href="../../startseite.html"> Zurück zur Startseite</a>
</body>
</html>
```

### Products:
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Produkte</title>
</head>
<body>
    <!-- Überschrift = Seitenbezeichnung und Verlinkungen einfügen! -->
    <h1>Produkte</h1>
    <hr>
    <ol>
        <li> 
            <a href="./produkt1/produkt1.html"> Produkt 1</a>
        </li>
        <li>
            <a href="./produkt2/produkt2.html"> Produkt 2</a>
        </li>
        <li>
            <a href="./produkt3/produkt3.html"> Produkt 3</a>
        </ol>
    </ul>
    <hr>
    <a href="../../startseite.html"> Zurück zur Startseite</a>
</body>
</html>
```

#### Product One:
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Produkt_1</title>
</head>
<body>
    <!-- Überschrift = Seitenbezeichnung und Verlinkungen einfügen! -->
    <h1>Produkt 1</h1>
    <a href="../produkte.html"> Zurück zu der Produktübersicht</a> <br>
    <hr>
    <a href="../../../startseite.html"> Zurück zur Startseite</a>
</body>
</html>
```

#### Product Two:
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Produkt_2</title>
</head>
<body>
    <!-- Überschrift = Seitenbezeichnung und Verlinkungen einfügen! -->
    <h1>Produkt 2</h1>
    <a href="../produkte.html"> Zurück zu der Produktübersicht</a> <br>
    <hr>
    <a href="../../../startseite.html"> Zurück zur Startseite</a>
</body>
</html>
```

#### Product Three:
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Produkt_3</title>
</head>
<body>
    <!-- Überschrift = Seitenbezeichnung und Verlinkungen einfügen! -->
    <h1>Produkt 3</h1>
    <a href="../produkte.html"> Zurück zu der Produktübersicht</a> <br>
    <hr>
    <a href="../../../startseite.html"> Zurück zur Startseite</a>
</body>
</html>
```
