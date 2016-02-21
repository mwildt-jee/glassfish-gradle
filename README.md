# glassfish-gradle
Gradle Tasks für Web-Projekte im Glassfish Server

## Aufgabe
Schreiben Sie einen einfachen Deployment-Task, der nach dem Build des `war`-Archives eines Web-Moduls, das Deployment auf den laufenden Glassfish-Server durchführt.

Hinweise:
* Das Deployment erfolgt über die Glassfish-Konsole mit dem Befehl `asadmin deploy /path/to/war/archive`
* Das von Gradle erzeugte `war`-Archiv wird im Verzeichnis `build/libs` abgelegt.
* Nutzen Sie zum Testen das Projekt web-sample-gradle unter https://github.com/mwildt-jee/web-sample-gradle
