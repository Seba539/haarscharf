# Regeln für die Website von Friseur Haarscharf

Diese Datei gilt für alle, die an der Seite arbeiten, auch für KI-Assistenten (Claude, ChatGPT, Copilot …). Bitte vor jeder Änderung lesen.

Inhaber: Sebastiano Parisi. Mitarbeit: seine Schwester und ihre KI, außerdem Sebastianos Claude.

## Wichtig: Was hier gespeichert wird, ist sofort online
Jede Änderung im Zweig `main` erscheint nach 1–2 Minuten auf https://haarscharf-solingen.de. Es gibt keine Vorschau. Also vorher prüfen, ob die Seite am Handy und am Computer richtig aussieht.

## Nie löschen oder umbenennen
- `CNAME`: hält die Adresse haarscharf-solingen.de.
- `robots.txt` und `sitemap.xml`: damit Google die Seite findet.
- `.nojekyll`: sorgt dafür, dass GitHub die Seite unverändert ausliefert.
- In `index.html` die Zeile `<meta name="google-site-verification" …>` im Kopf: ohne sie geht der Zugang zur Google Search Console verloren.

## Inhalte
- **Preise, Leistungen und Bewertungen** nur ändern, wenn Sebastiano es freigegeben hat.
- **Terminanfrage und Preisliste:** Die Beschreibungen in der Terminanfrage lauten immer genau so wie in der Preisliste. Wer das eine ändert, ändert das andere mit.
- **Bewertungen:** nur echte Google-Bewertungen, wörtlich (Kürzungen mit „…“), nur mit Erlaubnis. Keine Bewertungen, die Elena oder Fado nennen.
- **Nichts Privates:** Diese Seite und alle Dateien hier sind öffentlich. Keine privaten Adressen, Telefonnummern, Kontodaten, Passwörter oder Zugangsschlüssel ablegen.
- **Impressum und Datenschutz** nicht entfernen. Sie stehen seit 18.11.2026 als eigene Seiten in `impressum.html` und `datenschutz.html` und sind unten auf der Startseite verlinkt. Bei neuen Einbindungen (Karten, Videos, Schriften von fremden Servern, Formulare, Tracking) zuerst klären, ob Cookie-Hinweis oder Datenschutzerklärung angepasst werden müssen.
- Gestaltung: schwarz und gold, wie bisher. Größere Umbauten erst als Vorschlag zeigen, nicht direkt online stellen.

## Zusammenarbeiten
- Vor jeder Änderung den neuesten Stand holen (`git pull`), damit niemand die Arbeit der anderen überschreibt.
- Kleine Schritte mit kurzer deutscher Beschreibung speichern, z. B. „Preis Damen-Haarschnitt kurz angepasst“.
- Bilder vor dem Hochladen verkleinern (Breite höchstens etwa 1600 Pixel), damit die Seite am Handy schnell lädt.
