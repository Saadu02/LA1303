# LA1302

Name: Sathana Suganthasri

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 14.02.2024 | 0.0.1     | Projekt fertig erstellt.|
| 14.01.2024 | 0.0.2     | Dokumentation fertig erstellt.|


## 1 Informieren

### 1.1 Ihr Projekt

In meinem Projekt geht es um ein Quiz. Der Benutzer kann Fragen und Antworten schreiben, ändern, Löschen und Aufrufen kann. 

### 1.2 Anforderung

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 | muss | Funktion | Der Benutzer muss wörter einfügen können. |
| 2 | muss | Randbedingung | Das Programm soll in C# geschrieben werden.|
| 3 | muss | Funktion | Nach jedere einfügen des Wörters, müssen die Karten gespeichert werden. |
| 4 | muss | Funktion | Dss Program soll eine Änderungsfunktion haben, um Karteikarte zu ändern. |
| 5 | muss | Funktion | Das Programm soll eine Lösch-Funktion haben, um Karteikarte zu löschen.|
| 6 | muss | Funktion | Wenn ich eine ID eingebe, muss dem entsprechende ID angezeigt werden. |
| 7 | muss | Funktion | Das Programm muss ein Datenbank haben, um später die Kärtchen auszurufen. |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1 | Programm startet (Get)| - | [] | 
| 1.2 | Testfall 1.1 | Frage: "Wer ist das" Antwort "ein Hund" | Frage: "Wer ist das" Antwort "ein Hund" |
| 3.1 | Ihr neuer Notenschnitt ist ... Möchten sie weitere Noten eingeben y oder n? | n | Ihre Notenschnitt wäre .... und das heisst .....  |
| 4.1 | Programm startet | doqjd | Ihre Eingabe ist ungültig. Bitte geben Sie eine Zahl ein.|
| 4.2 | Möchten Sie weitere Noten eingeben y oder n?| fojwe | Ihre Eingabe ist ungültig. Bitte geben Sie eine y oder n.|
| 5.1 | Programm startet | 10 | Bitte geben Sie eine Zahl zwischen 1 und 6 ein. |
| 6.1 | Programm startet: Willkommen zum Notenrechner! Geben Sie Ihre Note ein:  | 3 | Ihr neuer Notenschnitt ist 3. Möchten Sie weitere Noten eingeben y oder n? |
| 7.1 | 2 | n | Ihr Notenschnitt wäre 3.125 und heisst ungenügend. |
| 8.1 | Möchten Sie weitere Noten eingeben y oder n?| 45erdf | *Beep* |


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A | 17.01.2024 | Sathana | Wörter einfügen | 50min |
| 3.A | 17.01.2024 | Sathana | Wörter Speicherung  | 45min |
| 4.A | 24.01.2024 | Sathana | Änderungsfunktion | 45 min |
| 5.A | 17.01.2024 | Sathana | Lösch-Funktion | 50 min |
| 6.A | 14.01.2024 | Sathana | ID anzeigen | 40min |
| 7.A | 14.01.2024 | Sathana | Datenbank | 45 min
      
Total: 7


## 3 Entscheiden

Ich habe mich entschieden den Quiz im Visual Studio in C# zu implementieren.


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 17.01.2024 | Sathana | 50min | 2 x 45 min |
| 3.A  | 24.01.2024 | Sathana | 45min | 2 x 45min |
| 4.A  | 24.01.2024 | Sathana | 45min | 50 min |
| 5.A  | 14.02.2024 | Sathana | 50min | 50min |
| 6.A  | 14.02.2024 | Sathana | 40 min | 45min |
| 7.A  | 14.02.2024 | Sathana | 45min | 30 min |


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 14.02.2024 | - | Sathana |
| 1.2  | 14.02.2024 | - | Sathana |
| 4.1  | 14.02.2024 | - | Sathana |
| 4.2  | 14.02.2024 | - | Sathana |
| 7.1  | 14.02.2024 | - | Sathana |
| 8.1  | 14.02.2024 | - | Sathana |
| 5.1  | 14.02.2024 | - | Sathana |
| 7.2  | 14.02.2024 | - | Sathana |


Das Spiel wurde auf einem HP Windows 11 Pro getestet. Ab und zu mal hat der Ton bei fehlerhaften Eingaben nicht abgespielt. Ansonsten funktioniert alles einwandfrei.

