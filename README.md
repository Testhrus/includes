# Was ist das hier?

Dies ist das gemeinsame Stammverzeichnis für alle meine mit Latex geschriebenen Fangeschichten.
Die einzelnen Dateien legen das Aussehen der Dokumente fest.

Es gibt im jeweiligen Geschichten-Repository Befehle, um das Aussehen zu beeinflussen.

Standardmäßig werden die Dokumente im DIN A5-Format mit 3mm Beschnitt (Zugabe) erzeugt. 
Das heißt, das Papierformat ist 154x216mm.

Die mit * gekennzeichneten Optionen sind Standard.

- Ausgabeformate sind aktuell DINA5*, Wissenschaft (17mmx24mm) und DINA4.

- Den Rand kann auf 3mm Beschnitt*, 3mm Beschnitt mit sichtbaren Grenzen und ohne Beschnitt eingestellt werden.

- Schriftarten im Dokument kann man auf Libertinus*, Libertine und BaselBook setzen.

- Die Schriftgröße ist standardmäßig auf 12pt festgelegt (Die Latexklasse kann auch noch 11pt und 10pt)

- Als Extra-Ausgabe kann man auf der Übersichtsseite noch angeben, bei welchem Anbieter man das Dokument als Buch gedruckt hat.

- Als letzte Option legt man das Hogwartslogo fest standard*, grau, farbig

```
pageborder      = >cutting3mm<, visibleborder, none
papertype       = >dina5<, dina4, science
fonttype        = >libertinus<, libertine, basel
hpfontsize      = 12pt
printingcompany = >epubli<, 1buch, podbuchdruck
hogwartslogo    = >standard<, color, gray
```

# Wie kompiliere ich?

Diese Repo ist nicht zum kompilieren gedacht. Es wird entweder als Subrepository in eine Geschichte eingebunden, oder per Pfadangabe, 
wenn man mehrere Geschichten hat, die das selbe Layout haben, welches sich aber je Geschichte ändert.

Die einzelnen Geschichten können mit Luatex kompiliert werden (Pdftex und Xetex wurden nicht getestet).
