# ISMS Cockpit | D-Cyber Compliance

Webanwendung von D-Cyber Compliance (D-Services GmbH) zur Steuerung eines Informationssicherheitsmanagementsystems nach **ISO/IEC 27001:2022** und des Zertifizierungszyklus nach **ISO/IEC 17021-1**.

## Module

| Modul | Inhalt | Normbezug |
|---|---|---|
| Dashboard | Umsetzungsgrad, nächstes Audit, offene Findings, Risikomatrix, Handlungsbedarf | Kap. 9.1 |
| Mandant und Scope | Geltungsbereich, Zertifizierungsstelle, Zertifikatsdaten | Kap. 4.3 |
| Normkapitel 4 bis 10 | Anforderungen und erwartete dokumentierte Information | Kap. 4 bis 10 |
| SoA und Controls | 93 Controls, Anwendbarkeit, Begründung, Umsetzungsstatus, CSV-Export | Kap. 6.1.3 d |
| Dokumentenlenkung | Register mit Version, Status, Prüffristen, Erkennung doppelter Nummern | Kap. 7.5 |
| Risiken | Inhärentes und Restrisiko, Behandlungsoption, Controls | Kap. 6.1.2, 8.2, 8.3 |
| Nachweise | Evidence je Control mit Ablaufdatum, Abdeckungsanalyse | Kap. 7.5.3 |
| Audits und Findings | Stage 1, Stage 2, Überwachung, Rezertifizierung, interne Audits, Korrekturmaßnahmen | Kap. 9.2, 10.2 |

## Datenschutz und Vertraulichkeit

- Die Anwendung ist eine statische Seite ohne Server und ohne Tracking. Daten werden ausschließlich im Browser (localStorage) gehalten.
- **Mandantendaten werden nie in dieses Repository eingecheckt.** Der Austausch erfolgt über verschlüsselte Exportdateien (`.dcc`, AES-GCM 256, Schlüsselableitung PBKDF2-SHA-256 mit 310.000 Iterationen), abgelegt beim Mandanten (z. B. SharePoint).
- Der enthaltene Demo-Mandant „Muster GmbH“ ist vollständig fiktiv.
- Einzige externe Ressource: Google Fonts (Ubuntu). Für einen vollständig DSGVO-konformen Betrieb die Schrift lokal einbinden.

## Betrieb

Statische Datei `index.html`, lauffähig über GitHub Pages oder jeden Webserver.

## Hinweis zu Normtexten

Die Control-Titel sind sinngemäße Kurzbezeichnungen. Der Normtext der ISO/IEC 27001:2022 ist urheberrechtlich geschützt und nicht enthalten.

© D-Services GmbH · D-Cyber Compliance · Stuttgart
