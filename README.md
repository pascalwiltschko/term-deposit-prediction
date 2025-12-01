# Vorhersage der Kundenakquisition für Festgelder

## Über das Projekt

Diese Analyse untersucht einen Datensatz mit Informationen über Marketingkampagnen einer Bank. Ziel ist die Entwicklung eines Modells zur Vorhersage, ob ein Kunde ein Festgeldkonto abschließen wird oder nicht.

Die Analyse umfasst folgende Schritte:

1. **Datenverständnis**: Analyse der Struktur und des Inhalts des Datensatzes für ein Verständnis der verfügbaren Merkmale und sinnvoller Evaluierungs-Metriken.
2. **Datenaufbereitung**: Vorbereitung der Daten für die Modellierung durch Aufteilung für Training und Evaluation sowie entsprechende Transformationen.
3. **Modellierung**: Training eines Benchmark-Modells und Vergleich mit einem Random Forest Modell für einen ersten Eindruck der Vorhersageleistung und Wichtigkeit der Merkmale.
4. **Evaluierung**: Bewertung der Modelle anhand geeigneter Metriken zur Beurteilung der Prognoseleistung.
5. **Fazit**: Zusammenfassung der Ergebnisse und Empfehlungen für weitere Schritte zur Verbesserung der Vorhersagegenauigkeit.

## Installation

Für das Dependency Management wird `uv` verwendet. Die Python-Umgebung kann mit folgendem Befehl eingerichtet werden:

```bash
uv sync
```

Alternativ können die benötigten Pakete auch mit der *requirements.txt*-Datei installiert werden:

```bash
pip install -r requirements.txt
```

## Daten

Die Daten müssen separat heruntergeladen werden:

1. Download möglich auf dieser [Webseite](https://archive.ics.uci.edu/dataset/222/bank+marketing).
2. Extraktion der Datei *bank-additional-full.csv*.
3. Ablage der Datei im Ordner *data*.

## Ausführung

Die Analyse kann durch Ausführen des Jupyter Notebooks `term_deposit_prediction.ipynb`. gestartet werden.
