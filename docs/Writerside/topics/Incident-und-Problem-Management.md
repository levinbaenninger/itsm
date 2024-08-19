# Incident und Problem Management

## Incident Management

Incident Management
:
Der Zweck vom Incident Management ist das Minimieren von negativen Auswirkungen von Incidents, indem der normale Servicebetrieb schnellstmöglich 
wiederhergestellt wird.

Verschiedene Incidents müssen angemessen behandelt werden; es gibt Incidents mit geringen Auswirkungen, Major Incidents, Security Incidence, etc. 
Für alle Arten sollen verschiedene Verfahren festgelegt werden.

Weiter muss ein Incident vorab priorisiert werden, z.B. in einem Service-Level-Agreement.

Idealerweise verknüpfen wir diese Incidents zu Configuration Items (CI), um mehr Informationen zu haben. Ein CI kann z.B. ein Drucker sein oder 
ein Laptop.

Zudem braucht man ein gutes Tool, um gleichartige Incidents zu erkennen, um zu erkennen, wo Häufungen auftreten, etc.

## Problem Management

Problem Management
:
Der Zweck vom Incident Management ist das Reduzieren der Eintrittswahrscheinlichkeit und der Auswirkung von Incidents durch die Identifizierung 
tatsächlicher und potenzieller Ursachen von Incidents und das Management von Workarounds und Known Errors.

````mermaid
graph TD;
    Problemidentifikation-->Problemsteuerung
    Problemsteuerung-->Fehlersteuerung
````

Aktivitäten zu obigen Schritten sind z.B.:

- Analyse von Trends
- das Erkennen von wiederauftretenden Incidents
- das Risiko für Major Incidents erkennen und Gegenmassnahmen entwickeln

Das führt dann hoffentlich zu einem Known Error für welchen man ersteinmal ein Workaround entwickelt und danach behebt man diesen Fehler.