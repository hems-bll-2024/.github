# STYLEGUIDE der Organisation _hems-bll-2024_

---

## 1 Repository

### 1.1 Dateistruktur

-   Jedes Repository **muss** eine README.md und LICENSE.md Datei beinhalten.
    -   README.md Dateien **sollten** eine _möglichst_ genaue Aussage über Aufbau, Funktion und Verhalten der im Repository gespeichterten Datein wiedergeben. Die Datei kann auch für bestimmte Zwecke sich _nicht_ im 'root'-Verzeichnis des Repositories befinden, sondern innerhalb eines eigenen Ordners.
    -   Die LICENSE.md Datei **muss** mit der LICENSE.md Datei im Repository [.github](https://github.com/hems-bll-2024/.github) übereinstimmen. (Aktuelle Lizenz: [BSD-3-Clause](https://joinup.ec.europa.eu/licence/bsd-3-clause-new-or-revised-license))
-   Jedes Repository **sollte**, sofern es sich um 'Code' handelt, ein src Ordner beinhalten, in dem der komplette Quellcode enthalten ist.

### 1.2 Commits

-   Jeder Commit enthält zwei 'Messages' (-m), die den folgenden Formaten entsprechen:
    1. Message: "Version: [[Semver 2.0.0 Code](https://semver.org/lang/de/)], [Eigens gewählter Titel des Commits]"
    2. Message: "[Beschreibung des Commits oder das Informationsformat[^1]]"

<!-- Kommentar zur visuellen Trennung des Haupttextes und der Fußnoten -->

[^1]:
    Informationsformat:
    Version: [Semver 2.0.0 Code]
    Autor: [Autorname (Github-Name oder echter Name)]
    Aktuelle Lizenz: [Aktuelles Lizenzkürzel]
    \n \<-Optional-\> Neue Funktionen:
    [Liste der neuen Funktionen]
    \n \<-Optional-\> Modifizierte Funktionen:
    [Liste der modifizierten Funktionen]
    \n \<-Optional-\> Entfernte Funktionen:
    [Liste der entfernten Funktionen]
