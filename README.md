# SQLite in de browser

Een webpagina waarop je SQL-commando's (CREATE TABLE, INSERT, SELECT, UPDATE, DELETE, …) uitvoert op een SQLite-database die volledig in de browser draait via [sql.js](https://github.com/sql-js/sql.js) (WebAssembly). Het resultaat verschijnt onderaan in een tabel.

## Functies

- SQL uitvoeren (knop of Ctrl/Cmd + Enter), meerdere commando's na elkaar, met resultaat per commando
- Lijst met tabellen; klik om de eerste 100 rijen te zien
- Historiek van uitgevoerde SQL (bewaard in de browser); klik om een commando terug in het invoerveld te zetten, aan te passen en opnieuw uit te voeren
- Database bewaren in de browser (IndexedDB), automatisch of met de knop
- Nieuwe lege database starten
- Bestaande `.sqlite`-database openen en de huidige database als `.sqlite` downloaden
- `.sql`-bestand importeren en uitvoeren, of de database exporteren als `.sql`
- Alle acties in één dropdownmenu, met een donker/licht-schakelaar

## Gebruik

Open `index.html` in een browser of zet het bestand op een webserver. Een internetverbinding is nodig om jQuery en sql.js via een CDN te laden.
