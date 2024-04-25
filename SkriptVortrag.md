# Skript

## Einleitung

Guten Tag und vielen Dank, dass Sie heute hier sind. Mein Name ist [Dein Name] und gemeinsam mit meinem herausragenden Team freue ich mich, Ihnen die Fortschritte und Hürden auf unserem Weg durch das zweite Release unseres Projekts "Convenient Community" zu präsentieren. 

Lassen Sie uns mit einer kleinen Begebenheit beginnen, die unseren Arbeitsprozess veranschaulicht: Stellen Sie sich eine Gruppe von Bergsteigern vor, die sich auf den Weg zum Gipfel machen. Jeder bringt unterschiedliche Fähigkeiten und Ausrüstung mit. Anfangs ist der Pfad steinig und jeder Schritt erfordert vollen Einsatz. Doch mit jedem Meter, den die Gruppe aufsteigt, verbessert sich ihre Technik, sie passen sich an das Terrain an und lernen, einander zu vertrauen und zu unterstützen.

Genau wie diese Bergsteiger, stießen auch wir auf unseren ersten 'Gipfeln' – User Stories des ersten Releases – auf Schwierigkeiten. Wir hatten mit neuen und unbekannten Technologien zu kämpfen, die unsere Koordination und Zusammenarbeit auf die Probe stellten. Aber mit jedem Problem, das wir gemeinsam lösten, wuchsen wir über uns hinaus, verbesserten unsere Fähigkeiten und unsere Zusammenarbeit.

Heute sind wir hier, um Ihnen zu zeigen, wie diese Erfahrungen uns stärker gemacht haben und wie sie in das zweite Release eingeflossen sind. Wir werden Ihnen nicht nur die technischen Aspekte unserer Arbeit vorstellen, sondern auch die Prozesse und Entscheidungen, die uns hierher gebracht haben.

Begleiten Sie uns auf dieser Reise, auf der jedes abgeschlossene Sprint und jede implementierte User Story ein weiterer Schritt nach oben ist, auf dem Weg zum Gipfel eines nahtlosen, benutzerzentrierten Produkts.

Fragen bitte am Ende!

## Hauptteil

### Einführung in Release 2

#### RELEASES

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

#### BURNDOWN CHARTS

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

#### HERAUSFORDERUNG SPRINT 2

Eine weitere Herausforderung, die sich in den Retrospektiven gezeigt hat, ist das Zeitmanagement. Das Bedeutet für uns zum einen, dass einige Aufgaben länger gedauert hatten, als aufgrund ihrer Story Punkte anzunehmen war. Hieraus ist ein Action Item entstanden: Im Sprint Planning beim Erstellen der konkreten Tasks schätzen wir als Team gemeinsam die Zeit, die wir hierfür glauben zu benötigen und vermerken diesen auf Jira als Kommentar. Damit können wir uns in Diskussion und den Abgleich und am Sprint Ende vergleichen, sodass wir unsere Schätzungen in Zukunft verbessern können.

#### HERAUSFORDERUNG SPRINT 3

In Sprint drei haben wir in der Retrospektive bemerkt, dass die meisten User Stories erst relativ spät in der finalen Deployment Umgebung erprobt wurden, weshalb wir auch via Action Item festgelegt habe, dass eine User Story spätestens 7 Tage nach beginn mit dem PO in eine erste Review gehen soll. Hierdurch wird eine frühere Erprobung gewährleistet, sodass mögliche Probleme schnell erkannt werden.

### Technische Herausforderungen und Lösungen

#### SPRINT 2 DEPLOYMENT AUF DER WEBSITE

Für einen möglichst kurzen und einfachen Deployment Prozess haben wir bereits von beginn an eine Lösung zur automatisierten Auslieferung der Software geplant und implementiert. Die technischen Details des Prozesses kann ich nach der Präsentation auf Wunsch gerne erläutern, aber im Grunde wird eine gespeicherte und freigegebene Änderung auf dem Haupt-Branch der Anwendung vollautomatisiert gebaut, getestet und danach auf die Server-Instanzen ausgeliefert. Damit sind Änderungen in circa 10 Minuten live, was den Entwicklern Zeit spart, die in Features und Bug-Fixes investiert werden kann und dem Kunden Geld.

#### SPRINT 3 MOBILES DEPLOYMENT

Wie bei den meisten Gruppen war die größte Herausforderung des Releases, dass die Anwendung Tag der Präsentation auf mobilen Endgeräten funktionieren muss. Alle bestehenden Funktionen musste in der Umgebung überprüft werden. Hierbei fällt einem dann auf, dass das Layout überarbeitet werden muss oder eine Funktion auf dem Desktop ausgeführt wird, auf dem Smart Phone aber nichts passiert. Vor allem der Chat-Bereich sowie die Benachrichtigungs-Funktionen haben am Ende von Sprint 3 viel Zeit gekostet.

Zwar hatten wir durch unser Self-Hosting einige Annehmlichkeiten wie beispielweise der Verzicht auf einen VPN für das Erreichen der Seite, wodurch auch das automatisierte Ausliefern ermöglicht wird. Jedoch hatten wir auch Probleme, da wir im ersten Setup auf einem Raspberry Pi bei Christopher daheim eine geringe Bandbreite hatten, sodass die Applikation lange Ladezeiten hatte.

Danach haben wir Azure Cloudservices mit dem studentischen Gratis-Volumen ausprobiert, was jedoch auch nicht die erforderliche Performanz hatte.

Am Ende haben wir uns Entschieden, es auf meinem Server zu hosten, da dieser momentan sowieso keine Auslastung erfährt und nach kurzer Erprobung das beste Performanz-Verhalten zeigte.

### User Stories mit Live Demo

#### Als Anbieter will Fotos und Beschreibung zu meinen Anzeigen hinzufügen, um potenzielle Interessenten anzusprechen

Die Beschreibung hatten wir bei der Implementierung der Anzeigen direkt schon mit implementiert, sodass noch der Teil mit dem Hochladen der Fotos übrig geblieben ist. Ich zeige jetzt, wie ich eine bestehende Anzeige mit einem Bild um eine persönliche Note erweitern kann.

1. App öffnen, Nutzer bereits angemeldet
2. Auf Anzeigen klicken
3. eigene Anzeige suchen
4. Anzeige anklicken, zur Detailansich wechseln
5. Auf Foto Klicken, Dateimanager öffnet sich
6. Foto auswählen und hochladen
7. Foto ist in Detailansicht zu sehen
8. fertig

#### Als Interessent will ich Anbieter kontaktieren können

Hier haben wir uns angeschaut, wie andere Applikationen diese Funktion implementieren. Die Wahl fiel relativ schnell auf einen modernen Ansatz mit einem Chat-Bereich, sodass Echtzeitkommunikation möglich ist im Gegensatz zu einem mail-ähnlichen System.

1. App öffnen, Nutzer bereits angemeldet
2. Auf Anzeigen klicken, zur ANzeigenübersicht
3. fremde Anzeigen anklicken, zur Detailansicht wechseln
4. Eric Empfängt Nachricht, Benachrichtigungen?
5. Antwort der Nachricht Empfangen
6. Backspace auf die Chats
7. fertig

#### Als Interessent möchte ich in App Benachrichtigungen erhalten, wenn es Anfragen von Interessenten für meine Anzeige gibt

*ÜBERLEITUNG AN ERIC* Wurde indirekt gezeigt, aber mein Kollege wird Ihnen die später noch einmal Benachrichtigungs-Funktion als Teil des dritten Sprintes, da wir versuchen, die Komponenten wiederverwendbar zu designen und zu implementieren.

Kommen wir zu den Stories aus Sprint 3

(welche stories?)

1. Anmelden/Registrieren (muss)
2. Nutzer Bewerten/Bewertungen ansehen (gut)
3. Benachrichtigungen (gut)
4. Anzeigen markieren (nur wenn zeit übrig)
5. Anzeige als nicht mehr verfügbar(nur wenn zeit übrig) !!!Könnte sehr Zeitintensiv sein
6. Registrierung aufheben (nur wenn zeit übrig)(würde sich gut am Ende anbieten)

*STORY 1 FOLIE*

#### Als Nutzer*in möchte ich mich An- und Abmelden. War gleichzeitig die Story mit der höchsten Priorisierung und mit den meisten Storypoints des dritten Sprints

die hohe prioriserung kommt vorallem dadurch, dass viele weitere Stories in den kommenden Sprints auf den Funktionen die diese Story liefert aufbauen.

Ich führ euch das ganze einmal vor

*ZUR SMARTPHONE ANSICHT WECHSELN*

1. zeigen das wenn nicht angemeldet fehlen sachen im Menü, man kann nicht bewerten, keine anzeigen erstellen, keine eigenen anzeigen sehen
2. registrieren wählen + account erstellen
3. zeigen das funktionen da sind
4. abmelden?
5. wieder mit selbem erstelleten account anmelden

*STORY 2 FOLIE*

#### Als nächstes haben wir einen Funktion zur abgabe von bewertung an Nutzern implementiert. Dazu gehört auch noch eine zweite Story zum Anzeigen der Bewertungen die ein Nutzer erhalten hat, um zum Beipiel die vertrauenswürdigkeit des Nutzers festzustellen

ZUR SMARTPHONE ANSICHT WECHSELN>

1. sollte noch angemeldet sein
2. Bewertung an user schreiben + abschicken
3. auf detailed anzeige oder userwahl gehen
4. bewertungssterne zeigen

#### Als Nutzer möchte ich Benachrichtigungen erhalten, um Anzeigen in meiner Nähe nicht zu verpassen

*STORY 3 FOLIE*

Im folgenden haben wir eine Funktion implementiert welche einem Benachrichtigungen mithilfe der Benachrichtigungsfunktion des Webbrowsers sendet, wenn eine neue Anzeige veröffentlicht wird oder man eine Nachricht erhält.

*ZUR SMARTPHONE ANSICHT WECHSELN*

1. sollte immer noch angemeldet sein
2. Zweites Telefon
3. Nachrichtenfunktion sollte schon gezeigt sein
4. Zweites Telefon schick Nachricht an Vorführ Telefon
5. Beten das Firefox nicht diesen macht

### Ausblick auf Release 3

*FOLIE MIT RELEASEPLAN NOCHMAL ZEIGEN*

Der nächste Release beinhaltet 4 weitere Sprints in denen die Epics Nutzerprofil, Lokalität und Verwaltung behandelt werden. Viele der Userstories aus diesem Release basieren auf den Ergebnissen aus dem
zweiten Release, darunter zum Beispiel die einrichtung des eigenen Nutzerprofils oder die ein klick Anmeldung, die beide auf dem Login und Registrierungssystem basieren.

## Schluss

*FOLIE MIT ZUSAMMENFASSUNG*

Während wir uns dem Ende unserer Präsentation nähern, erinnere ich mich an die Geschichte der Bergsteiger, mit der wir begonnen haben. Wie sie haben auch wir eine beträchtliche Strecke zurückgelegt. Jeder Sprint war ein weiterer Schritt auf unserem Weg, und wie die Bergsteiger, die den Gipfel erreichen, können wir nun auf eine Landschaft voller erreichter Ziele zurückblicken.

Die technischen und organisatorischen Herausforderungen, die wir Ihnen heute präsentiert haben, waren unsere steilen Hänge und herausfordernden Pfade. Aber genau wie unsere Bergsteiger haben wir uns angepasst, unsere Werkzeuge geschärft und unsere Teamdynamik gestärkt.

Wir möchten Ihnen danken, dass Sie Teil unserer Expedition waren und uns durch diesen Teil unserer Reise begleitet haben. Das nächste Camp liegt bereits vor uns – das dritte Release. Wir sind zuversichtlich, dass die bisherigen Erfahrungen, die wir gesammelt haben, uns dabei helfen werden, die kommenden Herausforderungen mit Bravour zu meistern.

Zum Abschluss noch eine persönliche Anmerkung: Diese Reise wäre nicht möglich gewesen ohne die Hingabe jedes einzelnen Teammitglieds, das seine Expertise und Leidenschaft eingebracht hat. Wir sind mehr als nur eine Gruppe von Entwicklerinnen und Entwicklern – wir sind ein Team, das gemeinsam wächst, sich gegenseitig unterstützt und zusammen den Gipfel erreichen wird.

Vielen Dank für Ihre Aufmerksamkeit, und wir freuen uns auf die Fragen, die Sie vielleicht für uns haben.
