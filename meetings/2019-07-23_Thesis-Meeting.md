# 2019-07-23 Thesis Meeting

|||
-----------------------|---------------------------------------------
 **Participants**:     | ANO MOE
 **Date**:             | 2019-07-23
 **Start time**:       | 13:00
 **End time**:         | 14:30
 **Location**:         | 079

## Agenda

* Diagramme
* Softwarestand

## Discussed Topics

* Diagramme
    * Komponentendiagramm: PositionProviding zu VehicleInfoProviding
    * Externer Output-Rahmen wie die anderen nach oben vergrößern
    * Sequenzdiagramme:
        * Anstatt generatedCam eher "receiving CAM"
        * Anstatt "Sending requisite CAM data" her "Sending Foreign vehicle information"
        * Im EA: Arbeiten mit "isReturn" Pfeilen für Rückgaben von Funktionen
        * Unterscheide synchrone von asynchronen Aufrufen z.B. LDM
        * Gleiche Namen für gleiche Aufrufe verwenden in den unterschiedlichen Diagrammen
* Softwarestand
    * Objekt zur Übertragung zwischen CamHandler und BlindSpotDetection: "ForeignVehicleInformation"
* Konzept
    * Scoreberechnung anhand Geschwindigkeitsdifferenz, Richtung, Distanz etc...
    * Alle Informationen (eigene Position, Richtung, Geschwindigkeit, Blinker, ...) immer wenn verfügbar an BlindSpotDetection geben
    * Pflegen einer Datenbank/Liste/... mit potentiell gefährlichen Fahrzeugen (Score > Threashold)

## Assigned Work

