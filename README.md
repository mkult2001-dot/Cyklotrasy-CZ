# Cyklotrasy CZ v6.1

PWA prototyp pro plánování silničních tras v ČR.

## Opravy v6.1
- opravené označení verze (v6.1)
- nový service worker `sw-v6.js` s novou cache, který při nasazení odstraní staré cache verze
- routingové kandidáty se načítají bez HTTP cache
- aplikace zobrazuje pouze trasy, které splní všechny tvrdé limity
- vzdálenost musí být v toleranci ±15 km
- maximální převýšení a maximální sklon jsou tvrdé limity
- Okruh filtruje vlastní křížení, opakované úseky a výrazný backtracking
- Okruh používá pouze několik kontrolních bodů; geometrické body z routingu se neposílají zpět do routeru
- Tam a zpět vrací stejnou trasu
- Vlastní spojuje start → průjezdní body → start
