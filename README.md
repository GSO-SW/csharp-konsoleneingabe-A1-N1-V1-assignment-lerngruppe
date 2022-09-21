<div id="container" style="white-space:nowrap">

  <div id="image" style="display:inline float: right;">
        <img style="float: left;" src="./AddFiles/C%23_logo.png" alt="drawing" width="8%"/>
  </div>

  <div id="texts" style="display:inline; white-space:nowrap; float: right;"> 
        <h1>C#-Grundlagen</h1>
        <h3>Arbeitsauftrag zur Konsoleneingabe und Konvertierung</h3>
</div>

## :dart: Zielsetzung

Dieser Auftrag hat folgende Ziele:

+ Einfache Programmierprobleme nutzen, um die Modul 1 behandelten Themen zu Vertiefen
+ Üben Informationen zu Recherchieren, die nicht explizit in der Aufgabenstellung genannt werden
+ Üben Sie das Erstellen, Klonen und Einreichen von Aufträgen über Visual Studio 2022 und GitHub

##  :school_satchel: Skills

+ Nutzung des Internets, um Informationen oder Formeln zu finden, die zur Lösung von Programmieraufgaben benötigt werden
+ Verwendung von Zuweisungs-Workflow-Schritten

## :bulb: Benötigtes Wissen
+ Konsoleneingabe erzeugen
+ Konsoleneingabe konvertieren und Variablen zuweisen

## :bookmark_tabs: Informationsquelle
Das Informationsmaterial zu Modul 1 finden Sie [hier](./AddFiles/SAS_Eingabe_Info.pdf)

## :white_check_mark: Aufgaben

### Akzeptieren und Klonen von Assignments

Um das Zuweisungs-Repository zu erstellen, verwenden Sie folgenen [link]().

### Allgemeine Schritte beim Schreiben von Programmen

Die meisten unserer Programme werden dem gleichen allgemeinen Ablauf folgen: Informationen vom Benutzer einlesen, Daten verarbeiten/berechnen, eine Ausgabe erzeugen. Eine Möglichkeit, Ihre Gedanken zu ordnen, besteht darin, **Kommentare zu schreiben**. Verwenden Sie diese als Gliederung für den Code, den Sie schreiben werden. Beginnen Sie mit der Erstellung von Abschnitten für jede der oben genannten Gruppen.

Für jedes Problem müssen Sie die nötigen Schritte zu Eingabe,Verarbeitung und Aufgabe identifizieren und sie in eine Reihenfolge bringen. Schreiben Sie die Schritte als Kommentar auf Deutsch in Ihren Code, bevor Sie programmieren. Wenn Sie das Programm sprachlich nicht umsetzen können, wissen Sie nicht genug, um den Code zu schreiben. 

Bevor Sie den Code schreiben, lesen Sie das Problem und ordnen Sie die Informationen den folgenden Kategorien zu. Tun Sie dies in Kommentaren in Ihrer Codedatei. 

1. **Eingabe** - welche Informationen werden vom Benutzer benötigt? Entwickeln Sie einige Beispieleingaben. Die Eingabefunktion gibt Informationen in Form einer Zeichenkette (Text) zurück. Wenn Sie nach einer Zahl fragen, vergessen Sie nicht, den Text in eine Zahl umzuwandeln, die in nachfolgenden Berechnungen verwendet werden kann. 

2. **Verarbeitung** (Berechnungen) - formeln aufschreiben. Wenden Sie die Beispieleingabewerte von Hand auf Ihre Formeln an, um sie auf ihre Richtigkeit zu überprüfen.

3. **Ausgabe**- was sind die gewünschten Ergebnisse? Liefern Ihre Berechnungen alles, was Sie brauchen? Wenn nicht, gehen Sie  wieder zu Punkt 2.

Erst wenn Sie herausgefunden haben, was Sie tun müssen, beginnen Sie mit dem Schreiben von Code. Beginnen Sie mit dem Abschnitt Eingaben. Schreiben Sie eine Anweisung, die einen Wert vom Benutzer erhält. Sie müssen Variablen erstellen, um die Informationen zu speichern. Verwenden Sie für diese Variablen beschreibende Namen. Geben Sie nach einer Konsoleneingabe den Wert der Eingabe durch eine Konsolenausgabe wieder aus. Führen Sie das Programm zum Testen aus, um sicherzustellen, dass Ihr Code funktioniert. Wenn ja, können Sie die Konsolenausgabe entfernen oder auskommentieren und mit dem nächsten Eingabewert fortfahren. Wenn nicht, müssen Sie Ihren Code korrigieren, bis er funktioniert. Setzen Sie diesen Code- und Testzyklus fort - schreiben Sie eine Zeile Code, dann testen Sie diese.

Sobald Sie alle Eingabewerte haben, fahren Sie mit dem Abschnitt Verarbeitung fort. Möglicherweise müssen Sie zusätzliche Variablen erstellen, um die berechneten Daten zu speichern. Geben Sie diese Berechnungen nach und nach aus. Stimmen sie mit den Handrechnungen überein, die Sie oben gemacht haben? Wenn nicht, korrigieren Sie Ihren Code, um die richtigen Ergebnisse zu erhalten.

Schließlich schreiben Sie die Konsolenausgabe, die die Ausgabe erzeugen. In einem ersten Durchgang geben Sie einfach die gewünschte Ausgabe ein. Gehen Sie dann zurück und fügen Sie die Formatierung hinzu. Um zum Beispiel die Ausgabe in einigen der Beispiele zu erzeugen, müssen Sie möglicherweise Tabulatorzeichen in Ihre Ausgabestrings einfügen.

---

### Aufgabe 1: Persönliche Daten

Lesen Sie die persönlichen Daten des Benutzers ein und speichern Sie diese in folgenden Variablen: 

    string vorname;
    string nachname;
    short alter;
    double groesse;
    bool erste_ps;
Gestalten Sie das Programm benutzerfreundlich.

> :information_source: **Hinweise**:exclamation:
> + Beachten Sie, dass Sie die Ausgabe unter der gestrichelten Linie erzeugen müssen; um die Aufgabe zu bestehen
> + Sie müssen die Formatierung im Beispiel genau befolgen, um den Unittest zu bestehen
> + Nutzen Sie Platzhalter um "Vorname:", "Nachname:", "Alter:", "Größe:" und "ProgErf" 10 Stellen Platz zu geben und linksbündig zu fixieren   

Beispiel 1 Ausgabe/Ergebnis:
![alt text](./AddFiles/Task1_example.jpg)

---
  
### Aufgabe 2: Arbeit einreichen

1. In Visual Studio 2022 das Fenster "Git-Änderungen" aufrufen
2. Eine kurze Beschreibung Ihrer Änderungen in die Textbox eingeben und "commit für alle" klicken
3. Mit dem Pfeil nach oben die Arbeit auf GitHub pushen.
4. Das Repository im Brower aufrufen und aktualisieren um die Änderungen zu bestätigen.
5. Im Pull-Request die Nachricht "Bereit zum Bewerten" hinterlassen, damit Ihre Lehrkraft weiss das Sie fertig sind.

---
  
# :100: Erfolgskriterien
  
+ Eingesetzten Quellcode kommentieren
+ Quellcode schreiben der lesbar ist und mit Hilfe einer logischen Folge das Problem löst
+ Programmausgabe die korrekt, lesbar und richtig formatiert ist 
