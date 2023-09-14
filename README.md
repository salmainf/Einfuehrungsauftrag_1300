# Einfuehrungsauftrag_1300

 # Projekt-Dokumentation

Salma Tanner

| Datum | Version | Zusammenfassung                                              | IPERKA      |
| ----- | ------- | ------------------------------------------------------------ |-------|
| 18.08.23      | 0.0.1   | Start des Projektes, beginnen mit der Projektdokumentation | I,P,E|
| 25.08.23      | 0.0.2   | Starten mit Implementieren, Aktualisieren der Projektdokumentation.| R|
|  01.09.23     | 0.0.3   | Weiterfahren mit Implementieren, Aktualisieren der Projektdokumentation|R|
|08.09.23|0.0.4|Abschliessen mit der Implementation und Erledigen des Portfolioeintrages|KA|

## 1 Informieren

### 1.1 Ihr Projekt

Ich habe in Visual Studio einen Numberguesser in C# implementiert.

In diesem Projekt geht es vorallem darum, meine C# Kenntnisse wieder ein wenig aufzufrischen und aufzubessern. Dies möchte ich mit Hilfe von einfacher Repetition durch Kurse, PPP oder vergangenen Projekten umsetzen. Ich erhoffe mir meine Kenntnisse mit C# zu erweitern und nutzen, um das Projekt so effizient wie möglich umzusetzen.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |   Muss          | Funktional     |  Als ein Programmierer möchte ich ene Zufallszahl zwischen 1-100 generieren. |
| 2    |    Muss         |  Funktional    |   Als User möchte ich, dass ich eine Rückmeldung erhalten, ob meine geratene Zahl richtig ist.                              |
| 3    |     Muss        | Funktional     |      Als User möchte ich Zahlen eingeben können, damit ich die Zufallszahl erraten kann.  |
| 4    |       Muss      |   Funktional   |     Als ein Programmierer möchte ich den User fragen, ob er nochmals eine Runde spielen will, wenn er die Zufalszahl erraten hat.   |
| 5    |       Muss      |   Funktional   |    Als ein Programmierer möchte ich den Namen des Nutzers abfragen, wenn im Multiplayer Modus gespielt wird.                        |
| 6    |       Muss      |    Funktional  |  Als ein User möchte ich am Ende sehen, wie viele Versuche ich gebraucht habe.|
| 7    |     Muss        |  Funktional    |   Als User möchte ich bei einer Falschen Eingabe eine Nachricht angezeigt bekommen.| 
| 8    |        Muss     | Funktional     |   Als ein User möchte ich bei jedem Versuch angezeigt bekommen, ob meine geratene Zahl kleiner oder grösser als die Zufallszahl ist.|
| 9   |     Muss        |  Funktional    |   Als ein User möchte ich zwischen dem Singleplayer und Multiplayer Modus auswählen können.| 




### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1 |  Programm gestartet         |  -       |      Speichern von Zufallszahl             |
| 2.1  |  Programm gestartet warten auf Eingabe von User            |  13       |   Richtig!/Falsch!                |
| 3.1 |  Programm gestartet          |  -       |  Ich denke die Zahl ist:                 |
| 4.1 |  Programm gestartet, Zufallszahl erraten         |  -       |  Wollen Sie nochmals spielen?                 |
| 5.1 |  Programm gestartet, spiel läuft         |  Salma     |  Salma du hast richtig geraten!                |
| 6.1 |  Programm gestartet, Zufallszahl erraten        |  -      |  Du hast x Versuche gebraucht                 |
| 7.1 | Programm gestartet, warten auf Eingabe von User         |  zh     | Eingabe Fehlerhaft!                | 
|8.1 |  Programm gestartet, spiel läuft      |   34      | Die Zufallszahl ist kleiner!                |



### 1.4 Diagramme

![grafik](https://github.com/salmainf/Einfuehrungsauftrag_1300/assets/110892351/10695a91-c463-4790-ada5-4eeb36f5af8f)

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |  25.08.23     |Salma Tanner|  Generieren und Speichern der Zufallszahl            |    30min           |
| 2.A |   25.08.23    |  Salma Tanner         |   Ausgabe von Rückmeldung, ob die geratene Zahl richtig ist.|30min  |        
| 3.A  |   25.08.23    |  Salma Tanner         |   Benutzereingabe von geratener Zahl generieren           |    30min           |
| 4.A  |   25.08.23    |  Salma Tanner         |   Nachfrage ob der Benutzer nach dem gewinnen nochmals eine Runde spielen will.           |   30min            |
| 5.A |   25.08.23    |  Salma Tanner         |  Abfrage für Benutzer-Name erstellen           |    30min           |
| 5.B |   25.08.23    |  Salma Tanner         |  benutzer-Name nach Gewinn mit Anzahl Versuchen ausgeben            |60min               |
| 6.A |   25.08.23    |  Salma Tanner         |   Speichern der Anzahl Versuche           |  30min             |
| 6.B |   25.08.23    |  Salma Tanner         |    Ausgabe von Anzahl Versuchen nach Gewinn          |  30min             |
| 7.A |   25.08.23    |  Salma Tanner         |   Generieren von Fehlerausgabe bei inkorrekter Eingabe           | 60min              |
| 8.A |   25.08.23    |  Salma Tanner         |     Ausgabe von Nachricht, wenn die geratene Zahl kleiner ist als die Zufallszahl.        |  30min             |
| 8.B |   25.08.23    |  Salma Tanner         |    Ausgabe von Nachricht, wenn die geratene Zahl grösser ist als die Zufallszahl.             |  30min             |

Total: 6.5h






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

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.



