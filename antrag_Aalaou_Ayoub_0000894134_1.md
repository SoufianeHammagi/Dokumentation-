# Antrag Aalaou Ayoub (from PDF)

Betriebliche Projektarbeit

Prüfungsteilnehmer/-in:

Ausbildungsbetrieb:

Ayoub Aalaou
Ansbacher Str. 38
28215 Bremen

ePhilos
Aktiengesellschaft
Fahrenheitstr. 7
28359 Bremen

E-Mail:
aalaou.ayoub97@gmail.com

Identnummer:
0000894134
Prüflingsnummer: 40092
Vorschlag:
Beruf:
Prüfungstermin:
Prüfungsart:

contact@ePhilos.de

Ausbilder/in bzw. Projektbetreuer/in
Lars Leising
l.leising@ephilos.de

1
Fachinformatiker Fachrichtung: Anwendungsentwicklung
Sommer 2025
50 - Abschlussprüfung / Abschlussprüfung Teil 2

1 Projektantrag*
[bearbeitet am 21.01.2025 um 11:34 Uhr]
Implementierung End-To-End Testing im ComfortMarket.
1.1 Kurzform der Aufgabenstellung*
[bearbeitet am 21.01.2025 um 11:34 Uhr]
Die Einführung von End-to-End-Tests soll die Qualität und Zuverlässigkeit der ComfortMarket
steigern. Ziel ist es, die Testautomatisierung zu implementieren.
1.2 Ist-Analyse*
[bearbeitet am 21.01.2025 um 11:35 Uhr]
Die Softwarefamilie ComfortMarket bietet Lösungen zur Digitalisierung von
Beschaffungsprozessen an. Diese modulare, prozessorientierte Software unterstützt sowohl
Großkunden als auch mittelständische Unternehmen und führt zu schnellen und nachhaltigen
Erfolgen im Einkauf.
Aktuell liegt der Fokus im ComfortMarket auf Unit-Testing für das Frontend und Backend, um die
Qualität einzelner Funktionen oder Methoden in Isolation zu gewährleisten und Fehler frühzeitig zu
erkennen.
Jedoch decken sie nicht das Zusammenspiel verschiedener Module oder Schichten des Systems
ab. Das bedeutet, dass Unit-Tests keine Integrationsprobleme aufdecken können.

2. Zielsetzung entwickeln / Soll-Konzept***

2.1 Was soll am Ende des Projektes erreicht sein?* [bearbeitet am 21.01.2025 um 11:35 Uhr]
Ziel des Projekts ist es, eine Infrastruktur zu schaffen, mit der ComfortMarket umfassend durch
End-to-End-Tests geprüft werden kann. Dabei werden die wesentlichen Benutzeroberflächen
sowie die Interaktionen zwischen den verschiedenen Systemkomponenten getestet. Einzelne
Tests, wie beispielsweise der Login-Prozess, die Registrierung oder der Kaufprozess, werden
durchgespielt, um sicherzustellen, dass diese kritischen Szenarien reibungslos funktionieren.
Im Rahmen der Designphase wird das am besten geeignetes Testtool ausgewählt, das den
Anforderungen der Projektumgebung entspricht.
Das Projekt soll Grundlagen schaffen, mögliche Fehlerquellen zu identifizieren und die
Benutzererfahrung sowie die Systemstabilität zu optimieren. Durch diese Tests wird sichergestellt,
dass ein spezifisches Szenario oder ein spezifischer Prozess korrekt interagiert, bevor der
Prozess in einer realen Umgebung eingesetzt wird.
2.2 Welche Anforderungen müssen erfüllt sein?* [bearbeitet am 21.01.2025 um 11:36 Uhr]
•
Ein Testsystem für ComfortMarket muss eingerichtet werden, dass die Möglichkeit bietet,
Tests zu schreiben, welche einzelne Szenarien abdecken können.
• Eine Test-Datenbank muss bereitgestellt werden, die die sichere Speicherung und den Zugriff
auf Testdaten ermöglicht.
•
Das Projektsetup muss so gestaltet sein, dass es mit beiden Oberflächen-Versionen von
ComfortMarket kompatibel ist und nahtlos funktioniert.
• Test-Szenarien müssen erstellt und dokumentiert werden, um alle kritischen Anwendungsfälle
abzudecken.
•
Realistische Testdaten müssen für verschiedene Szenarien bereitgestellt werden,
einschließlich fehlerhafter und gültiger Eingaben, um die Systemstabilität zu gewährleisten.
2.3 Welche Einschränkungen müssen berücksichtigt werden?*
[bearbeitet am 21.01.2025
um 11:36 Uhr]
Die Integration von End-to-End-Tests muss mehrere Einschränkungen berücksichtigen. Dazu
gehören Sicherheitsaspekte, wie der Schutz sensibler Daten während der Testdurchführung und
die potenziellen Schwachstellen in den verwendeten Automatisierungstools. Zudem erfordert die
Projektumgebung eine präzise Konfiguration, da Unterschiede zwischen Entwicklungs-, Stagingund Produktionsumgebungen die Testergebnisse beeinflussen können. Die Kompatibilität mit
Programmiersprachen. Außerdem müssen die von ComfortMartket unterstützten Browser
berücksichtigt werden.
3. Projektstrukturplan entwickeln***

3.1 Was ist zur Erfüllung der Zielsetzung erforderlich?* [bearbeitet am 21.01.2025 um 11:37

Uhr]
Das Projekt wird agil entwickelt. In kurzen Iterationen wird regelmäßig mit dem Fachbereich
abgestimmt, um Feedback zu sammeln. Dieses ermöglicht es dem Entwickler, schnell auf
Änderungen zu reagieren und so Zeit zu sparen.
Die Versionierung des Projekts erfolgt über SVN, und alle Schritte werden in einem Ticketsystem
erfasst und dokumentiert. Dies sorgt für eine lückenlose Nachvollziehbarkeit und transparente
Kommunikation der Fortschritte und Aufgaben.
3.2 Hauptaufgaben auflisten*
• Analyse
• Entwurf
• Implementierung
• Abnahme
• Dokumentation

[bearbeitet am 21.01.2025 um 11:37 Uhr]

3.3 Teilaufgaben auflisten*
[bearbeitet am 21.01.2025 um 13:26 Uhr]
Analyse
• Durchführung der Ist-Analyse
• Ermittlung der Anforderungen
• Identifikation der relevanten Testumgebungen und Systeme.
Entwurf
• Erstellung von spezifischen Diagrammen
• Festlegung der Testdaten
• Auswahl geeigneter Tools und Frameworks für End-To-End-Tests
Implementierung
•
Einrichtung einer zentralen Konfiguration zur Vermeidung von Wiederholungen und
Sicherstellung, dass die Tests modular und wiederverwendbar sind.
• Einrichtung der Testumgebungen und Testtools
• Erstellung der Testskripte basierend auf den definierten Testfällen
Abnahme
• Durchführung der Tests und Dokumentation der Ergebnisse
• Validierung der Testergebnisse mit den Senior Entwicklern
• Behebung von Fehlern und Verbesserung von Prozessen
• Sicherstellung, dass die Testergebnisse nachvollziehbar und reproduzierbar sind
Dokumentation
• Erstellung der Projektdokumentation
• Erstellung eines Berichts über die durchgeführten Tests.
• Erfassung von Implementierungsdetails und Anpassungen.
3.4 Grafische oder tabellarische Darstellung*
Sehe Anhang.

[bearbeitet am 21.01.2025 um 11:46 Uhr]

4. Projektphasen mit Zeitplanung in Stunden*
1. Analyse (6 Stunden)
2. Entwurf (13 Stunden)
3. Implementierung (43 Stunden)
4. Abnahme (7 Stunden)
5. Dokumentation (8 Stunden)
Gesamtzeit: 77 Stunden

[bearbeitet am 21.01.2025 um 13:29 Uhr]

Legende * = Pflichtfeld, ** = Freitext, *** = keine Eingabe erforderlich

