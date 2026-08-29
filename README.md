# Cyklotrasy CZ v7
Plnohodnotný prototyp s Mapy.com: turistická mapa, bike_road routing, Okruh / Tam a zpět / Vlastní, 3 kandidáti, cílová délka, převýšení, sklon, avoidHighways a GPX-ready geometrie.

## Nasazení
Nahraj `index.html` do kořene GitHub Pages repozitáře.

## API
Klíč se neukládá do repozitáře. V aplikaci ho vlož a ulož do localStorage. V Mapy.com doporuč omezení na `mkult2001-dot.github.io` a pouze potřebné služby.

## Poznámka
Mapy.com `avoidHighways` podle dokumentace znamená vyhnutí dálnicím/rychlostním komunikacím; není to garance vynechání všech silnic I. třídy. Pro přesnou filtraci I. tříd by byl potřeba další datový zdroj (např. OSM).
