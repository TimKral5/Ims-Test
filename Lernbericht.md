# Lern-Bericht
Tim Kral

## Einleitung
Ich habe eine Benutzeroberfläche für mögliche spätere Projekte erstellt.

## Was habe ich gelernt?
Ich habe gelernt, mit CSS besser umzugehen.

## Beschreibung
Hier ein Beispiel:
```css

/* 
    Style of the "Explorer"-field
*/
[data-ws-type="explorer"] {
    position: absolute;
    top: 30px;
    left: 50px;
    bottom: 20px;
    width: 180px;
    background-color: rgb(15, 15, 15);
}

/* 
    Style of the Top-Navigation-Bar
*/
[data-ws-type="toolbox-top"] {
    position: absolute;
    top: 0px;
    left: 0px;
    right: 0px;
    height: 30px;
    background-color: rgb(30, 30, 30);
}

/*
    Style of the Left-Navigation-Bar
    (currently empty)
*/
[data-ws-type="toolbox-side"] {
    position: absolute;
    top: 30px;
    left: 0px;
    bottom: 20px;
    width: 50px;
    background-color: rgb(37, 37, 37);
}

/*
    Style of the Bottom-Navigation-Bar
    (Currently empty)
*/
[data-ws-type="toolbox-bottom"] {
    position: absolute;
    bottom: 0px;
    left: 0px;
    right: 0px;
    height: 20px;
    background-color: rgb(30, 30, 30);
}

/*
    Style of the Content-Body
    (containing tabs)
*/
[data-ws-type="body"] {
    position: absolute;
    top: 30px;
    left: 230px;
    bottom: 20px;
    right: 0px;
    background-color: rgb(10, 10, 10);
    color: lightgray;
    overflow-y: scroll;
}

```
> Die in den eckigen Klammern festgelegten Attribute können einfach auf ein HTML-Element angewendet werden (wohl bemerkt ohne Attribute wie 'id' oder 'class' übermässig zu belasten) und schon werden die festgelegten Eigenschaften angewendet. 

Beispiel:

```html

    <!-- Top-Navigation-Bar -->
    <div data-ws-type="toolbox-top">

    </div>

    <!-- Side-Navigation-Bar -->
    <div data-ws-type="toolbox-side">

    </div>

    <!-- Content-Body -->
    <div data-ws-type="body">

    </div>

    <!-- Bottom-Navigation-Bar -->
    <div data-ws-type="toolbox-bottom">

    </div>


```

## Verifikation

> Ich musste eines erneut ins Gedächtnis rufen (mittels [W3Schools](https://www.w3schools.com/)) und habe demenstprechend viel gelernt in Sachen CSS.

# Reflektion zum Arbeitsprozess

> 👍 Ich konnte effektiv arbeiten, da ich bereits diverse Dokumentationen kenne, in denen ich mein Gedächtnis auffrischen kann und weil ich auch schon viel mit CSS gearbeitet habe.

> 👎 Die Arbeit daran war anstrengend, da ich uhrzeitlich erst sehr spat am Abend daran gearbeitet habe.

> **VBV**: Ich möchte im Rahmen des Lernateliers an eben solchen Projekten arbeiten und gedenke dies auch zu tun.
