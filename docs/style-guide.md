# Style guide

Táto referencia vychádza z aktuálneho vzhľadu v `styles.css`. Pôvodný súbor
označený ako screenshot neobsahuje použiteľný obrázok, preto sú farby a prvky
opísané podľa existujúceho CSS.

## Vizuálny dojem

Čistý, pokojný a prístupný dizajn s veľkým množstvom voľného priestoru.
Obsah je sústredený do stredu stránky a jednoduchá biela karta jemne oddeľuje
praktické informácie od pozadia. Zaoblené rohy a veľmi decentný tieň dodávajú
stránke mäkký, neformálny charakter bez zbytočných dekorácií.

## Farby

| Použitie | Farba | Odhadovaný kód |
| --- | --- | --- |
| Pozadie stránky | veľmi svetlá sivomodrá | `#F8FAFC` |
| Hlavný text a nadpisy | tmavá bridlicová | `#1E293B` |
| Sekundárny text | bridlicová sivá | `#475569` |
| Text položiek zoznamu | tmavšia bridlicová sivá | `#334155` |
| Pozadie karty | biela | `#FFFFFF` |
| Jemné orámovanie karty | svetlá sivomodrá | `#E2E8F0` |
| Pozadie vloženého kódu | svetlá sivomodrá | `#F1F5F9` |
| Nenápadná poznámka | tlmená sivomodrá | `#94A3B8` |

Používaj neutrálnu paletu a dostatočný kontrast. Výraznú akcentovú farbu
existujúci návrh nepoužíva.

## Písmo a typografia

- Bezpätkové systémové písmo: `system-ui`, s náhradami `-apple-system`,
  `"Segoe UI"` a `sans-serif`.
- Základná výška riadku je `1.5`, čo podporuje pohodlné čítanie.
- Hlavný nadpis má približne `1.875rem` a výraznú, ale nie prehnane ťažkú
  hierarchiu.
- Dôležité označenia používajú polotučné písmo (`font-weight: 600`).
- Poznámky sú menšie (`0.75rem`) a používajú tlmenú farbu.

## Tlačidlá

V aktuálnom návrhu nie sú tlačidlá, preto ich vzhľad nie je priamo definovaný.
Ak ich stránka bude potrebovať, odporúčaný štýl v rámci tejto vizuálnej identity:

- tmavé bridlicové pozadie `#1E293B` a biely text `#FFFFFF`,
- zaoblené rohy približne `0.5rem`,
- pohodlné vnútorné odsadenie a jasne čitateľný text,
- pri prejdení kurzorom mierne zosvetliť pozadie; pri fokuse zobraziť zreteľný
  obrys, aby bolo tlačidlo dobre ovládateľné aj klávesnicou.

## Karty a drobné prvky

- Karta má biele pozadie, jemné orámovanie `1px solid #E2E8F0` a zaoblenie
  približne `0.75rem`.
- Tieň je veľmi jemný: `0 1px 2px rgba(0, 0, 0, 0.05)`.
- Kód v texte má svetlé sivomodré pozadie, malé horizontálne odsadenie
  a mierne zaoblenie rohov.
- Emoji môže slúžiť ako jednoduchý, priateľský vizuálny akcent.

## Rozloženie

Hlavný obsah je vycentrovaný horizontálne aj vertikálne. Text úvodu je
centrovaný, zatiaľ čo obsah karty a zoznam sú zarovnané doľava. Blok obsahu
má obmedzenú šírku približne `36rem` a stránka zachováva vonkajšie odsadenie
aj na menších obrazovkách.
