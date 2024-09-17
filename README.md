# Crime_statistic
Data Wrangling (xlsx; csv)


Dieses Projekt befasst sich mit der Analyse von Kriminalstatistiken in den Schweizer Kantonen im Rahmen eines nationalen Präventionsprogramms. Ziel ist es, die Art und Häufigkeit von Verbrechen in den Kantonen zu untersuchen und die Daten für weiterführende Analysen vorzubereiten.

## Hauptschritte des Projekts:

### Datenaufbereitung:
Ein Excel-Datensatz mit Kriminalstatistiken der letzten Jahre wird eingelesen und bereinigt. Fehlende Werte werden behandelt, irrelevante Spalten entfernt und die Daten aufbereitet, um eine saubere Struktur für die weitere Analyse zu gewährleisten.
Die Verbrechensgruppen werden extrahiert, und unnötige Einträge, wie doppelte oder fehlerhafte Werte, werden bereinigt. Es erfolgt eine Zuordnung der Gruppennamen zu den entsprechenden Straftaten.

### Datenmanipulation und -transformation:
Die Daten werden in ein Long-Format transformiert, um die Verbrechensfallzahlen pro Jahr und Kanton analysieren zu können. Fehlende Informationen in den Kantons- und Verbrechensspalten werden durch verfügbare Werte ausgefüllt.

### Einbindung von Einwohnerzahlen:
Ein zusätzlicher Datensatz mit den Einwohnerzahlen der Schweizer Kantone wird eingelesen, bereinigt und mit den Kriminalstatistiken verknüpft. Dabei wird ein Matching-Table erstellt, um verschiedene Schreibweisen der Kantonsnamen zwischen den Datensätzen abzugleichen.

### Berechnung der relativen Kriminalitätshäufigkeit:
Es wird die Anzahl der Straftaten pro 1000 Einwohner
für jeden Kanton und jedes Jahr berechnet. Dies ermöglicht eine vergleichbare Analyse der Kriminalitätsrate in den verschiedenen Kantonen über die Jahre.

<div style="display: flex; gap: 20px;">
  <img src="https://github.com/user-attachments/assets/30c487bf-4d9f-4147-a4a2-26499bb2489a" alt="image" width="800"/>
  <img src="https://github.com/user-attachments/assets/cf2905c7-cc94-4507-9f6b-700cc4ee6cb5" alt="image" width="800"/>
</div>


### Ergebnis:
Das Projekt liefert aufbereitete und bereinigte Daten zur weiteren Analyse der Kriminalität in Schweizer Kantonen. Es umfasst die Verknüpfung von Einwohnerzahlen und Kriminalstatistiken sowie die Berechnung von Kriminalitätsraten, die für jede Region vergleichbare Einblicke ermöglichen. Die Ergebnisse werden visuell als Zeitreihe dargestellt, um die Entwicklung der Kriminalität pro 1000 Einwohner
über die Jahre zu veranschaulichen.

