# Cyklotrasy CZ v6

PWA prototyp pro plánování silničních tras v ČR.

## Změny v6
- 3 režimy: Okruh / Tam a zpět / Vlastní
- Okruh používá pouze 3 routingové kontrolní body + start/cíl; geometrické GPX body se neposílají jako kontrolní body
- Tam a zpět vyžaduje koncový bod a vrací se po stejné geometrii
- Vlastní spojuje start → průjezdní body v pořadí → start
- maximální odchylka od požadované délky: 15 km
- maximální převýšení a maximální sklon jsou tvrdé limity
- pokud není nalezena platná trasa, aplikace to oznámí a kandidát je označen mimo limity
- GPX geometrie je pro export zjednodušena na max. 1400 bodů
- skóre již není uměle drženo nad 50
