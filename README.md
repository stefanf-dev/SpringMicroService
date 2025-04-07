# Spring Microservice – Mitarbeitermanagement & Zeiterfassung

Dieses Projekt ist eine Microservice-basierte Anwendung zur Verwaltung von Mitarbeiter und Unternehmen.

## Features

- **Registrierung & Login** für Mitarbeiter und Unternehmen
- **Erfassung & Bearbeitung** von Arbeitszeit- und Lohndaten
- **Verwaltung von Mitarbeiterinformationen** Übersicht über alle Mitarbeitenden & deren Daten für Arbeitgeber
- **Interne Kommunikation** zwischen Mitarbeitenden
- **REST-API** für den Zugriff auf die Services
- **Spring Security** zur Authentifizierung und Rollenverteilung

## Projektinstallation und Ausführung

-	Clonen des Repositories von https://github.com/stefanf-dev/SpringMicroService
-	Starten des Docker Servers mit dem Command: docker run --name mysqlContainer -p 3307:3306 -e MYSQL_ROOT_PASSWORD=root -d mysql
-	Command: mvn install (wenn Maven vorhanden) Oder: Projekt in der IDE öffnen und dort maven install ausführen
-	Starten der jar-File im Ordner: SpringMicroService/target/spring-boot-docker.jar im Terminal mit dem command: java -jar spring-boot-docker.jar
