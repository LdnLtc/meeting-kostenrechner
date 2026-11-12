# Meeting-Kostenrechner

Was kostet dieses Meeting? Diese kleine Webseite rechnet es live in **CHF** aus.

Alles steckt in einer einzigen Datei (`index.html`): HTML, CSS und JavaScript.
Es braucht keine Datenbank, keinen Server und keine Installation.

## Online öffnen

👉 **https://ldnltc.github.io/meeting-kostenrechner/**

(Der Link funktioniert, sobald GitHub Pages aktiviert ist – siehe unten.)

## Funktionen

- **Teilnehmende in Gruppen erfassen**, z.B. 3 × Entwickler à 90 CHF und 1 × Manager à 130 CHF
- **Geplante Dauer** eingeben → zeigt die erwarteten Kosten
- **Start / Pause / Zurücksetzen** mit Live-Zähler in grosser Schrift
- Anzeige von **Kosten total**, **Kosten pro Minute** und **verstrichener Zeit**
- Fortschrittsbalken; wird die geplante Zeit überschritten, färbt sich die Anzeige orange
- **Sprüche bei Schwellen**, z.B. ab 500 CHF: «Das hätte auch eine Mail sein können.»
- **Beamer-Modus** (Vollbild, nur der Zähler)
- Hell/Dunkel-Umschalter, funktioniert auf Handy, Laptop und Beamer
- Einstellungen bleiben im Browser gespeichert

### Tastenkürzel

| Taste      | Aktion             |
|------------|--------------------|
| Leertaste  | Start / Pause      |
| R          | Zurücksetzen       |
| B          | Beamer-Modus       |
| Esc        | Beamer-Modus beenden |

## Lokal öffnen (ohne Internet)

1. Oben auf dieser Seite auf den grünen Knopf **Code** klicken → **Download ZIP**.
2. ZIP-Datei entpacken (Doppelklick).
3. `index.html` doppelklicken – die Seite öffnet sich im Browser.

## GitHub Pages aktivieren (einmalig)

Damit die Seite unter dem Link oben erreichbar ist:

1. Im Repository auf **Settings** (Zahnrad oben) klicken.
2. Links im Menü **Pages** wählen.
3. Bei **Source** «Deploy from a branch» wählen, bei **Branch** `main` und `/ (root)`, dann **Save**.
4. Nach 1–2 Minuten ist die Seite unter `https://ldnltc.github.io/meeting-kostenrechner/` online.

## Etwas ändern

Am einfachsten direkt auf GitHub: `index.html` anklicken → Stift-Symbol (✏️ «Edit») →
ändern → unten **Commit changes**. Die Online-Version aktualisiert sich nach etwa einer Minute.

Die Sprüche findest du in `index.html` unter `const THRESHOLDS`, die vorbelegten Gruppen unter `const DEFAULT_CFG`.
