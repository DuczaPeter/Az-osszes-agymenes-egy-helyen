# AGENTS.md – sPg Star Citizen Tools Landing

Ez a fájl Codex, ChatGPT vagy más fejlesztői agent számára készült.

## Projektcél

A `DuczaPeter.github.io` a publikus sPg Star Citizen projektek központi, egyszerűen használható katalógusa.

## Nem tárgyalható szabályok

1. **A landing oldal egyetlen önálló `index.html`.**
   - CSS beágyazva.
   - JavaScript beágyazva.
   - Runtime sidecar nem kötelező.
2. A repository többi `.md` fájlja dokumentáció, jogi notice és fejlesztői handoff.
3. Projektfunkciót kizárólag:
   - az adott GitHub README,
   - tényleges HTML/UI,
   - vagy ellenőrzött projektforrás
   alapján írj le.
4. **Ne hallucinálj.**
5. A `PROJECTS.md` legyen összhangban az `index.html` kártyáival.
6. A fan-site notice maradjon jól látható, az RSI hivatalos oldal linkjével.
7. A landing MIT licence nem terjeszthető rá:
   - Star Citizen / CIG / RSI IP-re;
   - UEX adatokra;
   - SCMDB adatokra;
   - más repositoryk eltérő licencű kódjára.
8. Titkot, tokent, privát fixture-t, személyes logot ne commitolj.
9. Az üres vagy fejlesztés alatt álló repositoryt ne mutasd kész termékként.
10. A linkek `target="_blank"` esetén kapjanak `rel="noopener"` attribútumot.

## Dizájn

Tartsd meg az sPg vizuális rendszert:
- sötét kék / fekete háttér;
- cyan keretek és glow;
- sárga/arany Star Citizen-szerű akcentus;
- jól olvasható panelek;
- reszponzív desktop + mobil;
- túlzsúfoltság nélkül.

## Release gate

Módosítás előtt/után ellenőrizd:

- HTML megnyílik;
- nincs külső kötelező CSS/JS;
- kereső működik;
- kategóriaszűrők működnek;
- minden kártyának van GitHub linkje;
- kész projekt csak ellenőrzött állapotból jelenik meg aktívként;
- fan-site notice látható;
- hivatalos RSI link működik;
- `PROJECTS.md` és `SOURCES.md` frissítve;
- nincs secret.

## Fő források

- GitHub profil: https://github.com/DuczaPeter/
- RSI: https://robertsspaceindustries.com/
- RSI fan-site guidance: https://support.robertsspaceindustries.com/hc/en-us/articles/360006895793-Star-Citizen-Fankit-and-Fandom-FAQ
- Star Citizen Wiki: https://api.star-citizen.wiki/
- UEX: https://uexcorp.space/
- SCMDB: https://scmdb.net/
