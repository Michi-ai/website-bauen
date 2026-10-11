# Technische Entwicklung und EU-Regulierung

Stand: 11.10.2026. Quelle: Websuche. Benchmarks sind Forschungsergebnisse von Instituten, meist nicht peer-reviewed.
**Relevanz:** A = Kernfolie, B = Hintergrund, C = nur bei Nachfrage.

---

## 1. Wie schnell werden Agenten besser? METR „Time Horizon“ (Relevanz A)

- Paper: *Measuring AI Ability to Complete Long Tasks* (METR, März 2025), arXiv 2503.14499: https://arxiv.org/html/2503.14499v1
- **Maß:** Länge von Aufgaben (gemessen an der Dauer für Fachleute), die ein Agent mit 50 % Erfolgswahrscheinlichkeit löst.
- **Trend:** Verdoppelung etwa alle 7 Monate seit 2019, laut späteren Analysen zuletzt schneller.
- **Verlauf (laut Sekundärquellen, auf metr.org prüfen):**
  - Claude 3.7 Sonnet (Anfang 2025): rund 50 Minuten
  - Claude Opus 4.5: knapp 5 Stunden (laut Anthropic-Bericht vom Februar 2026)
  - Claude Opus 4.6 (Februar 2026): rund 12 Stunden
  - Claude Mythos Preview (März 2026): rund 16 bis 17 Stunden, **Konfidenzintervall sehr breit (rund 8 bis 55 Stunden).** METR sagt selbst, Werte über 16 Stunden sind mit dem aktuellen Aufgabenset unzuverlässig.
- **Wichtige Einschränkung:** Bei **80 % Zuverlässigkeit** liegt der Horizont deutlich niedriger (für Mythos rund 3 Stunden). Unternehmen brauchen meist eher 80 % oder mehr als 50 %. METR betont: Ein 50-%-Horizont von X Stunden heißt **nicht**, dass man Aufgaben unter X Stunden delegieren kann (METR, Jänner 2026: https://metr.org/notes/2026-01-22-time-horizon-limitations/).
- Die Aufgaben stammen überwiegend aus Software und Forschung. Die Übertragbarkeit auf typische KMU-Tätigkeiten ist offen.
- MIT Technology Review nennt den Graphen „the most misunderstood graph in AI“ (05.02.2026): https://www.technologyreview.com/2026/02/05/1132254/this-is-the-most-misunderstood-graph-in-ai/

## 2. Realistische Arbeitsumgebungen (Relevanz B)

- **TheAgentCompany** (Carnegie Mellon), arXiv 2412.14161: https://arxiv.org/pdf/2412.14161. Simulierte Softwarefirma. Bestes Modell (Stand 2025) erledigte rund 30 % der Aufgaben vollständig. Typische Fehler: komplexe Weboberflächen, Kommunikation mit Kollegen, mühsame Mehrdokument-Aufgaben. **Zahlen inzwischen durch neuere Modelle vermutlich überholt.**
- **Zuverlässigkeit im Unternehmenseinsatz:** Siehe `01-wissenschaftliche-literatur/agenten-produktivitaet-kundenservice-governance.md`, Abschnitt B (z. B. Leistungsabfall von 60 % auf 25 % bei Konsistenz über 8 Läufe; Preprints).

## 3. EU AI Act: aktueller Zeitplan (Relevanz A)

**Korrektur gegenüber dem ersten Rechercheschritt:** Der „Digital Omnibus“ ist inzwischen **in Kraft**.

- **Rechtsakt:** Verordnung (EU) 2026/1744 zur Änderung der KI-Verordnung (EU) 2024/1689. Parlament 16.06.2026, Rat 29.06.2026, Veröffentlichung im Amtsblatt 24.07.2026, **in Kraft seit 27.07.2026** (laut Kanzleiberichten; Nummer und Daten auf EUR-Lex prüfen).
- **Hochrisiko-Systeme nach Anhang III** (z. B. Personalauswahl, Kreditwürdigkeit, Zugang zu Leistungen): verschoben auf **2. Dezember 2027.**
- **Hochrisiko-KI in regulierten Produkten (Anhang I):** verschoben auf **2. August 2028.**
- **Transparenzpflichten (Art. 50)** gelten weitgehend **seit 2. August 2026**, also z. B. die Pflicht, offenzulegen, dass man mit einer KI interagiert. Nur die maschinenlesbare Kennzeichnung (Art. 50 Abs. 2) hat für bereits vermarktete Systeme eine Schonfrist bis 2. Dezember 2026.
- **Bereits seit 2025 gelten:** Verbote (Art. 5) und die Pflicht zur **KI-Kompetenz** der Beschäftigten (Art. 4). *(aus dem ursprünglichen Zeitplan der KI-Verordnung, nicht neu geprüft)*
- **Neu:** Verbot von KI für nicht-einvernehmliche intime Bilder und Missbrauchsdarstellungen, ab 2. Dezember 2026.
- **Agenten im AI Act:** Der AI Act kennt keine eigene Kategorie „Agent“. Die Pflichten hängen vom **Einsatzzweck** ab. Ein Kundenservice-Agent fällt meist unter Transparenzpflichten, ein Agent für Personalauswahl unter Hochrisiko. Keine Rechtsberatung, im Zweifel juristisch prüfen.

Quellen:
- Orrick (07/2026): https://www.orrick.com/en/Insights/2026/07/EU-AI-Act-Update-Digital-Omnibus-Finalizes-8-Compliance-Changes
- Jones Walker: https://www.joneswalker.com/en/insights/blogs/ai-law-blog/yes-august-2-still-matters-the-eu-approved-a-high-risk-ai-delay-but-most-trans.html
- Gibson Dunn: https://www.gibsondunn.com/eu-ai-act-omnibus-agreement-postponed-high-risk-deadlines-and-other-key-changes/
- DLA Piper: https://knowledge.dlapiper.com/dlapiperknowledge/globalemploymentlatestdevelopments/2026/The-Digital-AI-Omnibus-Proposed-deferral-of-high-risk-AI-obligations-under-the-AI-Act

## 4. Marktprognosen

Gartner und McKinsey sind nach `02-studien-und-arbeitsmarkt/` verschoben.
