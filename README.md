# Beispielprojekt mit JDBC (Java Database Connectivity)

Informationssysteme II, Bachelor Wirtschaftsinformatik

Stefan Sarstedt, stefan.sarstedt(at)haw-hamburg.de  
Sven Berding, sven.berding(at)haw-hamburg.de

Einrichtungshinweise:
1. Führe die Schritte von https://git.haw-hamburg.de/SoSe22IN2/in2lab (A. Einrichtung des JDK) durch.
2. Starte eine lokale MySQL-Instanz. Es gibt mindestens zwei Möglichkeiten: 
    1. Du installierst Dir MySQL (Download unter https://www.mysql.com/de/) .
    2. Du installierst Docker (https://www.docker.com) und startest eine MySQL-Instanz mittels `docker-compose`:
        ```bash
        docker-compose up -d
        ```
3. Führe die Applikation aus mittels (Vorsicht: nicht **build**!)
     ```bash
     ./gradlew bootRun (unter Linux/macOS, bei Bedarf dort zuvor "chmod +x ./gradlew" ausführen, um die Ausführungsberechtigung zu setzen)
     ```
     bzw. 
     ```bash
     gradlew.bat bootRun (unter Windows)
     ```    

4. Stoppe Deine MySQL-Instanz wieder.

Dieses Projekt basiert auf:
- https://www.baeldung.com/java-jdbc
- http://makble.com/gradle-example-to-connect-to-mysql-with-jdbc-in-eclipse
