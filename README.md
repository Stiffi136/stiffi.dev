# stiffi.dev

Persönliches Portfolio mit Entwicklungsprojekten. Die Seite besteht aus statischem HTML und benötigt keinen Build-Schritt.
## Projekte pflegen

Alle Projekte stehen in `projects.json`. Ein neuer Eintrag erzeugt automatisch eine neue Karte. Felder: `id`, `category`, `title`, `description`, `tags`, `image`, `imageAlt`, `github`, `play`. Screenshots liegen in `assets/`.

## Lokal ansehen

`index.html` lädt `projects.json` per `fetch`. Ein Doppelklick auf die Datei funktioniert deshalb nicht. Starte einen lokalen Server im Ordner, zum Beispiel `npx serve .` oder die VS-Code-Erweiterung „Live Server“.
