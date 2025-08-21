| Vorteile von **UDP**                                                                 | Nachteile von **UDP**                                                                                   |
|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| **UDP** ist viel schneller als **TCP**.                                               | **UDP** überprüft nicht, ob die Daten tatsächlich empfangen wurden.                                     |
| **UDP** überlässt es der Anwendung (Nutzersoftware), zu entscheiden, wie schnell Pakete gesendet werden. | Das ist zwar flexibel für Entwickler, kann aber problematisch sein.                                     |
| **UDP** reserviert keine dauerhafte Verbindung auf einem Gerät wie **TCP**.           | Das bedeutet, dass instabile Verbindungen für den Nutzer eine schlechte Erfahrung zur Folge haben.       |

| Vorteile von **TCP**                                                                 | Nachteile von **TCP**                                                                                                      |
|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| Garantiert die Integrität der Daten.                                                  | Benötigt eine zuverlässige Verbindung zwischen den Geräten. Wenn ein kleines Datenstück nicht empfangen wird, muss das gesamte Datenstück erneut gesendet werden. |
| Kann zwei Geräte synchronisieren, um zu verhindern, dass sie sich gegenseitig mit Daten in falscher Reihenfolge überfluten. | Eine langsame Verbindung kann ein anderes Gerät ausbremsen, da die Verbindung die ganze Zeit für dieses Gerät reserviert bleibt. |
| Führt viele zusätzliche Prozesse zur Sicherstellung der Zuverlässigkeit durch.        | **TCP** ist deutlich langsamer als **UDP**, da die Geräte mehr Rechenarbeit bei der Nutzung dieses Protokolls leisten müssen. |

**Wichtige Common Ports**
| Protokoll                       | Portnummer | Beschreibung                                                                                                                                           |
|---------------------------------|------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| File Transfer Protocol (**FTP**) | 21         | Dieses Protokoll wird von einer Dateiübertragungs-Anwendung im Client-Server-Modell genutzt. Damit können Dateien von einem zentralen Ort heruntergeladen werden. |
| Secure Shell (**SSH**)           | 22         | Dieses Protokoll wird genutzt, um sich sicher per textbasierter Oberfläche auf Systeme einzuloggen und sie zu verwalten.                               |
| HyperText Transfer Protocol (**HTTP**) | 80   | Dieses Protokoll betreibt das World Wide Web (WWW)! Dein Browser nutzt es, um Texte, Bilder und Videos von Webseiten herunterzuladen.                  |
| HyperText Transfer Protocol Secure (**HTTPS**) | 443 | Dieses Protokoll macht genau dasselbe wie oben; jedoch sicher, da es Verschlüsselung verwendet.                                                       |
| Server Message Block (**SMB**)   | 445        | Dieses Protokoll ist dem File Transfer Protocol (**FTP**) ähnlich; jedoch können zusätzlich zu Dateien auch Geräte wie Drucker gemeinsam genutzt werden.|
| Remote Desktop Protocol (**RDP**) | 3389      | Dieses Protokoll ist ein sicherer Weg, um sich per grafischer Desktop-Oberfläche auf ein System einzuloggen (im Gegensatz zu den textbasierten Einschränkungen von **SSH**). |


**Find all table of the 1024 common ports listed in the link below**
https://www.vmaxx.net/techinfo/ports.htm

