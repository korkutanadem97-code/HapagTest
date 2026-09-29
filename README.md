# Hapag-Lloyd Chat Channel Strategy Workshop Board

Interaktives Workshop-Board für den Hapag-Lloyd „Chat Channel Strategy“-Workshop. Die gesamte Anwendung besteht aus einer einzigen, eigenständigen HTML-Datei (`Hapag-Lloyd_Workshop_Board.html`). Sie braucht weder Build-Schritt noch Server.

## Verwendung

Die Datei im Browser öffnen, zum Beispiel per Doppelklick oder mit `open Hapag-Lloyd_Workshop_Board.html`. Die Navigation im Header oder die Timeline wechselt zwischen den Workshop-Abschnitten. Die Schriften (DM Sans, Space Mono) werden von Google Fonts geladen, dafür ist eine Internetverbindung nötig. Ohne Verbindung greift ein Fallback.

## Agenda

| Zeit     | Format      | Dauer  | Abschnitt                                   |
|----------|-------------|--------|---------------------------------------------|
| 1:00 PM  | Plenary     | 15 min | Welcome & Kickoff                           |
| 1:15 PM  | Interactive | 30 min | Release Iteration & CARE Framework          |
| 1:45 PM  | Interactive | 25 min | Demand Categorization & Process             |
| 2:25 PM  | Workshop    | 30 min | Dual-Product Orchestration                  |
| 2:55 PM  | Plenary     | 25 min | Country Rollout Standards                   |
| 3:20 PM  | Workshop    | 20 min | Use Case Evaluation Scorecard               |
| 3:40 PM  | Plenary     | 25 min | Governance Model                            |
| 4:05 PM  | Workshop    | 10 min | Operational Checklists                      |
| 4:15 PM  | Plenary     | 15 min | Wrap-Up & Next Steps                        |

## Struktur

- `Hapag-Lloyd_Workshop_Board.html`: Board mit HTML, CSS und JavaScript in einer Datei
- `README.md`: diese Datei

## Anpassen

Farben und Schatten stehen als CSS-Variablen (`--hl-*`) im `:root`-Block am Anfang der Datei. Jeder Workshop-Abschnitt ist ein `<div class="section" id="sN">`. Der zugehörige Link im Header trägt `data-s="N"`.
