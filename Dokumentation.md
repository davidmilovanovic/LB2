2# Modul 300 - Leistungsbeurteilung 2

## Inhaltsverzeichnis
 - [Service](#Service)
 - [Technische Angaben](#Technische-Angaben)
 - [Testing](#testing)
 - [Troubleshooting](#Troubleshooting)


## Service

Die LB2 besteht darin, ein Service zur Verfügung zu stellen. Dieser Service sollte mit Docker realisiert werden. Das ganze sollte anschliessend mit Markdown dokumentiert werden. Die Bewertungskriterien findet man [hier](https://bscw.tbz.ch/bscw/bscw.cgi/d29299146/LB2%20Anforderungen.pdf).

Bei meinem Service werden zwei Container erstellt. In dem einem Container befindet sich phpMyAdmin mit Apache2. In dem anderen Container befinde

## Technische Angaben
![Image](image/plan.png)  


## Testing

| Testfall                                                                                               | Resultat                                                                                                                                |
|--------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Git clone                                                               | Funktioniert einwandfrei                                                        |
| Container starten lassen                                        | Die Container lassen                                      |
| Vom Client auf http://localhost:80/phpmyadmin                                                                                                | Funktioniert. Phpmyadmin Startseite wird angezeigt.                                                       | 
| Mit root und Passwort anmelden                                                                                            | Funktioniert leider nicht                                                        |

  
## Toubleshooting



