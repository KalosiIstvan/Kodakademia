# KódAkadémia – önálló, ingyenesen használható tanulóweboldal

Ez a verzió **nem igényel Lovable-fiókot, API-kulcsot, előfizetést, Node.js-t vagy szervert**.

## Indítás
1. Csomagold ki a ZIP-fájlt.
2. Nyisd meg az `index.html` fájlt Chrome, Firefox vagy Edge böngészőben.
3. Válassz kurzust, majd leckét. Jelöld a leckét teljesítettnek a végén.

A projekt 13 tananyagban 78 leckét tartalmaz: alapok, HTML, CSS, JavaScript, TypeScript, JSX, React, Python, PHP, C#, C# konzolos alkalmazások, WPF és etikus hackelés / védekezés. Lua nincs benne.

## Fájlok
- `index.html`: az oldal váza
- `styles.css`: reszponzív, sötét téma
- `app.js`: teljes UI, keresés, navigáció, kvízek, könyvjelzők, haladás és játszótér
- `data.js`: a böngésző által használt teljes tananyag
- `courses.json`: a tananyag szerkeszthető, gépi feldolgozásra alkalmas formában

A `build_data.py` a tananyagot az általa tartalmazott szerzői adatokból újragenerálja; ehhez Python szükséges, de **a weboldal használatához nem**.

## Haladásmentés
A böngésző localStorage tárhelyére mentődik. Az oldal fejlécében a **Haladás export** lehetőséggel készíthetsz JSON biztonsági másolatot. A localStorage böngésző- és webcím-specifikus, inkognitó módban törlődhet. A mentés importálása későbbi fejlesztési lehetőség.

## Kódjátszótér
HTML, CSS és JavaScript böngészőben futtatható példákhoz elkülönített iframe. Más nyelvek (C#, WPF, PHP, Python) valódi futtatásához saját gépeden telepíteni kell a megfelelő fejlesztői környezetet. Etikus hackelés csak saját vagy engedélyezett laborban.

## Fontos megjegyzés
Ez egy **új, önállóan futó változat**, amelyet a korábbi Lovable-projekt állapotának és céljának ismeretében készítettünk, **nem a Lovable 90 fájljának byte-pontos átvétele**. A már meglévő oktatási témákat átdolgozott, bővített anyagok fedik le; a meglévő Lovable-projekt módosításához annak saját környezetében történő folytatás vagy export/szinkronizáció szükséges.

A leckék oktatási kiindulópontok: egy teljes szakmai terület tudása ennél több gyakorlást és további tananyagot igényel.
