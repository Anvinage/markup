# Markdown Dokumentation

- Det er meget let at lære
- Let at læse og skrive
- Minimalistisk
- Kan fremhæve indhold
- Meget flexibelt

## Kode eksempel på javascript loop
```Javascript
var fruits = ["æble", "banan", "appelsin", "jordbær"];

var outputElement = document.getElementById("output");

for (var i = 0; i < fruits.length; i++) {
    
    var fruitElement = document.createElement("p");
    
    fruitElement.textContent = fruits[i];
    
    outputElement.appendChild(fruitElement);
}
```

## Kode eksempel på HTML

```html
<nav>
        <ul>
            <li><a href="#link1">Link 1</a></li>
            <li><a href="#link2">Link 2</a></li>
            <li><a href="#link3">Link 3</a></li>
        </ul>
    </nav>
```
## Billede af blomst
![flot blomst](img/blomst.jpg)


## Citat
> "Fantasi er vigtigere end viden. For viden er begrænset til alt, hvad vi nu ved og forstår, mens fantasi omfavner hele verden, og alt hvad der nogensinde vil blive kendt og forstået."
>
> — Albert Einstein
