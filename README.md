# buildox-szallitasi-dijak

Buildox nyilvános szállítási díjnézet – automatikusan ellenőrzött adatok.

**Élő oldal:** https://vaszabi96.github.io/buildox-szallitasi-dijak/ (értékesítői gyorsnézet, bejelentkezés nélkül)

## ⚠️ Ez PUBLIKUS repó

Minden, ami ide kerül, bárki számára látható – a git-előzményekben is, törlés után is.

**Ide soha nem kerülhet:**

- beszerzési ár, árrés, nettó/akciós belső ár, beszállítói kondíció;
- vevő- vagy ügyféladat, egyedi kedvezmény, belső megjegyzés;
- API-kulcs, token, jelszó, deploy key, NAS- vagy belső hálózati elérés;
- nyers UNAS-/Vectory-export, teljes konfiguráció, beszállítói nyers paraméter.

Csak olyan adat lehet itt, amely a buildox.hu webshopban is nyilvánosan látszik (termék, cikkszám, kategória, szállítási díj és terület).

Ha az értékesítői nézetbe belső adat kellene, az **nem ebbe a repóba** kerül: előbb privát repó és jelszóval védett kiszolgálás szükséges.

## Működés

- A tartalmat (`index.html`, `status.json`, `.nojekyll`) a privát `unas-webshop-program` szinkronja publikálja automatikusan, csak teljesen ellenőrzött állapotból.
- Ezeket a fájlokat **kézzel ne szerkeszd** – a következő futás felülírja. Díjszabály- vagy sablonmódosítás a programrepóban történik.
- A GitHub Pages a `main` ág gyökerét szolgálja ki.
