# LA1302

Name: Sathana Suganthasri

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 14.02.2024 | 0.0.1     | Projekt fertig erstellt.|
| 14.01.2024 | 0.0.2     | Dokumentation fertig erstellt.|


## 1 Informieren

### 1.1 Ihr Projekt

In meinem Projekt geht es um ein Quiz, bei dem der Benutzer kann Fragen und Antworten schreiben, ändern, Löschen und anzeigen kann. 

### 1.2 Anforderung

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 | muss | Funktion | Der Benutzer muss Wörter einfügen können. |
| 2 | muss | Randbedingung | Das Programm soll in C# geschrieben werden.|
| 3 | muss | Funktion | Nach jedem einfügen des Wörters, müssen die Karten gespeichert werden(Datenbank). |
| 4 | muss | Funktion | Das Program soll eine Funktion zum Bearbeiten von Karteikarten haben, um Änderungen vorzunehmen. |
| 5 | muss | Funktion | Das Programm soll eine Löschfunktion für das Entfernen von Karteikarten haben. |
| 6 | muss | Funktion | Wenn ich eine ID eingebe, soll die entsprechende Karteikarte angezeigt werden. |
| 7 | muss | Funktion | Ich kann alle kärtchen auf einmal aubrufen, um alle anzeigen zu können. | 
| 8 | muss | Funktion | Wenn ich etwas Falsches eingebe, soll ein Error angezeigt werden. |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1 | Programm startet (POST-Methode)| { "frage": "Essen auf französisch?", "antwort": "manger" } | Code: 201 | 
| 3.1 | Programm startet (POST-Methode)| { "frage": "Der Name auf französisch?", "antwort": "le nom" } | Code : 201 | 
| 3.2 | Testfall 3.1 | (Get-Methode) mit entsprechenden Id klicken | Code : 200 { "frage": "Der Name auf französisch?", "antwort": "le nom" }|
| 4.1 | Programm startet (PUT-Methode)| id : (ID wählen) { "frage": "Essen auf französisch?", "antwort": "Repas" } | Code: 204 | 
| 5.1 | Programm startet (Delete-Methode)| id: (den gwünschten/existierte id wählen) | Code: 204 | 
| 6.1 | Programm startet (GET-Methode)| id: (den gewünschte/existerende id wählen) | Code: 204 | 
| 7.1 | Programm startet (GET)| (den Excute klicken) | Code: 200  (alle Kärtchen-Informationen werden angezeigt) | 
| 8.1 | Programm startet (GET-Methode)| id: (Id welches noch nicht existiert) | Code: Error 404, "Der Benutzer existiert nicht" | 
| 8.2 | Programm startet (PUT-Methode)| id: (id welches noch nicht existiert) | Code: Error 404, "Der Benutzer existiert nicht" |
| 8.3 | Programm startet (DELETE-Methode)| id: (ID welches noch nicht existiert) | Code: Error 404, "Der Benutzer existiert nicht" | 


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A | 17.01.2024 | Sathana | Wörter einfügen | 50 min |
| 3.A | 17.01.2024 | Sathana | Wörter Speicherung / Datenbank | 45 min |
| 4.A | 24.01.2024 | Sathana | Änderungsfunktion | 45 min |
| 5.A | 17.01.2024 | Sathana | Lösch-Funktion | 50 min |
| 6.A | 14.01.2024 | Sathana | ID anzeigen | 40 min |
| 7.A | 14.01.2024 | Sathana | ID/Datenbank | 45 min |
| 8.A | 14.01.2024 | Sathana | Error | 30 min|
      
Total: 7


## 3 Entscheiden

Ich habe mich entschieden, das Quiz in Visual Studio mit C# und ASP.NET Core-Web-API zu implementieren. 


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 17.01.2024 | Sathana | 50 min | 2 x 45 min |
| 3.A  | 24.01.2024 | Sathana | 45 min | 2 x 45min |
| 4.A  | 24.01.2024 | Sathana | 45 min | 50 min |
| 5.A  | 14.02.2024 | Sathana | 50 min | 50 min |
| 6.A  | 14.02.2024 | Sathana | 40 min | 45 min |
| 7.A  | 14.02.2024 | Sathana | 45 min | 30 min |
| 8.A  | 12.02.2024 | Sathana | 30 min | 15 min |


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 14.02.2024 | OK | Sathana |
| 3.1  | 14.02.2024 | OK | Sathana |
| 3.2  | 14.02.2024 | OK | Sathana |
| 4.1  | 14.02.2024 | OK | Sathana |
| 5.1  | 14.02.2024 | OK | Sathana |
| 6.1  | 14.02.2024 | OK | Sathana |
| 7.1  | 14.02.2024 | OK | Sathana |
| 8.1  | 14.02.2024 | OK | Sathana |
| 8.2  | 14.02.2024 | OK | Sathana |
| 8.3  | 14.02.2024 | OK | Sathana |


Dieses Quiz-Projekt wurde auf einem HP Windows 11 Pro getestet und alle Test wurden bestanden.
