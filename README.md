# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

✍️ Ihr Gruppenname und Ihre Nachnamen
Gruppennamen: Such-Maschine
Mitglieder: Sathana Suganthasri, Nicola Luca.Karrer, Brandon Spaqi und Mohammad Shahir.Bashiri

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren
Man hat verschiedene Text-Dateien in verschiedenen Ordnern. Man kann nach diesen Dateien individuell suchen oder die Such-Option benutzen. Hier kann man dann einen Begriff eingeben, der dann alle Dateien anzeigt, die diesen Begriff haben. 
Dateien hineinfügen 
Ordner erstellen 
Titel für Ordner 
Dateien automatisch einordnen 
Begriff eingeben 
Dateien anzeigen 


### 1.1 Ihr Projekt

✍️ Beschreiben Sie Ihr Projekt in einem griffigen Satz.
Das Programm soll zeigen, wo unsere Dateien gespeichert sind.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |                 |      | Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️ |
| ...  |                 |      |                                    |

✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.


### 1.21 Anforderungsanalyse
| AA-№ | Typ | Anforderung  |
| ---- | ------------ | ------- |
|1|Funktional||Das Programm soll vom Benutzer die Dateinamen abfragen. |
|2|Funktional|Das Programm soll automatisch die Dateien ordnen.| 
|3|Funktional|Das Programm soll eine Suchoption zur Verfügung haben.|  
|4|Randbedingungen|Das Programm muss in C# geschrieben sein.|   
|5|Funktional|Das Programm soll ein Ergebnis zeigen.|   
|6|Qualität|Das Programm soll Anzahl Ergebnis zeigen.|      
|7|Qualität| Das Programm soll farbig aussehen.  |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |              |         |                   |
| ...  |              |         |                   |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

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

| AP-№ | Zuständig | Was | Datum | Erledigt|
| ---- | ----- | --------- | ------------ | ------------- |
|      |alle|dokumentation|              |               |
|      |Brandon|Design|              |               |
|      |Mohammand|Kontrollieren|              |               |
|      |alle|Informieren|              |               |
|      |Sathana|Auftragsanalyse|              |               |
|      |Sathana, Nicola|Vorstellung zeichnen|              |               |
|      |       |           |              |               |



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
| 1 |   x.10    |  x        |   Mohammad     |
| 2  |      x.10 |  x        |   Mohammad     |
| 3  |  x.10     |   x       |   Mohammad     |
| 4  | x.10      |    x      |        Mohammad|
| 5  |   x.10   |      x    |        Mohammad|
| 6  | x.10      |      x    |        Mohammad|
| 7  |  x.10     |      x    |        Mohammad|

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.

