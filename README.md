Automatoetry - Haikus mit Mensch und Maschine
=============================================

Dieses Programm ist Open Source und steht unter der Gnu Public License (GPL v2). Der Code ist frei kopierbar, darf unter keiner anderen Lizenz weiterverwendet werden, yadda yadda yadda.

Die Idee
--------

Automatoetry ist der Versuch, aus dem Zusammenspiel von computerisiertem Ausprobieren und dem menschlichen Sinn für Schönheit heraus Poesie zu erschaffen. Ob es klappt? Ich habe keine Ahnung.

Das Medium der Wahl sind Haikus, eine japanische Gedichtform, die aus drei Zeilen mit 5, 7 und 5 Silben besteht.

Wie geht's?
-----------

Im Herzen von Automatoetry liegt ein genetischer Algorithmus, der Haikus erzeugt und zufällig mutieren lässt. Die hervorgebrachten Kind-Haikus ähneln ihrem Elter, sind aber nicht identisch; sie können sich in Details unterscheiden oder zur Gänze.

Aufgabe des Benutzers ist es, aus den vorgeschlagenen Kind-Gedichten das schönere herauszusuchen. Von diesem werden neue Kinder erzeugt, der Nutzer wählt wieder aus und so weiter. Ein Ziel gibt es nicht. Es geht ums Experimentieren und um den Spaß an der Sprache.

Idealerweise kommt nach vielen Generationen ein "schönes", also mehr oder weniger künstlerisches Haiku heraus. In der Galerie sind einige der Ergebnisse von Automatoetry gesammelt.

Wo kann ich es ausprobieren?
----------------------------

Eine aktuelle Version des Programms steht hier bereit: http://haiku.tobias-radloff.de (gehostet von Openshift)

Technische Details
------------------

**Abhängigkeiten**

* Python 2.6
* web.py 0.37
* libleipzig 1.3
* MySQL-python 1.2.3
* python-markdown 2

**Weitere Quellen**

* Automatoetry nutzt die API von http://wortschatz.uni-leipzig.de
* Zufallswort-Generator: http://wordreference.com/random/deen
* Der deutsche Stoppwort-Corpus entstammt dem NLTK 2.0 (http://nltk.org)
* jQuery 1.10.1


Von wem ist Automatoetry?
-------------------------

Autor: Tobias Radloff (http://www.tobias-radloff.de/)

E-Mail: mail [at] tobias-radloff [Punkt] de
