# Projektdokumentation LA-1300

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|18.08.2022|0.0.1|Dokumentation angefangen und Planen des Projektes.|
|25.08.2023| 0.0.2|Dokumentation erweitert, angefangen mit Programm.|   
|01.09.2023| 0.0.3|Programm fertig, angefangen zu Testen|   

## 1 Informieren

### 1.1 Ihr Projekt

Ich mach ein Programm, wo eine zufällige Zahl generiert wird und der User diese erraten muss. Ausserdem gibt es eine GUI und Soundeffekte.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
|1|muss|funktional|Als User möchte ich, dass ich nach dem Raten einen Hinweis bekomme, wie gross die zufällige Zahl ist, damit ich die Zahl einfacher erraten kann.|
|2|muss|funktional|Als User möchte ich, dass es ein GUI gibt, damit es eine übersichtliche und verständliche Übersicht ist.|
|3|muss|funktional|Als User möchte ich, dass es Soundeffekte gibt, damit ich weiss ob ich richtig oder falsch geraten habe.|
|4|muss|funktional|Als User möchte ich, dass ich am Ende sehe wie viel Rateversuche ich gebraucht habe, damit ich weiss, ob ich besser war als vorher.|
|5|muss|funktional|Als User möchte ich, dass am Ende des Programms die Möglichkeit kommt, das Spiel erneut zu spielen, damit ich nochmal spielen und Spass haben kann.|
|6|muss|funktional|Als User möchte ich, dass die Rückmeldung mit Farben veranschaulich wird, damit es klarer ist, ob ich richtig oder falsch geraten habe.|
|7|muss|funktional|Als User möchte ich, dass es nicht möglich ist Zahlen über 100 und unter 0 einzugeben, damit ich keinen Absturz erhalte.|

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | 
| ---- | ------------ | ------- | ----------------- |
|1.1|Pogramm wird geöffnet|Der User gibt ein geratene Zahl ein|Die geratene Zahl wird geprüft, ob sie der random Zahl entspricht. Wenn ja gewinnt der User das Spiel|
|1.2|Programm wird geöffnet|keine Eingabe|Wenn die geratene Zahl grösser ist als die generierte Zahl, wird ein roter Text ausgeben, dass die Zahl zu gross ist|
|1.3|Programm wird geöffnet|keine Eingabe|Wenn die geratene Zahl kleiner ist als die generierte Zahl, wird ein roter Text ausgeben, dass die Zahl zu klein ist|
|2.1|Programm wird geöffnet|keine Eingabe|Es gibt ein GUI|
|3.1|Programm wird geöffnet|eine Zahl|Es gibt einen Sound als Rückmeldung|
|4.1|Zahl wurde erraten|keine Eingabe|Programm zeigt wie viele Versuche man gebraucht hat|
|5.1|Zahl wurde erraten|keine Eingabe|Programm fragt, ob man nochmal spielen will|
|6.1|Programm wird geöffnet|eine Zahl|Es gibt einen farbigen Text (je nach geratener Zahl anders) als Rückmeldung|
|7.1|Programm wird geöffnet|eine Zahl über 100 oder unter 0|Programm gibt aus, dass keine Zahlen über 100 oder unter 0 eingegeben werden können|


## 2 Planen

| AP-№ |  Zuständig | Beschreibung | geplante Zeit |
| ---- | --------- | ------------ | ------------- |
| 1.A|Kritzner|Der User wird nach einer geratenen Zahl gefragt|60 min|
| 1.B|Kritzner|Die geratene Zahl wird geprüft ob sie grösser ist|10 min|
| 1.C|Kritzner|Die geratene Zahl wird geprüft ob sie grösser ist|10 min|
| 2.A  |Kritzner|Es gibt ein GUI|120 min|
| 3.A  |Kritzner|Nach Eingabe gibt es einen Sound|40 min|
|  4.A |Kritzner|Programm zeigt Anzahl Versuche.|20 min|
|  5.A |Kritzner|Programm fragt, ob man nochmal spielen will|   45 min            |
|  6.A |Kritzner|Es gibt farbige Rückmeldungen|30 min       | 
|  7.A |Kritzner|Programm kann Fehleingaben und nichtige Eingaben abfangen|30 min       | 





