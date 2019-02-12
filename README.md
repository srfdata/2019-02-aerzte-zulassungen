# 2019-02-aerzte-zulassungen

## Analyse der Anwendung von Disziplinarmassnahmen (DM)

Das MedBG listet 7 veschiedene Disziplinarmassnahmen zum Bestrafen von Medizinalpersonen auf. Daten zu deren Gebrauch wurden SRF Data vom BAG zur Verfügung gestellt und reichen bis ins Jahr 2013 zurück. Die Daten werden auch ins Verhältnis gesetzt mit der Anzahl an aktiven Berufsausübungsbewilligungen (BAB) pro Kanton, um die Vergleichbarkeit zu erhöhen. Auch die Daten zu den aktiven BAB stammen vom BAG, deshalb basiert die gesamte Analyse der DM nur aus Daten des BAG und nicht aus Daten aus dem Scraping (wie unten). 

Der Code zur DM-Anwendung erzeugt verschiedene Plots und befindet sich in der Datei `analysis/main.Rmd`. 
Die oben erwähnten Daten befinden sich im Verzeichnis `analysis/input/disciplinary_measures`.

*Anmerkung zur Normalisierung: Beim Plot, der die kantonalen Anwendungsanzahlen der DM mit der Anzahl aktiver Lizenzen ins Verhältnis setzt, ist zu beachten: Bei den Disziplinarmassnahmen werden keine Menschen, sondern Massnahmen dargestellt. Die Anzahl aktiver Lizenzen bezieht sich jedoch auf Medizinalpersonen, die in diesem Kanton eine aktive Lizenz haben. Eine Person kann theoretisch auch mit mehreren Massnahmen belegt werden. Dies führt zu einer kleinen Ungenauigkeit. Auch bezieht sich die Anzahl der aktiven Lizenzen auf den 31.12.2016, diese Zahl wird für die alle DM-Anwendungsjahre seit 2013 verwendet. Auch hier kommt es deshalb zu einer kleinen Ungenauigkeit.*

### Vorprozessierung und Analyse

Der Ordner `analysis` beinhaltet die Prozessierungsschritte (inkl. explorativer Analyse) in R. Der ganze Prozess steht ebenfalls [unter diesem Link](http://srfdata.github.io/2019-02-aerzte-zulassungen/) als HTML-File zur Verfügung. 

## Haftungsausschluss

Die veröffentlichten Informationen sind sorgfältig zusammengestellt, erheben aber keinen Anspruch auf Aktualität, Vollständigkeit oder Richtigkeit. Es wird keine Haftung übernommen für Schäden, die  durch die Verwendung dieses Scripts oder der daraus gezogenen Informationen entstehen. Dies gilt ebenfalls für Inhalte Dritter, die über dieses Angebot zugänglich sind. 

## Lizenz

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">2019-02-aerzte-zulassungen</span> von <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/srfdata/2019-02-aerzte-zulassungen" property="cc:attributionName" rel="cc:attributionURL">SRF Data</a> ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz</a>.

## Kontakt

Bei Fragen wenden Sie sich bitte an julian.schmidli(at)srf.ch oder an [@srfdata](https://twitter.com/srfdata)
