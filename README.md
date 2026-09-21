# Werkzeugkasten — Unterrichts-Website (MK)

Statische Website (GitHub Pages), Unterrichtsmaterial für ELT + AT.

## Struktur

```
index.html          Hub mit Bereichskarten
elt/index.html      Bereich Elektrotechnik (NEXUS-Loft, IAH51)
elt/ls-schalter.html   LS-App (CC-BY-Foto, self-contained)
arduino/index.html  Bereich Automatisierungstechnik (Arduino)
```

## Neue Seite einstellen (auch für die Arduino-Session)

1. Self-contained HTML (Bilder base64, kein CDN nötig) in den Bereichsordner legen, z. B. `arduino/ampel.html`
2. Karte auf der Bereichs-`index.html` ergänzen (Muster: `elt/index.html`)
3. `git add -A && git commit && git push` — Pages baut automatisch (~1 Min)

## Regeln (WICHTIG)

- **NIEMALS Eduki-Material** oder anderes fremdes Material ohne freie Lizenz — nur Eigenes, CC-lizenziertes (mit Bildnachweis auf der Seite) oder Gemeinfreies
- Keine Schülernamen, keine Fotos von Personen, keine Schul-Interna
- Kein KI-Vermerk auf Schülermaterial (Regel MK)
- Design-Tokens: Navy `#0F2034`, Cyan `#40A9DE`, Hell `#E3EEF7`, Grau `#595959`
