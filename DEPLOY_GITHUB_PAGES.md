# GitHub Pages telepítés

## Nagyon fontos

A ZIP fájlt **ne úgy töltsd fel a repositoryba, hogy bent marad ZIP-ként**, mert a GitHub Pages nem bontja ki és nem fogja abból futtatni az oldalt.

A ZIP egy szállítási csomag.

## Feltöltés GitHub webes felületről

1. Töltsd le a ZIP-et.
2. Bontsd ki a saját gépeden.
3. Nyisd meg:
   https://github.com/DuczaPeter/DuczaPeter.github.io
4. Válaszd az **Add file → Upload files** lehetőséget.
5. A kicsomagolt csomag **teljes tartalmát** húzd a feltöltőmezőre.
6. Az `index.html` közvetlenül a repository gyökerében legyen.
7. Commit message például:
   `Publish sPg Star Citizen Tools landing page`
8. Commitold a `main` branchre.

## GitHub Pages

A `DuczaPeter.github.io` nevű user-site repository esetén a GitHub Pages tipikusan a `main` branch gyökeréből szolgálja ki a weboldalt.

Ellenőrizd:
Repository → Settings → Pages

Ha szükséges:
- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

## Várt cím

https://duczapeter.github.io/

## Gyors ellenőrzés feltöltés után

- megnyílik a főoldal;
- látszanak a projektkártyák;
- működik a kereső;
- működnek a kategóriák;
- a Weboldal és GitHub gombok kattinthatók;
- alul látszik a nem hivatalos fan-site notice és az RSI link.
