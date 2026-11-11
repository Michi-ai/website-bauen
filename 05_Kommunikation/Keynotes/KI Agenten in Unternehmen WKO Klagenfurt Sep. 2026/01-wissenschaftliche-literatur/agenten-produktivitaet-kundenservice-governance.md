# Literatur (peer-reviewed bzw. wissenschaftliche Publikationen)

Stand der Recherche: 11.10.2026. Quellen: Consensus, SciSpace, Firecrawl (arXiv). Angaben zu Zitationszahlen stammen aus Consensus und sind Momentaufnahmen.
**Status:** Nur Titel, Autor/in, Jahr, Outlet und Abstract-Inhalt wurden geprüft. Volltexte wurden nicht gelesen. Vor dem Zitieren im Vortrag DOI/Seitenzahlen nachprüfen.

---

## A. Begriffe und Einordnung: Chatbot → KI-Agent → Agentic AI

| Quelle | Kernaussage (laut Abstract) | Nutzen für den Vortrag |
|---|---|---|
| Sapkota, R., Roumeliotis, K. I., Karkee, M. (2025): *AI Agents vs. Agentic AI: A Conceptual Taxonomy, Applications and Challenges.* Information Fusion. (Consensus: 582 Zitationen) | Trennt **AI Agents** (modulare, LLM-getriebene Systeme für Einzelaufgaben, z. B. Kundensupport, Terminplanung) von **Agentic AI** (Multi-Agenten-Kooperation, dynamische Aufgabenzerlegung, persistentes Gedächtnis, koordinierte Autonomie). Generative AI als Vorläufer. Nennt Halluzination, Brittleness, emergentes Verhalten und Koordinationsfehler als Probleme. | **Zentrale Begriffsfolie.** Liefert die wissenschaftliche Taxonomie für „Chatbot → Agent → Agentic AI“. |
| Dwivedi, Y. K. et al. (2025): *Agentic AI Systems: What It Is and Isn't.* Global Business and Organizational Excellence, DOI 10.1002/joe.70018. | Definiert Agentic-AI-Systeme über Planung, geteiltes Gedächtnis, Tools und Multi-Agenten-Teamarbeit. Risiken: kaskadierende Fehler, Zielfehlausrichtung, Regulierungslücken. Fordert Transparenz, Verantwortlichkeit, menschliche Aufsicht. | Management-Perspektive, passt zur WKO-Zielgruppe. |
| Islam, M. A. et al. (2025): *The Rise of Agentic AI: Synthesis of Current Knowledge and Future Research Agenda.* Global Business and Organizational Excellence. | Systematisches Review. Vier Forschungsstränge: Mensch-KI-Kollaboration, Autonomie vs. Kontrolle, Governance/Vertrauen, gesellschaftliche/ethische Folgen. Antecedent-Mechanism-Outcome-Framework. | Forschungsstand-Überblick, gut für die Folie „Was die Forschung bisher sagt“. |
| Hughes, L. et al. (2025): *AI Agents and Agentic Systems: A Multi-Expert Analysis.* Journal of Computer Information Systems. (Consensus: 204 Zitationen) | Expertenanalyse: Agentensysteme dezentralisieren Entscheidungen und verändern Organisationsstrukturen. Offene Fragen: Zurechnung von Verantwortung, Altsysteme, Bias. | Organisatorische Folgen. |
| Dodda, A. (2025): *Understanding agentic artificial intelligence: Autonomous digital agents and their impact on workflows and decisions.* Buchkapitel, DOI 10.70593/978-81-988918-1-5_3. | Drei Merkmale autonomer Agenten: handeln **im Auftrag** statt nur unterstützend, breites Aufgabenspektrum jenseits von Frage-Antwort, Interaktion in virtueller und physischer Welt. Volle Wirkung erfordert Prozess-Redesign. | Abgrenzung zum Chatbot (Frage-Antwort). **Qualität: Buchkapitel, Einzelautor, mit Vorsicht zitieren.** |

## B. Technik, Architektur, Evaluation

| Quelle | Kernaussage | Nutzen |
|---|---|---|
| Ferrag, M. et al. (2025): *From LLM Reasoning to Autonomous AI Agents: A Comprehensive Review.* IEEE Access. (236 Zit.) | Taxonomie von ca. 60 Benchmarks (2019–2025), Agenten-Frameworks 2023–2025, Protokolle (MCP, A2A, ACP). | Überblick für den technischen Teil. |
| Yehudai, A. et al. (2025): *Survey on Evaluation of LLM-based Agents.* arXiv. (236 Zit.) | Erste umfassende Evaluationsübersicht. Lücken bei Kosteneffizienz, Sicherheit, Robustheit. | Warum „Benchmark-Erfolg ≠ Praxistauglichkeit“. Preprint. |
| Li, X. et al. (2024): *A survey on LLM-based multi-agent systems: workflow, infrastructure, and challenges.* Vicinagearth. (685 Zit.) | Fünf Komponenten: Profil, Wahrnehmung, Handlung, Interaktion, Evolution. | Optional, Multi-Agenten-Grundlagen. |
| Ferrag, M. et al. (2025): *From Prompt Injections to Protocol Exploits: Threats in LLM-Powered AI Agents Workflows.* ICT Express. (121 Zit.) | Über 30 Angriffstechniken auf Agenten-Ökosysteme (Prompt-Injection, Protokoll-Schwachstellen). | **Sicherheitsfolie.** Agenten mit Tool-Zugriff vergrößern die Angriffsfläche. |

### Zuverlässigkeit (arXiv-Preprints, nicht peer-reviewed)
Die Arbeiten stammen aus der Firecrawl-Suche. Die arXiv-Nummern (2601.x, 2602.x, 2608.x, 2610.x) liegen teils nach meinem Kenntnisstand. **Ich konnte sie nicht unabhängig verifizieren. Vor jeder Verwendung selbst auf arxiv.org öffnen.**

- *Beyond Accuracy: A Multi-Dimensional Framework for Evaluating Enterprise Agentic AI Systems* (arXiv 2511.14136): Leistung fällt von 60 % (Einzellauf) auf 25 % (Konsistenz über 8 Läufe); bis zu 50-fache Kostenunterschiede bei ähnlicher Genauigkeit. Starke Aussage für Unternehmen, aber Preprint.
- *ReliabilityBench* (arXiv 2601.06112): Störungen senken die Erfolgsrate von 96,9 % auf 88,1 %.
- *On Randomness in Agentic Evals* (arXiv 2602.07150): Einzellauf-Ergebnisse schwanken um 2,2 bis 6,0 Prozentpunkte.
- *Evaluation and Benchmarking of LLM Agents: A Survey* (arXiv 2507.21504): Unternehmensspezifische Herausforderungen (Rollenrechte, Compliance, Langzeit-Interaktion).

## C. Empirische Wirkung in Unternehmen (Feldexperimente)

Wichtig für die Einordnung: Die meisten kausalen Studien untersuchen **generative KI als Assistenz** (Copilot, GPT-4), **nicht autonome Agenten**. Das sollte im Vortrag offen gesagt werden. Für echte Agenten ist die Evidenz noch dünn.

| Quelle | Design / Stichprobe | Befund |
|---|---|---|
| Cui, K. et al. (2026): *The Effects of Generative AI on High-Skilled Work: Evidence from Three Field Experiments with Software Developers.* Management Science, DOI 10.1287/mnsc.2025.00535. (181 Zit.) | 3 RCTs, 4.867 Entwickler (Microsoft, Accenture, Fortune-100-Firma) | +26,08 % abgeschlossene Aufgaben (SE 10,3 %); Weniger Erfahrene profitieren stärker. |
| Dell'Acqua, F. et al. (2026): *Navigating the Jagged Technological Frontier.* Organization Science, DOI 10.1287/orsc.2025.21838. (175 Zit.) | Präregistriertes Experiment, 758 BCG-Berater, GPT-4 | Innerhalb der KI-Fähigkeitsgrenze: +12,2 % Aufgaben, 25,1 % schneller, bessere Qualität. **Außerhalb: 19 % weniger korrekte Lösungen.** Begriff „jagged frontier“. |
| Dell'Acqua, F. et al. (2026): *The Cybernetic Teammate.* Organization Science, DOI 10.1287/orsc.2025.20702. | Präregistriertes Feldexperiment, 791 Fachleute bei Procter & Gamble | Einzelne mit KI erreichen Leistung von Teams ohne KI; KI überbrückt Fachsilos; Urteilsvermögen des Menschen bleibt bei der Auswahl wertvoll. |
| Dillon, E. et al. (2025): *Shifting Work Patterns with Generative AI.* arXiv. | Feldexperiment, 66 Firmen, 7.137 Wissensarbeiter, 6 Monate | Rund 2 Std. weniger E-Mail pro Woche; **sonst keine Verschiebung von Aufgabenmenge/-mix.** Dämpft Erwartungen. Preprint. |
| Fang, L. et al. (2025): *Generative AI and Sales Productivity: Field Experiments in Online Retail.* CESifo Working Paper. | Randomisierte Feldexperimente, Millionen Nutzer, 7 Workflows | Effekte von „nicht nachweisbar“ bis +16,3 % Umsatz, abhängig vom Mehrwert gegenüber bisheriger Praxis. Working Paper. |
| Ni, X. et al. (2026): *Generative AI in Action: Field Experimental Evidence from Alibaba's Customer Service Operations.* arXiv. | Großes Feldexperiment, Chat-Support | Schneller und subjektiv besser bewertet, aber **keine Verbesserung objektiver Qualität**; Leistungsschwache profitieren, **Top-Performer verschlechtern sich.** Preprint. |
| Fitz-Patrick, T. et al. (2025): *Assessing Generative AI value in a public sector context.* arXiv. | Präregistriert, Verwaltung | Dokumentenaufgabe +17 % Qualität, −34 % Zeit; Datenaufgabe **−12 % Qualität.** Aufgabenabhängig. Preprint. |
| Calvino, F. et al. (2025): *The effects of generative AI on productivity, innovation and entrepreneurship.* OECD Artificial Intelligence Papers. | Review experimenteller Forschung | Wirkung hängt von Erfahrung der Nutzer und Aufgabe ab; Langzeiteffekte und Verständnis der Grenzen sind Forschungslücken. |

**Roter Faden:** Die Evidenz zeigt konsistent Produktivitätsgewinne bei klar umrissenen Aufgaben, aber ungleich verteilt (Novizen > Experten) und mit Qualitätsrisiko außerhalb der KI-Fähigkeitsgrenze.

## D. Kundenservice: Chatbot vs. Mensch (Akzeptanz)

| Quelle | Befund |
|---|---|
| Markovitch, D. G. et al. (2024): *Consumer reactions to chatbot versus human service: outcome valence and perceived empathy.* J. of Retailing and Consumer Services. (87 Zit.) | N = 714 (4 Studien): Geringere Zufriedenheit und Wiederkaufabsicht nach Chatbot-Service; vollständig über wahrgenommene Empathie vermittelt. Empathischere Kommunikation (nicht menschliches Aussehen) hebt die Bewertung auf Mensch-Niveau. |
| Huang, D. et al. (2024): *Can chatbot customer service match human service agents on customer satisfaction?* J. of Retailing and Consumer Services. (120 Zit.) | N = 643 (3 Studien): Chatbot plus „Light-Touch“-Eingriff eines Menschen erreichte bei den meisten Ergebnissen Mensch-Niveau. |
| Zhang, Y. et al. (2025): *AI Chatbots Versus Human Agents in Customer Satisfaction: The Role of Warmth and Competence.* J. of Interactive Marketing. | 887 Chat-Transkripte plus Experiment (N = 989): Chatbots besser bei kompetenzgetriebenen, transaktionalen Anfragen; Menschen bei relationalen Anliegen (Vertrauen, Bindung). |
| Wu, L.-W. et al. (2026): *AI Chatbots Versus Human Agents for Customer Service: A Social Belonging Perspective.* J. of Consumer Behaviour. | N = 587 (3 Experimente) plus Social-Media-Daten: schwächere Kaufabsicht bei Chatbots, Mechanismus Zugehörigkeitsgefühl. |

**Fazit für den Vortrag:** Hybrid-Modelle (KI plus menschlicher Eingriff) sind in der Evidenz am robustesten. Meist Vignetten-/Online-Experimente, begrenzte Aussagekraft für reale Langzeitwirkung.

## E. Governance, Aufsicht, Verantwortung

| Quelle | Kernaussage | Qualität |
|---|---|---|
| Zhu, L.-M. et al. (2026): *Designing meaningful human oversight in AI.* AI and Ethics. (15 Zit.) | Schichtenmodell: KI hat operative, Mensch hat evaluative Handlungsmacht; Gefahr des „Rubber-Stamp“. | Konzeptionell, peer-reviewed. |
| Basu, P. (2026): *Governing agentic performance management.* Int. J. of Organizational Analysis. | Begriff **Specification Risk**: Agenten optimieren formalisierte Ziele, die von impliziten Organisationswerten abweichen. | Konzeptionell, 9 Propositionen, nicht empirisch. |
| Bahidika, O. (2026): *Agentic Accountability: „The Buck Stops Where?“* IJACSA. | Vierstufiges Aufsichtsmodell nach Risiko und Reversibilität; Pilot an 177 Vorfällen der AI Incident Database. | Konzeptionell plus kleiner Pilot, Journal mit geringerem Renommee. |
| Anchala, S. (2026): *Ethical, legal, and social implications of deploying agentic AI.* J. of Digital Security and Forensics. | Behauptet, 78 % der 150 Vorfälle hingen mit unzureichender Aufsicht zusammen; 62 % von 500 Befragten misstrauen hochautonomen Systemen. | **Vorsicht:** kleines Journal, Methodik unklar. Zahlen nicht ungeprüft übernehmen. |

## Lücken und Hinweise

- **Peer-reviewte Feldexperimente zu *autonomen* Agenten im Unternehmenseinsatz fehlen weitgehend.** Das ist selbst eine Aussage für den Vortrag.
- Viele Agenten-Arbeiten sind Surveys/Konzeptpapiere mit hoher Zitationszahl, aber geringer empirischer Basis.
- Arbeitsmarkt, Exposition und KMU: siehe `arbeitsmarkt-und-oekonomie.md`. Institutionelle Studien: `../02-studien-und-arbeitsmarkt/`. Anthropic: `../03-anthropic/`.
