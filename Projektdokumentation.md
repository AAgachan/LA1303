# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

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

In diesem Projekt strebe ich die Implementierung des Cäsarverschlüsselungsverfahrens in C# an. Ziel ist es, eine Funktion zu entwickeln, die eine Zeichenkette mithilfe des Cäsaralgorithmus verschlüsselt und entschlüsselt. Durch dieses Projekt hoffe ich, mein Verständnis für grundlegende Verschlüsselungstechniken zu vertiefen, insbesondere im Kontext von C#-Programmierung.

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
| 1.1  | Programm gestartet,Do you want to Encrypt [1], Decrypt [2], or Exit [3]?, 1, Enter a number between 1 and 25 to shift the encrypted Text: 2, Please enter the text:              |    a     |  Encrypted text: c                 |
| 2.1  | Programm gestartet,Do you want to Encrypt [1], Decrypt [2], or Exit [3]?, 1, Enter a number between 1 and 25 to shift the encrypted Text:             |  2       |  Please enter the text: ... Encrypted text:...                 |
| 3.1  | Programm gestartet,Do you want to Encrypt [1], Decrypt [2], or Exit [3]?             |  2       |    Decrypted text 1:...               |
| 4.1  | Programm gestartet            |    -     |    3 Bestanden               |



### 1.4 Diagramme

✍️Fügen Sie hier ein Use Case-Diagramm mit mindestens 10 Anwendungsfällen ein; und einen PAP.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
