# Brochure Assist 0.2

## GitHub Pages
Repository öffnen → Add file → Upload files → `index.html` ersetzen → Commit changes. Pages bleibt auf `main` und `/(root)`.

## Neu in 0.2
- 36 Layouts einschließlich freier Gestaltung
- Schriftarten und Schriftfarben pro Seite
- Felder tauschen (Bilder untereinander oder Texte untereinander)
- Freie Text- und Bildfelder ziehen und skalieren
- PDF-Seiten per Klick oder Drag & Drop als Zeichnung einfügen
- Projekte als JSON speichern und wieder öffnen

## Grenzen
PDF-Seiten werden aktuell für die Platzierung als hochauflösendes PNG gerendert (PDF.js über CDN, Internetverbindung nötig). Der Export erfolgt über Browser-Drucken und ist kein PDF/X-Vektorexport. Ein echtes PDF-Vektor-Passthrough, professioneller Anschnitt/Bundkorrektur und zuverlässige Druckvorstufe sind weitere Ausbaustufen. Das Panorama wird derzeit in zwei Hälften geteilt; abhängig vom Bildformat kann es noch zu sichtbaren Abständen kommen.
