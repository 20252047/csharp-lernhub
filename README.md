# C# Lernhub — POS1

Mobile-first Lernhub für C#-Strings, Collections, Exceptions und Übungsaufgaben.

## Struktur

| Datei | Zweck |
|---|---|
| `index.html` | Schlankes HTML-Grundgerüst ohne eingebettete Massendaten |
| `style.css` | Mobile-first Styling, Bottom-Navigation, responsive Desktop-Layout |
| `script.js` | Simulatorlogik, Übungen, dynamische Referenzdarstellung |
| `data.json` | Simulator-Strukturen und Übungsaufgaben |
| `references.json` | Ausgelagerte Referenzinhalte |

## Lokal starten

Wegen `fetch()` sollten die Dateien über einen lokalen Server geöffnet werden, nicht direkt per Doppelklick.

```bash
python -m http.server 8000
```

Danach im Browser öffnen:

```text
http://localhost:8000
```

## Mobile-first-Konzept

- Primäre Navigation unten am Smartphone.
- Panels im Simulator sind mobil einklappbar.
- Eingabefelder haben mindestens 44 px Touch-Zielhöhe.
- Inputs verwenden 16 px Schriftgröße, damit iOS beim Fokus nicht hineinzoomt.
- Referenznavigation wird mobil horizontal scrollbar und bleibt oben sticky.
- Desktop-Layout wird erst ab 768 px als Drei-Spalten-Layout aktiviert.
