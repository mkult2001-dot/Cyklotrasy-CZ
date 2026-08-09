# Cyklotrasy CZ v5

PWA prototyp pro plánování silničních okruhů v ČR.

## V4 obsahuje
- nový kandidátní algoritmus okruhů s více pokusy a kontrolou návratů/backtrackingu
- tři záměrně odlišné návrhy: Nejrychlejší, Nejklidnější, Nejzajímavější
- skóre kvality trasy
- odhad podílu asfaltu, I./II. třídy a cyklostezek přes OSM/Overpass
- barevné vrstvy trasy
- profil Silniční kolo / Gravel / Trekking
- preference hlavních silnic: neřešit / preferovat jiné / absolutně vyhnout
- samostatné omezení I. a II. třídy
- až 4 průjezdní body
- maximální převýšení a maximální sklon
- výškový profil propojený s mapou
- odhad času podle průměrné rychlosti a převýšení
- počasí a vítr přes Open-Meteo
- POI: kavárny/restaurace, voda, WC, cykloservisy přes OpenStreetMap/Overpass
- OSM cyklistická síť jako otevřená heatmapová vrstva (nejde o Strava proprietární heatmapu)
- GPX export a BRouter odkaz
- PWA / instalace na iPhone

## Externí služby
- OpenStreetMap / Leaflet
- BRouter
- Overpass API
- Open-Meteo

Routing a doplňkové vrstvy vyžadují internet. Před jízdou ověř aktuální uzavírky, zákazy a stav povrchu.
