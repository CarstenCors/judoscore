# Judo-Anzeigetafel

Eine vollständige Judo-Anzeigetafel-Software in einer *einzigen HTML-Datei*.  
Kann ohne Webserver verwendet werden, einfach die Datei `score.html` lokal im Webbrowser öffnen. Der Ressourcenordner dient nur der Bequemlichkeit.

<img src="screenshot.jpg?raw=true" alt="Beispielansicht" width="400" height="200" />

Inklusive dem 2025 wieder zurückgekehrten Yuko als Wertung.

## Hardware-Einrichtung
Die Software wurde für den Betrieb in einem "Duplicate-Screen"-Setup entwickelt, sodass der Bediener dasselbe sieht wie das Publikum.

## Konfiguration
Beim ersten Start oder durch Aufrufen des Einstellungsmenüs (Zahnrad-Symbol in der unteren linken Ecke) wird der Konfigurationsdialog geöffnet.

## Bedienung
Eine kurze Bedienungsanleitung ist im Menü enthalten. Punkte können mit der Maus zugewiesen werden, es gibt jedoch auch verschiedene Tastenkombinationen zur Steuerung von Uhren usw.

### Maus Bedienung

| Taste  | Funktion              |
|--------|-----------------------|
| Kampfzeit (links-klick)  | Mate / Hajime         |
| Kampfzeit (doppel-klick)  | Kampfzeit zurücksetzen         |
| Haltezeit (link-klick) | Osaekomi / Toketa |
| Haltezeit (doppel-klick) | Haltezeit zurücksetzen |
| Wertung (links-klick) | Wertung geben (Ippon / Wazari / Yuko) |
| Wertung (rechts-klick) | Wertung zurücknehmen (Ippon / Wazari / Yuko) |
| Strafe (links-klick) | Sido geben |
| Strafe (rechts-klick) | Sido zurücknehmen |

### Tastenbelegungen

| Taste  | Funktion              |
|--------|-----------------------|
| SPACE  | Mate / Hajime         |
| H      | Hajime               |
| M      | Mate                 |
| O      | Osaekomi             |
| T      | Toketa               |
| G      | Goldenscore          |
| B      | Glocke               |
| R      | Alles Zurücksetzen   |
| C      | Menü                 |

## Schnittstelle für Webserver
Es gibt eine Schnittstelle, um Live-JSON-Daten zu importieren, mit denen Namen sowie Gruppen- und Rundeninformationen von einem Drittanbieter-Webserver oder einer Datenbank angezeigt werden können.

## Eigene Glocken-/Horn-/Audiodateien
Eigene Audiodateien können in eingebetteter Base64-Form hinzugefügt werden:  
`<audio id="sound[n]" src="data:audio/ogg;base64,...>`

## Lizenz
Kostenlose Nutzung und Modifikation für nicht-kommerzielle Zwecke.  
(c) 2025 [https://github.com/carstencors/](https://github.com/carstencors/)

