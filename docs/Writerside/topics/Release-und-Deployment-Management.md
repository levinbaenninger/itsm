# Release- und Deployment-Management

Der Prozess **Release and Deployment Management** ist verantwortlich für den Aufbau, die Tests, das Deployment und die erste Unterstützung neuer oder geänderter Services. Ziel ist es, Services gemäss des Service Designs zu liefern, die die Anforderungen der Stakeholder erfüllen und die gewünschten Ziele erreichen.

## Hauptziele und Zweck

1. **Planung und Koordination:**
    - **Abstimmung:** Abstimmung der Release- und Deployment-Pläne mit Kunden und Stakeholdern unter Berücksichtigung der Business-Interessen.
    - **Release Units:** Definition und Verwaltung von Release Units, also den Teilen des Services, die gemeinsam ausgerollt werden.

2. **Qualitätssicherung:**
    - **Kompatibilität:** Sicherstellung, dass das Release Package aus kompatiblen Komponenten besteht.
    - **Dokumentation im CMS:** Vollständige Dokumentation des Release Packages und dessen Komponenten im Configuration Management System (CMS).

3. **Test und Implementierung:**
    - **Tests:** Aufbau und Tests des Service gemäss Service Design.
    - **Backout Plan:** Sicherstellung der Durchführbarkeit des Backout-Plans, falls die Implementierung fehlschlägt.

4. **Erste Unterstützung:**
    - **Initiale Unterstützung:** Bereitstellung einer ersten Unterstützung nach dem Deployment, um den Übergang in den Betrieb zu erleichtern.

## Prozesse und Aktivitäten

1. **Release Planung:**
    - **Zeitliche Planung:** Berücksichtigung der zeitlichen Vorgaben aus dem Service Design Package.
    - **Release-Strategien:**
        - **Big Bang:** Ein neuer oder geänderter Service wird an alle Nutzer gleichzeitig verteilt.
        - **Phasenorientiert:** Der Service wird zuerst an eine Nutzergruppe und dann gemäss Rollout-Plan an weitere Nutzergruppen verteilt.

2. **Deployment-Strategien:**
    - **Pull-Ansatz:** Nutzer können den Zeitpunkt des Updates selbst wählen, oft genutzt bei nicht sicherheitsrelevanten Updates.
    - **Push-Ansatz:** Updates werden automatisch und sofort installiert, Nutzer können den Zeitpunkt nicht wählen.

3. **Zusammenstellung und Tests:**
    - **Kompatibilitätstests:** Sicherstellen, dass Software auf der vorhandenen Hardware läuft.
    - **Dokumentation:** Sorgfältige Dokumentation aller Schritte und Komponenten.

4. **Flexibilität und Anpassungsfähigkeit:**
    - **Organisatorische Änderungen:** Fähigkeit, auf Änderungen und neue Anforderungen während des Release- und Deployment-Prozesses flexibel zu reagieren.

## Herausforderungen und Lösungsansätze

1. **Minimierung von Auswirkungen:**
    - **Wertschöpfung:** Sicherstellen, dass der Kunde einen messbaren Wertbeitrag durch das Release erhält.
    - **Minimale Störungen:** Reduzierung der Auswirkungen auf die laufenden Services und Support.

2. **Akzeptanz schaffen:**
    - **Dokumentation und Training:** Bereitstellung ausreichender Dokumentation und Schulungen, um Akzeptanz bei Kunden und Anwendern zu fördern.
    - **Übergabeort:** Erste Anweisung und Unterstützung am Übergabeort nach dem Deployment.

3. **Mischformen bei der Verteilung:**
    - **Automatisierte und manuelle Ansätze:** Kombination aus automatischen und manuellen Ansätzen bei der Verteilung, je nach Anforderungen und Infrastruktur.

Der **Release and Deployment Management**-Prozess ist essenziell für den erfolgreichen Aufbau, die Tests und das Deployment neuer oder geänderter Services. Durch sorgfältige Planung, Koordination und Qualitätssicherung wird sichergestellt, dass Services den Anforderungen der Stakeholder entsprechen und einen Wertbeitrag liefern. Die Auswahl geeigneter Release- und Deployment-Strategien, wie Big Bang oder phasenorientierte Ansätze, und die Berücksichtigung von Pull- und Push-Strategien zur Verteilung gewährleisten eine effiziente und effektive Implementierung. Erfolgreiche Dokumentation und Schulungen tragen dazu bei, die Akzeptanz bei Anwendern und Kunden zu fördern und den Übergang in den Betrieb reibungslos zu gestalten.