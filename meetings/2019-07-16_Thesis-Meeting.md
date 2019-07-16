# 2019-07-16 Thesis Meeting

|||
-----------------------|---------------------------------------------
 **Participants**:     | ANO MOE
 **Date**:             | 2019-07-16
 **Start time**:       | 13:00
 **End time**:         | 
 **Location**:         | 079

## Agenda

* Diagramme
* Softwarestand

## Discussed Topics

* Diagramme
    * Komponentendiagramm
        * Komponenten und Interfaces gut
        * ConfigurationAdmin nach links
        * Rahmen mit Externe Inputs und Externe Outputs benennen
        * Weitere Komponente erforderlich für StationInformation und SensorDataHandler
    * Ablaufdiagramme
        * MOE weiß was zu tun ist
* Softwarestand
    * Checkstyle aktivieren, um Warnungen zu minimieren
    * möglichst keine Abkürzen benutzen
    * kein Bsd Prefix an den Interfacenamen
    * Interfacenamen und Komponentennamenaus Komponentendiagramm benutzen!
    * PositionHandler
        * getDistance kann weg
        * Überprüfe, ob du einzeln Position, Speed, etc holst, oder in einem Objekt gebündelt
    * CAM zu BlindSpotDetectionMessage im CamHandler umsetzen und nicht erst im CamProcessing


## Assigned Work

* Diagramme finalisieren
* MOCK fertig stellen