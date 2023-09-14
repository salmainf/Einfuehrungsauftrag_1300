# Einfuehrungsauftrag_1300 Projektdokumentation

 # Projekt-Dokumentation

Salma Tanner

| Datum | Version | Zusammenfassung                                              | IPERKA      |
| ----- | ------- | ------------------------------------------------------------ |-------|
| 18.08.23      | 0.0.1   | Start des Projektes, beginnen mit der Projektdokumentation, Einarbeiten in C# | I,P,E|
| 25.08.23      | 0.0.2   | Starten mit Implementieren, Aktualisieren der Projektdokumentation.| R|
|  01.09.23     | 0.0.3   | Weiterfahren mit Implementieren, Aktualisieren der Projektdokumentation|R|
|08.09.23|0.0.4|Abschliessen mit der Implementation und Erledigen des Portfolioeintrages|KA|

##  Informieren

### Mein Projekt

Ich habe in Visual Studio einen Numberguesser in C# implementiert.

In diesem Projekt geht es vorallem darum, meine C# Kenntnisse wieder ein wenig aufzufrischen und aufzubessern und möglichst objektporientiert zu Programmieren. Dies möchte ich mit Hilfe von einfacher Repetition durch Kurse, PPP oder Youtube Videos umsetzen. Ich erhoffe mir meine Kenntnisse mit C# zu erweitern und nutzen, um das Projekt so effizient wie möglich umzusetzen.

###  User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |   Muss          | Funktional     |  Als ein Programmierer möchte ich ene Zufallszahl zwischen 1-100 generieren. |
| 2    |    Muss         |  Funktional    |   Als User möchte ich, dass ich eine Rückmeldung erhalte, ob meine geratene Zahl richtig ist.                              |
| 3    |     Muss        | Funktional     |      Als User möchte ich Zahlen eingeben können, damit ich die Zufallszahl erraten kann.  |
| 4    |       Muss      |   Funktional   |     Als ein Programmierer möchte ich den User fragen, ob er nochmals eine Runde spielen will, wenn er die Zufalszahl erraten hat.   |
| 5    |       Muss      |   Funktional   |    Als ein Programmierer möchte ich den Namen der Nutzer abfragen, wenn im Multiplayer Modus gespielt wird.|
| 6    |       Muss      |    Funktional  |  Als ein User möchte ich am Ende sehen, wie viele Versuche ich gebraucht habe.|
| 7    |     Muss        |  Funktional    |   Als User möchte ich bei einer Falschen Eingabe eine Nachricht angezeigt bekommen.| 
| 8    |        Muss     | Funktional     |   Als ein User möchte ich bei jedem Versuch angezeigt bekommen, ob meine geratene Zahl kleiner oder grösser als die Zufallszahl ist.|
| 9   |     Muss        |  Funktional    |   Als ein User möchte ich zwischen dem Singleplayer und Multiplayer Modus auswählen können.| 
| 10   |     Muss        |  Funktional    |   Als ein User möchte ich zwischen dem Normalen und Limitierten Modus auswählen können.| 
| 11  |     Muss        |  Funktional    |   Als ein User möchte ich im Limitierten Modus 5 Versuche zu Verfügung gestellt bekommen | 
| 12   |       Muss      |    Funktional  |  Als ein User möchte ich im Multiplayer Modus als Spieler 1 eine Zufallszahl eingeben können|
| 13    |       Muss      |    Funktional  |  Als ein User möchte ich als Spieler 2 die Zahl erraten können.|



###  Diagramme

<img width="516" alt="Screenshot 2023-09-13 145402" src="https://github.com/salmainf/Einfuehrungsauftrag_1300/assets/110892351/fbe58592-4829-4703-b2c2-b39fa5b896bd">
<img width="292" alt="Screenshot 2023-09-13 145257" src="https://github.com/salmainf/Einfuehrungsauftrag_1300/assets/110892351/5d6045b2-26d7-40c6-bb57-094bffac8663">
<img width="298" alt="Screenshot 2023-09-13 145311" src="https://github.com/salmainf/Einfuehrungsauftrag_1300/assets/110892351/47aaaaf0-9fe5-4758-8ea4-619db6450732">


##  Planen

| AP-№ | Frist | Zuständig | Beschreibung | 
| ---- | ----- | --------- | ------------ | 
| 1.A  |  25.08.23     |Salma Tanner|  Generieren und Speichern der Zufallszahl            |   
| 2.A |   25.08.23    |  Salma Tanner         |   Ausgabe von Rückmeldung, ob die geratene Zahl richtig ist.|       
| 3.A  |   25.08.23    |  Salma Tanner         |   Benutzereingabe von geratener Zahl generieren           |   
| 4.A  |   25.08.23    |  Salma Tanner         |   Nachfrage ob der Benutzer nach dem gewinnen nochmals eine Runde spielen will.           |  
| 5.A |   25.08.23    |  Salma Tanner         |  Abfrage für Benutzer-Name erstellen           |   
| 5.B |   25.08.23    |  Salma Tanner         |  benutzer-Name nach Gewinn mit Anzahl Versuchen ausgeben            |
| 6.A |   25.08.23    |  Salma Tanner         |   Speichern der Anzahl Versuche           |  
| 6.B |   25.08.23    |  Salma Tanner         |    Ausgabe von Anzahl Versuchen nach Gewinn          |  
| 7.A |   25.08.23    |  Salma Tanner         |   Generieren von Fehlerausgabe bei inkorrekter Eingabe           | 
| 8.A |    01.09.23     |  Salma Tanner         |     Ausgabe von Nachricht, wenn die geratene Zahl kleiner ist als die Zufallszahl.        |  
| 8.B |   01.09.23    |  Salma Tanner         |    Ausgabe von Nachricht, wenn die geratene Zahl grösser ist als die Zufallszahl.             |  
| 9.A |   01.09.23    |  Salma Tanner         |   Einbauen des Multiplayer Modus           | 
| 10.A |    01.09.23     |  Salma Tanner         |   Einbauen des Limitierten Modus           | 
| 11.A |    01.09.23     |  Salma Tanner         |   Ändern der Anzahl maximaler Versuche im Limitierten Modus           | 
| 12.A |    01.09.23     |  Salma Tanner         |   Benutzerdefinierte Eingabe der Zufallszahl im Multiplayer Modus           | 
| 13.A |   01.09.23    |  Salma Tanner         |   Benutzereingabe zum erraten der benutzerdefinierten Zufallszahl          | 








## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |  25.08.23     | Salma Tanner          |   30min            |     30min              |
| 2.A  |   25.08.23     |  Salma Tanner         |   30min            |        30min           |
| 3.A  |  25.08.23     |   Salma Tanner        |     30min         |        30min           |
| 4.A  |  25.08.23     |  Salma Tanner         |     30min          |           30min        |
| 5.A  |  25.08.23     |   Salma Tanner        |      30min         |       45min            |
| 5.B  |  25.08.23     |   Salma Tanner        |      60min        |        190min           |
| 6.A  |  25.08.23     |   Salma Tanner        |      30min         |      30min             |
| 6.B  |  25.08.23     |   Salma Tanner        |       30min        |        30min           |
| 7.A  |  25.08.23     |   Salma Tanner        |       60min        |         60min          |
| 8.A  |  25.08.23     |   Salma Tanner        |       30min       |       30min            |
| 8.B  |  25.08.23     |   Salma Tanner        |       30min        |      30min             |


## 5 Kontrollieren
###  Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1 |  Programm gestartet         |  -       |      Speichern von Zufallszahl in Variable            |
| 2.1  |  Programm gestartet warten auf Eingabe von User            |  Zahl      |   Richtig!/Falsch!                |
| 3.1 |  Programm gestartet          |  -       |  Ich denke die Zahl ist:                 |
| 4.1 |  Programm gestartet, Zufallszahl erraten         |  -       |  Wollen Sie nochmals spielen?                 |
| 5.1 |  Programm gestartet, spiel läuft im Multiplayer Modus        |  Namen der Spieler     |  Salma gib eine Zufallszahl ein:/ Sudenas errate die Zufallszahl:                |
| 6.1 |  Programm gestartet, Zufallszahl erraten        |  -      |  Du hast x Versuche gebraucht                 |
| 7.1 | Programm gestartet, warten auf Eingabe von User         |  zh     | Eingabe Fehlerhaft!                | 
|8.1 |  Programm gestartet, spiel läuft, warten auf Eingabe von User      |   34      | Die Zufallszahl ist kleiner/grösser!                |
|9.1 |  Programm gestartet, spiel läuft      |   -     | Willst du im Singleplayer oder im Multiplayer Modus spielen?:                |
|10.1 |  Programm gestartet, spiel läuft      |   -      | Willst du im Limitierten oder Normalen Modus spielen?:                |
|11.1 |  Programm gestartet, spiel läuft im Limitierten Modus     |   Limitiert     | Errate die Zufallszahl mit nur 5 Versuchen + Setzen der MaximalAttempts=5;                |
|12.1 |  Programm gestartet, spiel läuft      |   Name des Spielers als Spieler 1      | Salma gib eine Zufallszahl ein:                |
|13.1 |  Programm gestartet, spiel läuft, Console Clear      |   Eingabe Zufallszahl durch Spieler 1      | Sudenas errate die Zufallszahl:                |


| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |   08.09.23    |   Funktioniert       |  Salma Tanner      |
| 2.1  |   08.09.23     |  Funktioniert         |  Salma Tanner        |
| 3.1  |   08.09.23    |   Funktioniert        |   Salma Tanner       |
| 4.1  |   08.09.23    |   Funktioniert        |   Salma Tanner       |
| 5.1  |   08.09.23    |  Funktioniert         |   Salma Tanner       |
| 6.1  |   08.09.23    |    Funktioniert       |   Salma Tanner       |
| 7.1  |   08.09.23    |    Funktioniert teilweise      |   Salma Tanner       |
| 8.1  |   08.09.23    |    Funktioniert       |   Salma Tanner       |
| 9.1  |   08.09.23    |     Funktioniert      |   Salma Tanner       |
| 10.1  |   08.09.23    |   Funktioniert        |   Salma Tanner       |
| 11.1  |   08.09.23    |    Funktioniert       |   Salma Tanner       |
| 12.1  |   08.09.23    |    Funktioniert       |   Salma Tanner       |
| 13.1  |   08.09.23    |   Funktioniert        |   Salma Tanner       |

Das Spiel funktioniert im grossen und ganzen sehr gut, man kann es spielen. Sowohl im Multiplayer oder Singleplayer als auch im Normalen oder Limitierten Modus. Diese funktionieren alle einwandfrei. Die Fehlermeldungen werden jedoch nur bei den Benutzereingaben beim erraten der Zufallszahl angezeigt. Das ist ein Schwachpunkt, welcher ich noch verbessern hätte können. Dies hätte ich tun können, indem ich die Fehlermeldungen auch auf String's beziehe und nicht nur auf Int's. Darin lag mein Fehler, nun weiss ich es und kann es beim nächsten Projekt anwenden.



