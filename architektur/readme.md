# AP Architektur

## Inhalt (aus PMP)

Die FE bauen teilweise aufeinander auf. Beispielsweise nutzt der Web GIS Client den WMS. Dieser wiederum nutzt bei Vektordaten die Datenbank.
In diesem AP werden die Schnittstellen definiert, über welche abhängige FE auf "Basis  FE" zugreifen.

## Abgrenzung

In den Diagrammen dieses AP sind lediglich die Laufzeitabhängigkeiten zwischen funktionalen Einheiten abgebildet. Die Abhängigkeiten bezüglich der Verteilung der Konfiguration auf die verschiedenen Komponenten sind im AP Confflow beschrieben. Die Abhängigkeiten der Komponenten innerhalb einer Funktionalen Einheit sind "out of scope".

Folgende FE sind "in scope":
* API-Gateway 
* API: CCC-Anbindung
* API: Dataservice
* API: IAM
* API: Reports
* API: Suche
* API: WFS
* API: WMS
* API: WMTS
* Datenbezug
* simi
* SOLocator
* Web GIS Client


## Bearbeiten

Config-Service
Grundsätze:
* Jeder Komponente werden nur genau die Informationen bereitgestellt, welche von ihr auch verarbeitet werden. Damit ist direkt im Code transparent dokumentiert, welche Informationen von welchen Komponenten benötigt werden.










