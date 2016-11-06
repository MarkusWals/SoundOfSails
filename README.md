# Sound of Sails
Künstliche Intelligenz kennt man bisher aus den Medien als eine fortschrittliche Technologie,die vorrangig bei Autonom fahrende Autos, intelligenten Smart Home Anwendungen oder personalisierter Werbung angewendet wird. Deshalb haben wir uns im Rahmen des Coding Da Vinci-Events zur Aufgabe genommen, das zu ändern, und mit den bereit gestellten Kultur-Metadaten- neue Kunst zu schaffen. Die Musik.

Die gestellten Schiffsporträts vom Altonaer Museum werden in Ort, Zeichnungstechnik, Epoche untersucht. Zusätzlich wird ein intelligenter Algorithmus angewendet um die Bilder zu analysieren. Auf Grundlage dieser gewonnenen Daten wird unsere Applikation Musik generieren. Die Parameter des Musikgenerators sind unter anderem Tempo der Musik, Harmonieabfolge und Anzahl & Art der Musikinstrumente. Der Musikgenerator funktioniert über Midi Befehle, die von einer DAW-software abgegeben werden. Unter einer DAW versteht man eine Software, die quasi wie ein Musikstudio jedoch im Digitalformat funktioniert.Sie wird zur Professionellen Produktion von Digitaler Musik verwendet. Die Midi- Befehle werden mittels Metadaten der Schiffsporträts erstellt. Der Musik Generator lernt über eingebettete Midi-Music-Samples zu komponieren. Die komplexen Regeln der Harmonielehre und Melodieführung werden eingehalten um hörbare tonale Musik zu produzieren ( Das Phänomen von Jazz Harmoniken wird verwendet ).

Das Konzept bietet den Besuchern des Altonaer Museums ein erhöhtes Kulturerlebnis, in dem es die bestehenden Schiffsdaten mit der von uns programmierten Musikstücke in ein visuelles-audio Porträt verwandelt. In unserem Prototypen nutzen wir einen Rasperry Pi mit Touchscreen als unseren User Interface, der das Bild analysiert und Musik generiert.

Ähnlich wie ein Theaterpianist,der in den Goldenen Zwanzigern Kinofilme untermalt hat, ist unsere Vision mit Hilfe von künstlicher Intelligenz eine smarte Musikuntermalung für Bild und Film zu schaffen.

Das passionierte Team besteht aus Musikliebhabern und Programmierern: Markus Wals, Tungi Dang, Boris Crismancich


##Überblick:

![Sound of Sails](https://scontent-vie1-1.xx.fbcdn.net/v/t35.0-12/14975800_10208041071441421_70397208_o.jpg?oh=eff3e53040e79d041c1e34db6bac182d&oe=5822471F "Gesamtkunstwerk")

###Bilder
* Die Schiffsporträt-Sammlung im Altonaer Museum und deren Metadaten im xml Format https://www.dropbox.com/sh/c005ttp0va3zlpf/AACi04xncV2tBZefuRhHmngXa?dl=0
* Über 1000 Bilder als Trainings Daten für die Image Classifier der Visual Recocnition Api in Bluemix https://www.dropbox.com/sh/dt296dwafg47pd8/AAAqFLy_4CzsqDwpMJVZpVREa?dl=0

![Schiffsporträt (Altonaer Museum)](https://codingdavinci.de/img/daten/AB05260-edit.jpg "Schiffsporträt (Altonaer Museum)")

###Musik
* Audio Files die verschiedene Emotionen repräsentieren, später sollen hier Midi Patterns anstelle der Audio Daten verwendetet werden https://www.dropbox.com/sh/sqxcfngy33si90k/AADxZzWofXARNCv97R2WWEU5a?dl=0

###Hardware
* Raspberry Pi
* Touch Display 7"
* Lautsprecher
* Internet Verindung

###Software
* NodeJS
* Node-Red
* node-red-node-watson
* node-red-node-daemon

###IBM Bluemix
* Visual Recognition Service - Bildanalyse
* Alchemy Api - Metadatenanalyse


##Ausblick:
* Aus den Ergebnissen der Bild und Metadatenanalyse werden Midi Noten generiert werden (neuer Node) und diese als virtuelles Midi Instrument an Apple Logic oder Ableton Live angeschlossen werden. Somit kann die Applikation auch in der Cloud laufen und über das Internet Midi Patterns zu beliebigen PC's und Klangerzeugern streamen. 
** http://www.tobias-erichsen.de/software/rtpmidi.html
** http://nerds.de/en/loopbe1.html
* Erzeugen weiterer Classifier und weiteres Training 
* Das vorerst hardgecodete Mapping wird weiter an die Classifier angepasst


##Contribute
Das Projekt lebt von Beiträgen aus der Open Source Community, wir suchen Entwickler und Musikbegeisterte um das Projekt weiterzuentwickeln. 

####Kontakt:
Markus Wals https://www.facebook.com/markus.wals.9,
Tungi Dang https://www.facebook.com/tungi.haeids.mondaeis?fref=ts, 
Boris Crismancich https://www.facebook.com/boris.crismancich?fref=ts

