# 2019-07-02 Thesis Meeting

|||
-----------------------|---------------------------------------------
 **Participants**:     | ANO MOE
 **Date**:             | 2019-07-02
 **Start time**:       | 13:00
 **End time**:         | 14:00
 **Location**:         | 079

## Agenda

* Titel
* Arbeitsplan
* Diagramme
* Use Cases

## Discussed Topics

* Titel
    * Totwinkel und Totewinkel ist geschützt, kann nicht als Name eingesetzt werden
    * Favorit: Umsetzung eines kooperativen Toter-Winkel-Assistent
    * Wird Prof. Wieker vorgestellt und der gibt OK
* Arbeitsplan
    * pdf im BsdDiagramme Ordner 
    * sieht ok aus
* Diagramme
    * Komponentendiagramme
        * Externe Komponenten sollten eine andere Farbe
        * Alle Komponenten sollten die gleiche Größe haben und gleich ausgerichtet sein
        * So wenig Abkürzungen wie möglich
        * Interface zu BSD von CAM_Handler umdrehen --> Eventbasiert
        * Schnittstellennamen verwenden anstatt des übertragenen Datentyps
        * Es fehlt eine Sensor Komponenten für z.B. Blinker (TurnSignalLights)
        * Externe Komponenten
            * Positioning Service 
            * Local Dynamic Map (V2xMessageHandler)
            * HMI Provider
            * Sensor Data Provider (deine Software muss Converge_PositioningServiceClient (converge.service) implementieren)
        * Sequenzdiagramme
            * Mit Status/Zuständen arbeiten
            * Logik klar machen, wann z.B. aktuallisiert wird
        * Use Case Beschreibungen
            * Mindestens zwei Akteure
            * Klar machen, ob auf Autobahn oder im urbanen Bereich (Stadt)
            * *Magic Numbers* klar machen, woher die kommen (Abstand 15m)


## Assigned Work
