# AI Buddy

**Asztali IT-s társ Windowsra** — egy kis lebegő figura a képernyő sarkában, aki a szemével követi az egeret,
buborékban beszél, figyeli az időjárást, és jobb klikkre előveszi a „svájci bicskáját”.

## Mit tud

- **Öt figura** (Robot, Ovi, Egérke, Orb és a koreai, Kakao-matricás hangulatú **Abroncs**), 11 színtéma, három méret.
- **Magától is elfoglalja magát:** sétál, telefonozik, laptopozik, kávézik, tornázik, szelfizik, este megágyaz és alszik —
  véletlen hosszú, aranyos jelenetekben. Megfogható, elhajítható, a képernyő szélén visszapattan.
- **IT-tippek** (több mint 100: Windows, parancssor, PowerShell, hálózat, biztonság) — a parancs kattintásra a vágólapra kerül.
- **Időjárás-figyelés** (Open-Meteo): animált jel a feje mellett, és szól, ha esni fog, zivatar vagy erős szél jön.
- **Svájci bicska:** hálózati adatok, ping, port- és DNS-próba, gépinformáció, jelszógenerátor, alhálózat-számoló,
  ellenőrzőösszeg (SHA-256), Windows-eszközök egy kattintással.
- **Kijelző mód** gyári / irodai tévére: 0–24 órában ébren marad, és a három műszakhoz (6–14, 14–22, 22–6) illő,
  motiváló mondatokat mond, műszakváltáskor köszön.
- **Önfrissítés:** naponta megnézi, van-e új verzió, és egy kattintással (vagy a tévén magától) frissíti magát.

## Letöltés

A legfrissebb **`AiBuddy.exe`** a [Releases](../../releases/latest) oldalon. Egyetlen fájl, telepítés nélkül fut
(Windows 10 / 11, 64 bites). Olyan mappába tedd, ahová írni tudsz (pl. Dokumentumok) — különben nem tudja frissíteni magát.

Kilépés: jobb klikk a figurára → Kilépés.

## Biztonság

- A frissítést csak akkor telepíti, ha a kiadás leírója (`AiBuddy-frissites.txt`) a kiadó titkos kulcsával van aláírva,
  és a letöltött exe mérete és SHA-256-ja egyezik vele. Így más exe nem juthat a gépre a frissítésen keresztül.
- Internetet csak az időjáráshoz (Open-Meteo), a frissítéskereséshez (GitHub) és — gombnyomásra — a nyilvános IP
  lekérdezéséhez használ. Magáról semmilyen adatot nem küld.
- Az exe nincs kódaláíró tanúsítvánnyal aláírva, ezért az első indításkor a Windows SmartScreen figyelmeztethet
  („További információ” → „Futtatás mindenképp”).

---

Saját fejlesztés, magyar nyelvű. A forráskód nincs nyilvánosan fent; ez a tároló a kiadásokat (Releases) hordozza.
