# Vortrag zum zahmen Symbol der Milnor-K-Theorie und Diskreten Bewertungsringen

Dies sind die Quellen zur Ausarbeitung zweier Vorträge über 
*Das zahme Symbol der Milnor-K-Theorie und diskrete Bewertungsringe*. 
Sie wurden im Rahmen des Seminars
[*Einführung in die Algebraische K-Theorie*](http://homepages.uni-regensburg.de/~stf58529/teaching/ktheory/Welcome.html)
für Bachelorstudenten der Mathematik, geleitet von Dr. Florian Strunk
und Dr. Morten Lüders,
im Sommersemester 2015 an der Universität Regensburg gehalten.
Die Hauptquelle ist *Algebraic K-theory and quadratic forms* von J. Milnor.

## Dateiübersicht
- Hauptdatei mit Inhalt: `k-theory_script.tex`
- LaTeX-Kofigurationen/-Definitionen: `k-theory_config.tex`
- Literatur: `k-theory.bib`

## Kompilieren
(Getestete) Systemvoraussetzungen: **TeXLive2016**-Distribution

Zum Kompilieren folgende Befehle in dieser Reihenfolge ausführen

```bash
pdflatex k-theory_script.tex
biber k-theory_script
pdflatex k-theory_script.tex
```
