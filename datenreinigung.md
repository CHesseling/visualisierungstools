# Tools zur Datenreinigung

## Excel

### Vorgehen

1) Daten herunterladen, in Excel öffnen
2) Rechtsklick auf Tabellenreiter > „Verschieben/Kopieren“ > Kopie erstellen
3) Ansicht -> Fenster fixieren -> Fixierung aufheben
4) Alles markieren (Dreieck oben links zwischen 1 und A) -> Unter dem Ribbon „Start“ auf den Radiergummi „Löschen“ -> Formate Löschen
5) Unnötige Zeilen und Spalten löschen
6) Stimmen die Spaltenköpfe?
7) Formeln anwenden
8) „Formulierte“ Daten in neues Tabellenblatt sichern (Inhalte einfügen > Werte und Formatierungen)
9) Evtl unter neuen Name als CSV Datei speichern

### CSV
CSV Dateien in Excel importieren: https://support.microsoft.com/de-de/office/importieren-oder-exportieren-von-textdateien-txt-oder-csv-5250ac4c-663c-47ce-937b-339e391393ba



### Formeln und Funktionen

=Summe(A1+B1)
Summe von 2 Zellen

=Summe (A1:D17)
Summe von einem Zahlenbereich

=C2/$D$2
Das $-Zeichen fixiert eine Zelle. Beispiel: Wenn sich alle Berechnungen auf EINEN Basiswert beziehen sollen

=A1*1000
Zelle A1 mit 1000 multiplizieren

=A1/10
Zelle A1 durch 10 dividieren

=A1/100*19
Beispiel für die Berechnung der Mehrwersteuer

=(A1/A2*100)-100
Beispiel für Berechnung einer Veränderung in Prozent

=Anzahl(A1:D1)
Gibt die Anzahl einer Spalten

=Mittelwert()
Arithmetisches Mittel

=Median()
Medianwert errechnen (der Wert in der Mitte)

=Modus.einf()
Moduswert errechnen (häufigster Wert)

=Glätten
Entfernt u.a. Leerzeichen vorne und hinten

=Verketten(A1;” “;A2)
Zellen A1 und A2 verketten, mit Leerzeichen dazwischen

=Wert

Übersetzt Textformat in Zahlenformat

=Text
Übersetzt Zahlenformat in Textformat

SVERWEIS
Die Syntax des Befehls ist: SVERWEIS(Suchkriterium;Matrix;Spaltenindex;Bereich_Verweis)
- Suchkriterium: Ist der Begriff / Wert nach dem gesucht werden soll. Gesucht wird immer in der ersten Spalte der Matrix.
- Matrix: Ist der Listenbereich in dem nach dem Begriff gesucht wird
- Spaltenindex: Ist die Spalte aus der der Wert zurückgegeben wird
- Bereich_Verweis: Logischer Wert (WAHR, FALSCH) der angibt, ob eine ungefähre oder genaue Entsprechnug gesucht wird. (Genau = FALSCH)

Bis zum Ende markieren: Strg+Shift+Pfeil unten/rechts
AutoFill: Doppelklick auf das kleine Quadrat unten rechts
Zusammengefasste Spalten trennen: Daten-> Text in Spalten
Zellen Formatieren: z.B. > Zahl > 1000er Trennzeichen und Negative Werte rot

## OpenRefine
Clean Messy Data

https://openrefine.org/download

Umfangreiches Tutorial: https://libjohn.github.io/openrefine/

Reconciliation 
https://openrefine.org/docs/manual/reconciling
Beispiel: https://fdmlab.landesarchiv-bw.de/workshop/openrefine-einsteiger/06-reconciling-mit-gnd/

https://reconciliation-api.github.io/testbench/#/

## Tabula
Tabellen aus PDFs extrahieren
Download: tabula.technology
Web (Achtung, alles öffentlich): tabula.ondata.it/





