# PlayBox e-shop projektas

## Projekto aprašymas

Šis projektas yra paprasta internetinė parduotuvė, sukurta naudojant tik **HTML5** ir **CSS3**.
Projektas atliktas pagal užduotį sukurti responsyvų e-shop dizainą be JavaScript.

Parduotuvės tema – **vaikų žaislai**.
Pasirinktas spalvingas ir draugiškas dizainas, pritaikytas tiek mobiliesiems įrenginiams, tiek didesniems ekranams.

## Projekto tikslas

Sukurti 3 pagrindinius e-shop puslapius:

- prekių sąrašo puslapį
- vienos prekės puslapį
- krepšelio puslapį

Taip pat užtikrinti:

- tvarkingą HTML struktūrą
- estetišką CSS dizainą
- navigaciją tarp puslapių
- responsive išdėstymą
- hover efektus

## Naudotos technologijos

- HTML5
- CSS3
- Flexbox
- CSS Grid

## Puslapiai

### 1. `products.html`

Prekių katalogo puslapis.

Jame pateikiama:

- bent 6 prekės
- prekės nuotrauka
- pavadinimas
- kaina
- nuoroda į vienos prekės puslapį
- nuoroda į krepšelį

### 2. `product.html`

Vienos prekės detalus puslapis.

Jame pateikiama:

- didelė prekės nuotrauka
- prekės pavadinimas
- kaina
- aprašymas
- mygtukas „Pirkti“ / „Pridėti į krepšelį“

### 3. `cart.html`

Krepšelio puslapis.

Jame pateikiama:

- statinis prekių sąrašas
- kiekis
- kaina
- bendra suma
- mygtukas „Apmokėti“

## Dizaino sprendimai

Projektas kurtas pagal **mobile first** principą.

Pagrindiniai dizaino sprendimai:

- šviesus ir draugiškas spalvynas
- aiški tipografinė hierarchija
- kortelių dizainas produktams
- hamburger meniu mobiliems įrenginiams
- hover efektai mygtukams ir kortelėms
- responsive išdėstymas planšetėms ir desktop ekranams

## Failų struktūra

```text
eshop/
├── index.html
├── shop/
│   ├── products.html
│   ├── product.html
│   └── cart.html
├── assets/
│   └── css/
│       ├── style.css
│       └── cart.css
│       └── product.css
└── README.md
```
