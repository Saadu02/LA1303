# LA1303

Name: Sathana Suganthasri

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 06.10.2023 | 0.0.1     | Projekt fertig erstellt.|
| 06.10.2023 | 0.0.2     | Dokumentation fertig erstellt.|


## 1 Informieren

### 1.1 Ihr Projekt

In meinem Projekt geht es darum, dass man Noten eingeben kann und später wird den Durchschnitt angezeigt mit Bewertung. 

### 1.2 Anforderung

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 | muss | Funktion | Man muss Zahlen/Noten eingeben können. |
| 2 | muss | Qualität | Das Programm soll in C# geschrieben werden.|
| 3 | muss | Funktion | Nach jeder Eingabe sollte der Notendurchschnitt angezeigt werden. |
| 4 | muss | Funktion | Die Fehlermeldungen sollen abgefangen werden.|
| 5 | muss | Funktion | Man kann nur Zahlen von 1 bis 6 eingeben können.|
| 6 | muss | Funktion | Am Anfang sollte eine Begrüßung vorhanden sein.|
| 7 | muss | Funktion | Am Ende sollte eine Bewertung angezeigt werden, die angibt, ob die Noten sehr gut, gut, genügend oder ungenügend sind.|
| 8 | muss | Qualität | Die Anzeige der Bewertungen sollte entsprechende Farben entsprechend den Ergebnissen haben.|
| 9 | muss | Qualität | Ein Ton muss abgespielt werden bei einer falschen Eingabe. |



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1 | Programm startet: Geben Sie Ihre Note ein: | 6 | Ihr neuer Notenschnitt ist 6. Möchten sie weitere Noten eingeben? y oder n | 
| 1.2 | Möchten sie weitere Noten eingeben y oder n? | y | Geben sie Ihre Note ein: |
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
| 1.A | 05.10.2023 | Sathana | Eingabe Noten Speicherung | 40min |
| 1.B | 05.10.2023 | Sathana | Durchschnitt Speicherung  | 30min |
| 4.A | 05.10.2023 | Sathana | Fehlermeldung abfangen | 30 min|         
| 7.A | 05.10.2023 | Sathana | Noten-Skala | 20 min |
| 8.A | 05.10.2023 | Sathana | Farbe | 15 min|
| 5.A | 05.10.2023 | Sathana | Zahl zwischen 1 bis 6 | 25 min |
| 7.B | 05.10.2023 | Sathana | Ergebnisse anzeigen| 15 min |
| 8.A | 05.10.2023 | Sathana | Ton abspielen | 20 min |


Total: 7


## 3 Entscheiden

Ich habe mich entschieden den Notenschnittrechner im Visual Studio in C# zu implementieren.


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 05.10.2023 | Sathana | 40min | 35min |
| 1.B  | 05.10.2023 | Sathana | 30min | 20min |
| 4.A  | 05.10.2023 | Sathana | 30min | 40min |
| 7.A  | 05.10.2023 | Sathana | 20min | 20min|
| 8.A  | 05.10.2023 | Sathana | 15min | 10min |
| 5.A  | 05.10.2023 | Sathana | 25min | 25min |
| 7.B  | 05.10.2023 | Sathana | 15min | 15min |
| 8.A  | 05.10.2023 | Sathana | 20min | 15min |


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 06.10.2023 | OK | Sathana |
| 1.2  | 06.10.2023 | OK | Sathana |
| 4.1  | 06.10.2023 | OK | Sathana |
| 4.2  | 06.10.2023 | OK| Sathana |
| 7.1  | 06.10.2023 | OK | Sathana |
| 8.1  | 06.10.2023 | OK | Sathana |
| 5.1  | 06.10.2023 | OK | Sathana |
| 7.2  | 06.10.2023 | OK | Sathana |
| 8.1  | 06.10.2023 | OK | Sathana |

Das Spiel wurde auf einem HP Windows 11 Pro getestet. Ab und zu mal hat der Ton bei fehlerhaften Eingaben nicht abgespielt. Ansonsten funktioniert alles einwandfrei.

