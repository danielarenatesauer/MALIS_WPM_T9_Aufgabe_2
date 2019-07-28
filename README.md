# MALIS_WPM_T9_Aufgabe_2

Die vorliegende Aufgabe fokussiert auf einem Lösungsvorschlag für eines der bereits in Aufgabe MALIS_WPM_T9_Aufgabe_1 angesprochenen Probleme. Der Prozess des Imports von bibliographischen Daten zu Zeitschriftenartikeln, die in unterschiedlichen Datenformaten als OpenAccess Publikationen vorliegen, in den Bibliothekskatalog, soll erleichtert werden. Dabei werden folgenden zwei Fälle unterschieden:

1) Daten können als Zitationen im txt oder csv Format heruntergeladen werden, z.B. Zeischrift "Heritage" 
2) Links zu einzelnen Nummern einer Zeitschrift werden durch webscraping von einer Webseite abgeschöpft, z.B Zeischrift Conserva

In beiden Fällen müssen die Daten gereinigt werden, das heisst alle überflüssigen Informationen entfernt und die verbleibenden Daten nach einem vorher festgelegten fixen Schema strukturiert werden. Danach können sie als Excelfiles mit dem tool MarcEdit in den Katalog überführt werden.

Lösungsansätze:

## 1. Beispiel: Zeitschrift Heritage

Es ist gelungen, eine mit einem Bibliographic Reference Management Programm heruntergeladene und anschliessend im GitHub Repositorium lokal gespeicherte csv Datei mit Pandas Dataframe zu bearbeiten und somit eine bereinigte Datenstruktur zu erhalten.

Anmerkung: Dieser Prozess mag für den vorliegenden Fall nicht unbedingt notwendig sein, da man ein ähnliches Resultat ohne viel Aufwand auch auf anderen Wegen, d.h. ohne oben genannte Prozesse durlaufen zu müssen, hätte erreichen können. Im komplexeren Fällen, bei langen Dateien mit vielen Daten könnte es aber durchaus nützlich sein, in ähnlicher Weise vorzugehen.

## 2. Beispiel: Zeitschrift Conserva

Mit Hilfe des Imports einer Python libray mit der ein Webscraping, das heisst Daten aus einer Webseite strukturiert dargestellt   und nach bestimmten Kriterien gefiltert werden können, werden von der Webseite der Zeitschrift Conserva einer Liste von allen links zu bisher erschienenen Nummern gefiltert.

Anmerkung: es muss jetzt nach einer Möglichkeit gesucht werden automatisch alle links in einzelnen Seiten zu öffnen um wichtige bibliografische Informationen ( Autor, Titel, Seitenzahl) abschöpfen zu können. 

# Fazit

Es sind zwar Ansätze gefunden worden, die in einigen Fällen möglicherweise von Nutzen sein könnten, es müssen aber in beiden Fällen noch Verbesserungen eingebaut werden.
