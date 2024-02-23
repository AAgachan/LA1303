# Projekt-Dokumentation

Agachan Atputharasa, Simon Veljkovic

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|19.01.24| 0.0.1|  Wir haben unser Projekt begonnen (Planung). |
|26.01.24| 0.1.0|  Wir haben mit der Implementation begonnen. |
|02.02.24| 0.5.0|  Wir haben unseren Code vervollständigt. |
|23.02.24| 1.0.0|  Wir haben unseren Portfolioeintrag geschrieben, die Dokumentation vervollständigt und das Projekt beendet. |                                                          

## 1 Informieren

### 1.1 Ihr Projekt

In diesem Projekt geht es um die Implementierung von Cäsarverschlüsselungsverfahren in C#

In diesem Projekt streben wir die Implementierung des Cäsarverschlüsselungsverfahrens in C# an. Ziel ist es, eine Funktion zu entwickeln, die eine Zeichenkette mithilfe des Cäsarverfahrens verschlüsselt und entschlüsselt. Durch dieses Projekt hoffen wir, unser Verständnis für grundlegende Verschlüsselungstechniken zu vertiefen, insbesondere im Kontext von C#-Programmierung.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 | Muss| Funktional  | Als Benutzer möchte ich eine C#-Funktion haben, die eine Zeichenkette mit dem Cäsarverschlüsselungsverfahren verschlüsseln kann, um meine Daten zu schützen. |
| 2 | Muss | Funktional  | Als Benutzer möchte ich die Möglichkeit haben, den Verschiebewert (Schlüssel) für die Cäsarverschlüsselung anzupassen, um die Flexibilität der Verschlüsselung zu erhöhen. |
| 3 | Muss | Funktional  | Als Benutzer möchte ich eine Funktion haben, die eine verschlüsselte Zeichenkette entschlüsseln kann, um meine ursprünglichen Daten wiederherzustellen. |
| 4 | Kann | Rand| Als Entwickler möchte ich geeignete Tests implementieren, um sicherzustellen, dass die Cäsarverschlüsselungsfunktion korrekt und zuverlässig arbeitet. |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm gestartet, Do you want to Encrypt [1], Decrypt [2], or Exit [3]?, 1, Enter a number between 1 and 25 to shift the encrypted Text: 2, Please enter the text:              |    a     |  Encrypted text: c                 |
| 2.1  | Programm gestartet,Do you want to Encrypt [1], Decrypt [2], or Exit [3]?, 1, Enter a number between 1 and 25 to shift the encrypted Text:             |  2       |  Please enter the text: ... Encrypted text:...                 |
| 3.1  | Programm gestartet,Do you want to Encrypt [1], Decrypt [2], or Exit [3]?             |  2       |    Decrypted text 1:...               |
| 4.1  | Programm gestartet            |    -     |    3 Bestanden               |



### 1.4 Diagramme
![LA 1303](https://github.com/AAgachan/LA1303/assets/110893260/8cb86c54-1927-4d9c-8407-148992555063)



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 02.02.2024      | Agachan          |  Erstellt das Cäsarverschlüsselungsverfahren          |   90'            |
| 2.A  | 02.02.2024      | Simon          | Erstellt den Verschiebewert für das Cäsarverschlüsselungsverfahren             | 60'              |
| 3.A  | 02.02.2024      | Agachan          | Erstellt das Cäsarentschlüsselungsverfahren             | 60'              |
| 4.A  | 02.02.2024      | Simon          |  Erstellt Unittest            |   90'            |

Total: 300'



## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 26.01.24      | Agachan          | 90'              |   80'                |
| 2.A  | 26.01.24      | Simon          |  60'             |     70'              |
| 3.A  | 02.02.24      | Agachan          | 60'              |   80'                |
| 4.A  | 02.02.24      | Simon          |   90'            |     90'              |
  


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 23.02.24      | OK         | Agachan       |
| 2.1  | 23.02.24      | OK         | Agachan       |
| 3.1  | 23.02.24      | OK         | Agachan       |
| 4.1  | 23.02.24      | OK       | Agachan       |


Alle Testfälle haben funktionier.
