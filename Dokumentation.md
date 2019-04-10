2# Modul 300 - Leistungsbeurteilung 2

## Inhaltsverzeichnis
 - [Aufgabenstellung](#aufgabenstellung)
 - [Netzwerkplan](#netzwerkplan)
 - [Mein Service](#mein-service)
 - [Testing](#testing)


## Aufgabenstellung

Die LB1 besteht darin, ein Service zur Verfügung zu stellen. Dieser Service sollte mit dem starten eines Vagrantfiles ohne weitere Konfigurationen starten. Das ganze sollte anschliessend mit Markdown dokumentiert werden. Die Bewertungskriterien findet man [hier](https://bscw.tbz.ch/bscw/bscw.cgi/d29084554/M300_LB1_Bewertungsraster.pdf?op=get&open=1).

## Voraussetzungen/WichtigeThemen


## Netzwerkplan

![Image](Netzwerkbild.png)        

<div id='id-section2'/>

## Mein Service

Bei meinem Service wird ein Webserver erstellt. Auf dem Webserver läuft die Webanwendung phpMyadmin, welches mit dem sql-Server verbunden ist.


**Zugriff auf den Service** </br>
Man muss in einem Browser http://10.71.13.8:80/phpmyadmin eingeben.


## Testing

| Testfall                                                                                               | Resultat                                                                                                                                |
|--------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Vom Client auf http://localhost:80 zugreifen.                                                                 | Funktioniert. Die Default Page des Webservers wird angezeigt.                                                        |
| Vom Client auf http://localhost:80/phpmyadmin                                           | Funktioniert. Phpmyadmin Startseite wird angezeigt.                                     |
| git clone                                                                                              | Funktioniert einwandfrei                                                        |
| FireWall Status überprüfen                                                                                            | FireWall is running                                                        |

  




