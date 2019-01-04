# Nav on Docker

Dies ist ein Leitfaden zur Erstellung von Docker-Containern mit der Business Central Anwendung aus von Microsoft zur Verfügung gestellten Images auf einem Windows-Rechner.

Inhalt:
1)  Vorbereitung
2)  Container erstellen
3)  Container verwenden

Details zu den einzelnen Schritten befinden sich im [Wiki](https://github.com/BS-Concepts/Docker/wiki).

# 1. Vorbereitung

Zunächst müssen wir die "Docker for Windows"-Anwendung installieren. Diese bekommen wir von der [Docker Webseite](https://hub.docker.com/editions/community/docker-ce-desktop-windows).
Nach der Installation müssen wir sichergehen, dass Docker für Windows-Container eingestellt ist.
Anschließend installieren wir noch das PowerShell-Modul "Navcontainerhelper", welches die Arbeit mit NavContainern erleichtert.
Zum Schluss müssen wir noch ein Image festlegen aus dem wir den Container erstellen wollen.
Dieses können wir aus einem von Windows angelegten Repositoy auf [Docker Hub](https://hub.docker.com/r/microsoft/bconprem) beziehen.

Zum [Wiki](https://github.com/BS-Concepts/Docker/wiki)

# 2. Container erstellen

Aufruf des navcontainerhelper-Befehls "new-navcontainer" um einen neuen Container zu erstellen.
Die möglichen Parameter sind auf der GitHub Seite des [navcontainerhelper-repositorys](https://github.com/Microsoft/navcontainerhelper) zu finden.

Zum [Wiki](https://github.com/BS-Concepts/Docker/wiki)

# 3. Anwendung

Nun ist der Container betriebsbereit und er kann verwendet werden.
So kann zum Beispiel mit den erstellten Shortcuts auf den Windows- oder den Web-Client zugegriffen werden.
Auch die Verbindung auf den SQL-Server im Container, sowie das Arbeiten mit VS-Code und AL sind von außerhalb möglich.

Zum [Wiki](https://github.com/BS-Concepts/Docker/wiki)
