# Beschreibung
Der Logikbaustein ruft über die API von Divera in Verbindung mit dem API Key aktuelle Einsatzdaten ab. Jedes mal wenn der Baustein am Eingang „E1 Trigger“ einen Wert ungleich 0 bekommt startet die Abfrage der Daten erneut.

Link zur Divera API Dokumentation: https://api.divera247.com/?urls.primaryName=api%2Fv1#/E

Achtung
Hinweis: Der Intervall zum Triggern des Bausteins sollte nicht zu klein sein um des Gira X1 nicht zu überlasten. Ein Intervall von 20-30 Sekunden ist sinnvoll.

## Eingänge

E1 Trigger - Trigger ungleich 0 startet die Abfrage

E2 API KEY - Hier muss der API Key eingetragen werden.


## Ausgänge

A1 Einsatzalarm	- An diesem Ausgang liegt eine 1 an wenn ein Alarm anliegt.

A1 Stichwort - An diesem Ausgang wird das Stichwort ausgegeben wenn ein Alarm anliegt.

A1 Meldung - An diesem Ausgang wird die Meldung ausgegeben wenn ein Alarm anliegt.

A1 Datum/Uhrzeit	
An diesem Ausgang wird Dazum/Uhrzeit ausgegeben wenn ein Alarm anliegt.

A1 Adresse - An diesem Ausgang wird die Adresse ausgegeben wenn ein Alarm anliegt.

A1 Sonderrechte - An diesem Ausgang wird eine 1 ausgegeben wenn Sonderrechte konfiguriertwurden.

A1 Einsatznummer - An diesem Ausgang wird die Einsatznummer von Divera ausgegeben wenn ein Alarm anliegt.

A1 Impulsausgang - An diesem Ausgang wird ein Impuls (1) von einer Sekunde ausgegeben wenn ein Alarm anliegt.
