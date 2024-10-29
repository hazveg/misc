# Prüfung Datenanalyse

- Methoden der Datengewinnung
- Fehler bei der Datengewinnung
- Grundbegriffe der Datenanalyse
- grafische Darstellung (Diagrammtypen erstellen können, Vor-Nachteile)
- Kennzahlen kennen und berechnen können, auch ohne höhere Hilfsmittel und mit Hilfsmitteln (TI-Nspire)
- Sowohl das Histogram wie das Boxplot muss auch ohne Hilfsmittel erstellt werden können.
- Aussagen zu Diagrammtypen ????

# Methoden der Datengewinnung

- Experimente
- Befragungen
- Beobachtungsstudien
- Sekundärstatistische Erhebung

# Fehler bei der Datengewinnung

- zufällige Fehler
- systematische Fehler
- Übertragungsfehler
- mutwillige Fehler

# Grundbegriffe der Datenanalyse

## Grundgesamtheit

Die Menge der für eine Untersuchung relevanten Personen oder Objekte

## Stichprobe

Eine Teilmenge der Grundgesamtheit

zufällige Auswahl -> **Zufallsstichprobe** / **randomisierte Stichprobe**

## Stichprobenumfang

Die Anzahl der in der Stichprobe untersuchten Personen oder Objekte

Anzahl = Grundgesamtheit -> **Vollerhebung**

## Bias

systematische Abweichung, welche bei einer nicht zufällig gezogenen Stichprobe auftritt.

## Repräsentativität

Eine Stichprobe ist dann *repräsentativ*, wenn sie ein unverzerrtes Abbild der Grundgesamtheit ist. d.h. für alle
Merkmale entspricht die Verteilung der Häufigkeiten in der Stichprobe jener in der Grundgesamtheit.

## Urliste

In der Urliste sind die ursprünglich erhaltenen Daten enthalten. Diese sind hierbei noch nicht weiter bearbeitet worden.

## Datensatz

Die zusammengefassten Daten einer Studie, egal ob von der Urliste oder nicht.

## Untersuchungseinheiten

Bei jeder Datengewinnung werden Daten pro einzelne Untersuchungseinheiten gesammelt. Jede Untersuchungseinheit erhält
in einer Tabelle eine eindeutige ID, welche in der ersten Spalte gespeichert wird.

## Merkmale / Variablen

An jeder Untersuchungseinheiten werden Daten für bestimmte Merkmale / Variablen erhoben.

```
1 Variable      ->      univariat
2 Variablen     ->      bivariat
>2 Variablen    ->      multivariat
```

## Wert / Ausprägung

Der Wert, der eine Variable in einer Untersuchungseinheit annimmt wird als "Ausprägung" bezeichnet.

## Beobachtung

Eine Beobachtung ist eine Untersuchungseinheit sowie den Ausprägungen in dessen Merkmalen.

## Variablentypen

![qualitativ/kategoriell { nominal, ordinal }, quantitiv/metrisch { diskret, stetig/kontinuierlich }](variablentypen_baum.png)

## geordnete Stichprobe und Rang

- nominal       ->  gleiche Ausprägungen nacheinander
- ordinal       ->  entsprechend der Ordnung der Merkmalsausprägungen
- quantitativ   ->  in Reihenfolge der Grösse der Ausprägungen

Bei sortierten Datensätzen macht es auch Sinn, den Untersuchungseinheiten einen Rang zu geben.
Falls hierbei die gleichen Daten auf mehreren Rängen kommen, gibt es zwei Vorgehensweisen:

1. Ränge einfach so belassen
2. Den Rang der mehrfachigen Ausprägung mitteln.

Bsp: Die diskrete Ausprägung 5 erscheint auf den Rängen 3, 4, 5.
Bei ungerader Anzahl nimmt man den mittleren Rang und setze diesen zum Wert 5.

1. 3
2. 4
4. 5
6. 7
7. 9
...

Bei gerader Anzahl nimmt man den Durchschnitt der mittleren zwei Rangwerte.

# grafische Darstellung

## absolute / relative Häufigkeit

![Definition der absoluten/relativen Häufigkeit, S. 379](häufigkeit.png)

## Säulen- und Balkendiagramme

Hierbei werden qualitative Merkmale dargestellt. Die Höhe der Säulen / die Breite der Balken werden durch die relative / absolute Häufigkeit hiervon bestimmt.
Säulen / Balken werden mit Zwischenräumen voneinander getrennt.

## Kreisdiagramm

Im Kreisdiagramm werden die relativen Häufigkeiten einer einzelnen Ausprägung mit Kreissektoren dargestellt.
Der Zentriwinkel hiervon ist proportional zum prozentualen Wert der Häufigkeit.

# Kennzahlen

Man nehme bei den Definitionen hier eine sortierte Liste von ganzen Zahlen an.

## Mittelwert

![Mittelwert Definition](mittelwert.png)

## Median

> "... 50% der Ausprägungen kleiner oder gleich und 50% der Ausprägungen grösser oder gleich ... sind."

![Median Definition](median.png)

## Minimum

Das *Minimum* `x_min` eines Merkmals einer Stichprobe ist die kleinste auftretende Ausprägung.

## Maximum

Das *Maximum* `x_max` eines Merkmals einer Stichprobe ist die grösste auftretende Ausprägung.

## unteres Quartil

> "... 25% der Ausprägungen kleiner oder gleich und 75% der Ausprägungen grösser oder gleich ... sind."

![unteres Quartil Definition](unteres_quartil.png)

## oberes Quartil

> "... 75% der Ausprägungen kleiner oder gleich und 25% der Ausprägungen grösser oder gleich ... sind."

![oberes Quartil Definition](oberes_quartil.png)

## Standardabweichung (*standard deviation*)

![Standardabweichung Definition](standardabweichung.png)

## Interquartilsabstand

![Interquartilsabstand Definition](interquartilsabstand.png)

## Spannweite

![Spannweite Definition](spannweite.png)

# Histogram

- Anzahl `k` von Klassen definieren, idealerweise im Bereich `5 - 20`; oder `sqrt(n)`, wobei `n` die Anzahl Datensätze ist.
- Klassengrenzen definieren, sie sollten alle dieselbe Breite haben.
- Absolute Häufigkeiten definieren (= Anzahl Beobachtungen pro Klasse).
- Die Höhe eines Rechtecks wird auf einem Histogram proportional zur absoluten Häufigkeit der Klasse gezeichnet.
- Die Grafik wird zum Schluss noch mit dem Inhalt und Kontext entsprechen beschriftet und bezeichnet.

# Boxplot

Grundsätzlich wird im Boxplot folgendes Format befolgt:

- Minimum
- unteres Quartil
- Median
- oberes Quartil
- Maximum

![Boxplot Definition](boxplot.png)

Zwischen `unteres Quartil` und `oberes Quartil` wird eine Box eingefärbt. Hierin sind 50% aller Datensätze enthalten.
Oberhalb und unterhalb der Box werden Antennen eingezeichnet. Diese sind beim `Minimum`/`Maximum` wenn die Distanz zwischen
dessen Wert unterhalb 1.5 * `Interquartilsabstand` liegt. Wenn nicht, wird es da eingezeichnet und der Wert - sowie weitere
Werte ausserhalb dieser Grenze - als Extremwerte aufgeführt.
