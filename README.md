# sales-dashboard

## Projektbeschreibung

Dieses Projekt zeigt ein Sales Dashboard, das Verkaufsdaten analysiert, bereinigt und visualisiert. Ziel ist es, Einblicke in die Verkaufsleitung zu gewinnen, Datenqualität zu verbessern und eine interaktive Übersicht für wichtige Kennzahlen zu erstellen.

Die Daten stammen aus einer generierten CSV-Datei, die bereinigt und anschließend für das Dashboard aufbereitet wurde. Zusätzlich wurden Mockup-Skizzen erstellt, um das Layout und die Visualisierungen des Dashboards zu planen.

## Projektstruktur



## Vorhergehensweise

1. Exploratory Data Analysis (EDA)
   - Daten untersucht, um Struktur und fehlende Werte zu erkennen.
2. Data Cleaning
   - Duplikate entfernt
   - Negative Werte analysiert und entfernt
   - Nullwerte behandelt
3. Feature Engineering
   - Feature "Region" bereinigt (z.B. Schreibfehler: "Weest" -> "West")
   - Neue Spalte "OrderSizeCategory" (in Power BI) erstellt:
       - 1-3 Bestellungen: Small Order
       - 4-6 Bestellungen: Medium Order
       - 7-9 Bestellungen: Large Order
4. Speichern der bereinigten Daten
   - Bereingte CSV-Datei abgespeichert (sales_dataset_cleaned.csv)
5. Dashboard-Erstellung in Power BI
   - Dashboard-Layout anhand Mockups umgesetzt
   - Bereinigte Daten geladen
   - Interaktive Visualisierungen erstellt
  

## Verwendete Technologien
Python, Pandas, Power BI, Jupyter Notebook

## Mockup & Design
- Mockups befinden sich im Ordner [design/](design/)

## Demo


