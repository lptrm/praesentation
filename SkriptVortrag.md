# Skript

## Einleitung

## Hauptteil

### Einführung in Release 2

--RELEASES--

*RELEASEPLAN BILD ZEIGEN*

Release 1

umfasste 1 Sprint

| Priority | Type  | ID           | Description                                                                                     | Assigned To      | Status |
|----------|-------|--------------|-------------------------------------------------------------------------------------------------|------------------|--------|
| Highest  | Story | LABSWPCC-8   | Als Anbieter möchte ich Anzeigen erstellen, um Produkte anzubieten.                             | Jan Obernberger  | DONE   |
| Highest  | Story | LABSWPCC-16  | Als Interessent möchte ich spezifisch nach Inseraten schauen.                                   | Jan Obernberger  | DONE   |
| High     | Story | LABSWPCC-12  | Als Anbieter möchte ich Inhalt und Titel der Anzeigen bearbeiten.                               | Jan Obernberger  | DONE   |
| High     | Story | LABSWPCC-14  | Als Anbieter möchte ich sehen, was ich alles wann online gestellt habe, um einen Überblick zu behalten. | Jan Obernberger  | DONE   |

Wurde am 28.03 erfolgreich released und war im Zeitplan

Die User Stories des ersten Releases umfassten sich hauptsächlich mit dem erstellen der Anzeigen.

Mit diesem Release wurden die Basisfunktionen der Anwendung bereitgestellt auf denen die Nachfolgenden Stories aufbauen konnten.

Mit dem zweiten Release lag der Fokus auf der Registrierung und Anmeldung der Nutzer*innen sowie auch die Nutzerinteraktion mit zum Beipiel der Bewertungsfunktion. Neben diesen Funktionen wurden aber auch noch weitere Stories zu den Anzeigen implementiert. Dazu aber gleich mehr wenn wir zur Vorstellung der einzelnen User-Stories kommen.

*BURNDOWN CHARTS*

*ERSTES BURNDOWN CHART BILD ZEIGEN*

Hier sieht man unseren Burndown chart vom ersten Sprint. Hier lässt sich noch ein eher nicht so guter Verlauf erkennen, da die Kurve erst kurz vor knapp, am Tag des eigentlichen Releases 1 und Sprintende zu abrupt sinken beginnt. Dies lag vorallem an der einführung in viele neue und unbekannte Techniken

*ZWEITES BURNDOWN CHART BILD ZEIGEN*

Wenn man sich jetzt aber den Burndown chart vom zweiten Sprint anschaut kann man sehen, wie sich der Verlauf der Kurve schon leicht verbessert hat im Verleich zum vorherigen Sprint

*DRITTES BURNDOWN CHART BILD ZEIGEN*

Beim dritten Sprint lassen sich deutliche Verbesserungen sehen, die Kurve fällt viel gleichmäßiger als davor ab und es werden nichtmehr alle Issues erst am Ende abgehakt
Wenn man sich hier den linken Rand des Burndown charts ansieht, lässt sich ein kleiner Unglück dadurch passiert ist, dass Stories versehentlich zu früh abgehakt wurden obwohl sich noch nicht fertig implementiert waren. Wie wir dieses Problem gelöst haben erzählt euch jetzt Jan.

*ÜBERLEITUNG ZU JAN* (mal noch fragen ob die so gut ist)

### Organisatorische Herausforderungen und Lösungen

*ÜBERLEITUNG* (danke Eric)

Um das Problem zu lösen, haben wir uns mit Jira auseinandergesetzt und erfahren, dass es möglich ist, das Active Sprint Board mit entsprechenden Berechtigungen anzupassen. Wir baten Herr Ballein, den Administrator, eine weitere Spalte neben den bestehenden "ToDo" "In Progress" und "Done" mit der Bezeichnung "In Review" zu ergänzen. Das stellt sicher, dass die Tasks nicht mehr versehentlich von den Mitgliedern beendet werden.

*HERAUSFORDERUNG SPRINT 2*

Eine weitere Herausforderung, die sich in den Retrospektiven gezeigt hat, ist das Zeitmanagement. Das Bedeutet für uns zum einen, dass einige Aufgaben länger gedauert hatten, als aufgrund ihrer Story Punkte anzunehmen war. Hieraus ist ein Action Item entstanden: Im Sprint Planning beim Erstellen der konkreten Tasks schätzen wir als Team gemeinsam die Zeit, die wir hierfür glauben zu benötigen und vermerken diesen auf Jira als Kommentar. Damit können wir uns in Diskussion und den Abgleich und am Sprint Ende vergleichen, sodass wir unsere Schätzungen in Zukunft verbessern können.

*HERAUSFORDERUNG SPRINT 3*

In Sprint drei haben wir in der Retrospektive bemerkt, dass die meisten User Stories erst relativ spät in der finalen Deployment Umgebung erprobt wurden, weshalb wir auch via Action Item festgelegt habe, dass eine User Story spätestens 7 Tage nach beginn mit dem PO in eine erste Review gehen soll. Hierdurch wird eine frühere Erprobung gewährleistet, sodass mögliche Probleme schnell erkannt werden.

### Technische Herausforderungen und Lösungen

*SPRINT 2 DEPLOYMENT AUF DER WEBISTE*

Für einen möglichst kurzen und einfachen Deployment Prozess haben wir bereits von beginn an eine Lösung zur automatisierten Auslieferung der Software geplant und implementiert. Die technischen Details des Prozesses kann ich nach der Präsentation auf Wunsch gerne erläutern, aber im Grunde wird eine gespeicherte und freigegebene Änderung auf dem Haupt-Branch der Anwendung vollautomatisiert gebaut, getestet und danach auf die Server-Instanzen ausgeliefert. Damit sind Änderungen in circa 10 Minuten live, was den Entwicklern Zeit spart, die in Features und Bug-Fixes investiert werden kann und dem Kunden Geld.

*SPRINT 3 MOBILES DEPLOYMENT*

Wie bei den meisten Gruppen war die größte Herausforderung des Releases, dass die Anwendung Tag der Präsentation auf mobilen Endgeräten funktionieren muss. Alle bestehenden Funktionen musste in der Umgebung überprüft werden. Hierbei fällt einem dann auf, dass das Layout überarbeitet werden muss oder eine Funktion auf dem Desktop ausgeführt wird, auf dem Smart Phone aber nichts passiert.


### User Stories mit Live Demo

### Ausblick auf Release 3

## Schluss