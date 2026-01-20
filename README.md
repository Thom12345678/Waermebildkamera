# Wärmebildkamera – 6-Minuten-Präsentation (.pptx generieren)

So erzeugst du die PowerPoint:

## Schnellstart
```bash
# 1) (optional) Neues virtuelles Environment
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate

# 2) Abhängigkeiten installieren
pip install -r requirements.txt

# 3) Präsentation erzeugen (Standard-Template von PowerPoint)
python generate_waermebild_presentation.py

# Optional: Mit Corporate-Template (.potx) + Autor + Datum
python generate_waermebild_presentation.py --template /pfad/zu/deinem_template.potx --author "Thom12345678" --date "20.01.2026" --output presentations/Waermebildkamera_6min_Praesentation.pptx
```

Die erzeugte Datei: `presentations/Waermebildkamera_6min_Praesentation.pptx`

## Inhalte
- 10 Folien, ca. 6 Minuten
- Deutsche Stichpunkte und Sprechernotizen
- Platzhalter für Bilder (optional einfügen)
- Kompatibel mit Standard-Layouts oder deinem .potx

## Tipp
- Füge nachträglich passende Wärmebilder ein (Gebäude, Schaltschrank, Feuerwehr, Wildtier).
- Wenn dein Corporate-Design spezielle Layouts hat, nutze `--template` und passe bei Bedarf die Layout-Indizes im Skript an.
