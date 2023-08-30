# Projekt-Dokumentation


Bischof Gabriel

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|  16.08.2023 | - | An diesem Tag habe ich mich wieder mit C# auseinander gesetzt und die Planung erstellt. |
|  23.08.2023 | 0.0.1 | Ich habe angefangen mit dem Programm und konnte den grössten Teil erledigen. |
|  30.08.2023 | 1.0.0 | Mein Programm wurde fertiggestellt und auf Fehler getestet. |



## 1 Informieren

### 1.1 Ihr Projekt

In diesem Projekt arbeite ich an einem Number Guesser welches die jeweiligen Versuche der Eingaben zählt.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 | Muss  | Funktional | Als ein Spieler möchte ich dass mir eine Zufällige Zahl von 1-100 generiert wird, damit ich sie erraten kann. |
| 2 | Muss  | Funktional | Als ein Spieler möchte ich eine Zahl eingeben, damit ich die Zahl erraten kann.|
| 3 | Muss  | Funktional | Als ein Spieler möchte ich wissen ob die Zahl niedriger oder höher als die eingeben Zahl ist, damit ich weiss ob ich höher oder niedriger schätzen muss.|
| 4 | Muss  | Funktional | Als ein Spieler möchte ich wissen ob die Zahl erraten worden ist, damit ich weiss das es die richtige Zahl ist.|
| 5 | Muss  | Qualität   | Als ein Spieler möchte ich wissen wie viele Versuche ich gebraucht habe, damit ich mich verbessern kann.|
| 6 | Muss  | Qualität   | Als ein Spieler möchte ich darauf hingewiesen werden ob ich ein Fehler bei der Eingabe gemacht habe, damit Fehler im Programm vermieden werden können.|
| 7 | Kann | Rand | Als ein Spieler möchte ich in einer Liste alle meine Versuche aufgeschrieben haben, damit ich herausfinden kann welcher mein bester Versuch war.|


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Eingabe von Zahl | 12  |  Zahl ist zu niedrig/hoch. |
| 1.2  | Eingabe von Zahl  | d  |  Falsche Eingabe: Geben sie eine Zahl ein.|
| 1.3  | Eingabe von Zahl | 12 |  Die Zahl 12 ist die richtige Zahl.|
| 2.1  | Richtige Zahl wurde eingegeben. | 12 | Du hast 4 Versuche gebraucht.|
| 3.1  | Falsche Eingabe | Erereg | Falsche Eingabe: Geben sie eine Zahl ein.|
| 4.1  | Willst du weiter spielen | n | Liste wird erstellt mit Versuchen. |


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 23.08  | Gabriel Bischof  | Generieren von Random Zahl | 10 Min. |
| 2.A  | 23.08  | Gabriel Bischof  | Eingabe von Zahl (Variabeln definieren)  |  15 Min. |
| 3.A  | 23.08  | Gabriel Bischof  | Erstellen von Angaben ob zu tief oder zu hoch gerraten worden ist.  |  60 Min. |
| 4.A  | 23.08  | Gabriel Bischof  | Erstellen von der Überprüfung ob die Zahl richtig erraten worden ist.  |  15 Min. |
| 5.A  | 23.08  | Gabriel Bischof  | Zählen der Versuche und sie dem Spieler wiedergeben  |  25 Min. |
| 6.A  | 23.08  | Gabriel Bischof  | Fehlereingaben abfangen. |  10 Min. |
| 7.A  | 23.08  | Gabriel Bischof  | Erstellen einer Liste mit den Anzahl versuchen. |  45 Min. |






Total: 180 min



## 3 Entscheiden

Ich bleibe bei meinen aktuellen Plan und versuche die Anforderungen umzusetzen.


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A | 23.08 | Gabriel Bischof | 10  min  |   5 min  |
| 2.A  | 23.08 | Gabriel Bischof |  15 min |   5 min  |
| 3.A  | 23.08 | Gabriel Bischof |  60 min |   70 min  |
| 4.A  | 23.08 | Gabriel Bischof |  15 min |   15 min  |
| 5.A  | 23.08 | Gabriel Bischof |  15 min |   15 min  |
| 6.A  | 23.08 | Gabriel Bischof |  10 min |   5 min  |
| 7.A  | 23.08 | Gabriel Bischof |  45 min |   60 min  |



## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | 
| ---- | ----- | -------- |
| 1.1  | 30.08 | OK       |        
| 1.2  | 30.08 | OK       | 
| 1.3  | 30.08 | OK       |        
| 2.1  | 30.08 | OK       | 
| 3.1  | 30.08 | OK       |        
| 4.1  | 30.08 | OK       | 



Alle Test sind positiv verlaufen. Ich habe keine Fehler beim Testen entdeckt.


