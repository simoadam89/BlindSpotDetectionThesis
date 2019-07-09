# 2019-07-02 Thesis Meeting

|||
-----------------------|---------------------------------------------
 **Participants**:     | ANO MOE
 **Date**:             | 2019-07-09
 **Start time**:       | 13:10
 **End time**:         | 14:00
 **Location**:         | 079

## Agenda

* Titel
* Diagramme
* Magic Numbers

## Discussed Topics
* Titel
    * Heute noch zu Herrn Wieker und Titel vorschlagen
    * Wenn Titel fest steht: Thesis anmelden!
* Diagramme
    * Kompontendiagramm
        * Am BlindSpotDetection ist ein Interface ohne zugehörige Komponente
        * Verbindung zwischen BlindSpotDetection und HMI_Connector ist ohne Namen
            * z.B. BlindSpotIndicating
        * HMI_Connector sollte HmiConnector heißen
        * Anzeige heißt HmiProvider und dessen Schnittstelle heißt auch HmiProvider
        * Beschriftung des Rahmens fehlt
            * Komponenten nach dem EVA (Eingabe-Verarbeitung-Ausgabe) Prinzip gruppieren
        * Für die Konfiguration fehlt noch der ConfigurationAdmin mit dem ManagedService Interface
    * Sequenzdiagramme
        * Logik nicht erkennbar
        * nach jedem Pfeil sollte direkt der nächste Pfeil/Schritt folgen
        * siehe Skizze
* Magic Numbers
    * IEEE beschreibt ca. 3m x 3m Fläche schräg hinter dem Auto
    * Volvo (BLIS) arbeitet mit ca. 10m x 3m
    * Eigene Erfahrungswerte müssen noch ermittelt werden und später konfigurierbar sein
* Geplante Arbeiten
    * Implementierung beginnen
        * MOCK implementierungen empfohlen, damit die Schnittstellen schonmal funktionieren
    * Sequenzdiagramme überarbeiten
    * Komponentendiagramm ergänzen
    * Abklären mit JES wie die "ManagementDatenbank" aussieht, in der z.B. Autolänge etc gespeichert ist
    * Mit FLP abklären, wo und wie z.B. die GPS Antenne markiert und platziert werden soll

## Assigned Work
