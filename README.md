# CreativeCharts

CreativeCharts ist ein leistungsstarkes Visualisierungssystem, das speziell für Entwickler und Datenanalysten entwickelt
wurde. Mit CreativeCharts können Sie Daten in verschiedenen Diagrammtypen visualisieren und speichern. Das System
besteht aus drei Hauptkomponenten: ApiGateway, ChartService und Frontend.

## Funktionalität

- **ApiGateway**: Das ApiGateway ist die zentrale Schnittstelle zwischen dem Frontend und den verschiedenen Services. Es
  routet Anfragen an die entsprechenden Services und gewährleistet eine effiziente Datenübertragung.

- **ChartService**: Der ChartService ist ein Microservice, der für die Verwaltung der Diagrammdaten verantwortlich ist.
  Er bietet Funktionen zur Erstellung, Bearbeitung und Löschung von Diagrammen und verwendet eine MongoDB-Datenbank.

- **Frontend**: Das Frontend bietet eine benutzerfreundliche Oberfläche für die Visualisierung und Interaktion mit
  Diagrammdaten. Es unterstützt verschiedene Diagrammtypen und verwendet React, Material-UI und die X-Charts-Bibliothek
  von MUI.

## Schnellstart

**ApiGateway**: Um das ApiGateway zu starten, führen Sie den folgenden Befehl aus:

```bash
dotnet run Program.cs
```

**ChartService**: Um den ChartService zu starten, führen Sie die folgenden Schritte aus:

1. Kopieren Sie die `.env.example`-Datei und passen Sie die MongoDB-Verbindungszeichenfolgen in der `.env`-Datei an.

2. Führen Sie dann den Befehl aus:

```bash
cd ChartService/src
node server.js
```

**Frontend**: Um das Frontend im Entwicklungsmodus zu starten, verwenden Sie den folgenden Befehl:

```bash
cd Frontend/frontend
npm install
npm run dev
```

## Weitere Informationen

Informationen zur Konfiguration und zur Verwendung finden Sie in den jeweiligen Readme-Dateien der Komponenten.

Entwickeln Sie mit CreativeCharts leistungsstarke datenbasierte Anwendungen und erleichtern Sie die Datenvisualisierung.

Viel Spaß mit CreativeCharts!

