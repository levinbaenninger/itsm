# Überblick

Anders als in den vorhergegangenen Phasen gibt es in der Phase **Service-Transition** eine logische Abfolge der Prozesse nacheinander. Man kann 
auch sagen, dass Service-Transition an sich einen einzelnen Prozess darstellt.

## Abfolge der Prozesse

![service-transition.png](service-transition.png) { thumbnail="true" width="600" }

Der **Auslöser** der **Service-Transition** ist stets eine oder mehrere <tooltip term="RFC">**RFC**</tooltip>**s**. Solch ein RFC kann durch mehrere Stakeholder 
gestellt werden. Es ist ein Änderungsantrag in einem IT-Projekt, bspw. ein komplett neuer Service oder ein neues Feature in einem bestehenden 
Prozess. Welche Änderungen genau nötig sind, leitet sich aus dem Service-Design-Package ab.

Der Prozess **Change-Management** hat die Aufgabe alle anstehenden Änderungen zu koordinieren und in manchen Fällen Entscheidungen zu treffen, z.B. ob 
eine Änderung überhaupt nötig ist oder nicht.

Bevor Änderungen durchgeführt werden, sind umfangreiche Tests nötig. Dafür sind zunächst die genauen Schritte der Einführung zu planen. Diese 
Aufgabe führt der Prozess **Service Transition Planning and Support** durch.

Um die Schritte genau planen zu können, ist es ausserdem erforderlich die aktuelle Konfiguration aller beteiligten Komponenten zu kennen. Diese 
formel genehmigte Konfiguration nennt man **Baseline**. Die Informationen bekommt man vom Prozess **Service Asset and Configuration Management**.

Nach der Planung und Bewertung des Ablaufs beginnt das **Release and Deployment Management** mit den Tests, bevor dann der Release freigegeben und 
schlussendlich verteilt wird.

Am Schluss wird noch ein Abschlussbericht, ein **Post-Implementation Review** erstellt.