# Wolfram Eberius

![Wolfram Eberius](https://avatars2.githubusercontent.com/u/3819073?v=3&s=200 "Wolfram Eberius") | 

- software developer
- scrum master
- focus on opendata
- passionate about digital topics
- working out loud
- [OK Lab Köln](https://codefor.de/koeln/)
- [D64 Zentrum für digitalen Fortschritt](https://d-64.org/)

# Links

- [twitter](https://twitter.com/eberius)
- [github](https://github.com/weberius)
- [Xing](https://www.xing.com/profile/Wolfram_Eberius)
- [Facebook](https://www.facebook.com/wolfram.eberius)
- [Flickr](https://www.flickr.com/photos/eberius/)

# Open Source/ Open Data Projekte

## wikidataGeoService (02.2019 - ZZ.2019)

Das Projekt [wikidataGeoService](https://github.com/weberius/wikidataGeoService) habe ich im Rahmen des [wikidata-workshop](https://de.wikipedia.org/wiki/Wikipedia:Wikidata-Workshop-Ulm-2019) im [verschwörhaus](https://verschwoerhaus.de/) begonnen. Ziel ist es auf räumliche Daten in wikidata per Service zuzugreifen. Dabei wird die Abfrage gegen wikidata per Apache Jena gekapselt. Um die Daten ohne weiteres z.B. per leaflet anzeigen zu können, werden die Ergebnisse auf Wunsch per GeoJson ausgeliefert.

## publicTransportElevator (01.2019 - ZZ.2019)

Das Projekt [publicTransportElevator](https://github.com/weberius/publicTransportElevator) bietet den Zugriff auf die Aufzüge und die Störungen der Aufzüge im Bereich der KVB. Die Daten basieren auf den Datensätzen Fahrtreppen KVB Köln der Offenen Daten der Stadt Köln. Die Daten werden als json-Daten verwendet und in einer H2Gis persistiert. Die Applikation bietet Schnittstellen zur Abfrage der Daten und eine einfache Weboberfläche zur Anzeige im räumlichen Kontext. Diese Applikation verarbeitet nicht die Daten der Haltestellen in Köln.

## wahlbeteiligung (06.2017 - 09.2017)

Das Projekt [wahlbeteiligung](https://github.com/weberius/wahlbeteiligung) soll unterschiedliche Wahlbeteiligung in unterschiedlichen geographischen Strukturen veranschaulichen. Es fokussiert sich zunächst auf die Wahlergebnisse im Bereich der Stadt Köln zu den Landtagswahlen.

## PublicDepartCologne (03.2017 - 05.2017)

Das Projekt [PublicDepartCologne](https://github.com/codeforcologne/PublicDepartCologne) soll es Nutzern des öffentliche Personen Nahverkehrs in Köln aufgrund ihres Aufenthaltortes und anhand von Echtzeitdaten zu Abfahrtszeiten ermöglichen, abzuschätzen, ob sie eine z.B. eine Strassenbahn noch zu Fuss erreichen können. Dadurch wird es möglich, z.B. Umwege für Besorgungen oder zur Zerstreuung zu planen, ohne die Bahn/ den Bus zu verpassen.

## isochrone (05.2017)

Das Projekt [isochrone](https://github.com/weberius/isochrone) erlaubt es, isochrone in einer Datenbank zu speichern. Es können keine Isochronen erzeugt werden. Es wird vorausgesetzt, dass die einzulesenden Isochronen im geojson Format vorliegen. Zum Einlesen der Isochronen werden die export-Ergebnisse von openrouteserivce verwendet. Der Service soll verschiedene Clients unterstützen. Die Trennung schnittstellen-seitig erfolgt durch einen entsprechenden Pfad.

## baumkataster (03.2017)

Das Projekt [baumkataster](https://github.com/weberius/baumkataster) soll es ermöglichen, auf die Daten des Baumkataster Koeln zuzugreifen. Die Daten werden von den Offenen Daten Köln zur Verfügung gestellt. Die Daten sind in eine Datenbank übernommen worden. Auf diese Weise ist es möglich per API auf den Datenbestand zu zugreifen.

## wahlergebnis (09.2016)

Das Projekt [wahlergebnis](https://github.com/weberius/wahlergebnis) bietet die Möglichkeit, Ergebnisse von Wahlen zu persistieren, um per REST-Schnittstelle gezielt auf Informationen zugreifen zu können. Grundlage sind offene Daten.

## wahlgebiet (09.2016)

Das Projekt [wahlgebiet](https://github.com/codeforcologne/wahlgebiet) bietet die Möglichkeit, Informationen zu geographische Strukturen, wie Stimmbezirke, Wahllokale und Wahlkreise zur Verfügung per REST-Schnittstelle zugänglich zu machen. Grundlage sind offener Daten.

## kvbrad (01.2016 - 08.2016) 

Die Webapplikation [kvbrad](https://github.com/codeforcologne/kvbrad) soll die Benutzung von Wegen in Köln auf Basis der Standorte Fahrradverleih Koeln - KVB-Rad mit dem Fahrrad verdeutlichen. Hierzu werden die Standorte der KVB-Fahrräder periodisch gespeichert und die Wege zwischen zwei gespeicherten Standorten über Graphhopper auf Basis der OSM Daten geroutet. Die Ergebnisse des Routings werden in Teilabschnitte aufgetrennt. Durch Zählen dieser Teilabschnitte läßt sich die Nutzungsintensität von bestimmten Wegen für die Fahrräder bestimmen. 

## denkmalinkoeln (09.2015 - 12.2015)

Das projekt [denkmalinkoeln](https://github.com/denkmalinkoeln/denkmalinkoeln.github.io) zeigt auf Basis der Denkmalliste Stadt Koeln die Baudenkmäler der Stadt Köln auf der Karte von Köln an. Diese werden durch das Offene Daten Portal der Stadt Köln zur Verfügung gestellt. Die Webapplikation [denkmalinkoeln.github.io](https://denkmalinkoeln.github.io/) bietet einen locationbased Zugang zu diese Informationen.

## schuleninkoeln (12.2014 - 01.2015)

Ziel des Projektes [schuleninkoeln](https://github.com/schuleninkoeln/schuleninkoeln.github.io) ist es Schulen und Schüler bezogen auf Stadtteile in Köln anzuzeigen. Die Webapplikation [schuleninkoeln.github.io](https://schuleninkoeln.github.io/) zeigt farblich durch die Anzahl der Schüler unterschiedenen Stadtteile. Ausserdem kann wird die Anzahl der Schüler im Stadtteil angezeigt werden. 

