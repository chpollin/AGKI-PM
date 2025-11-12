# Skriptum Session 6: Anforderungsanalyse

## 1. Requirements Engineering: Grundlagen

### 1.1 Was sind Anforderungen?
- Definition nach IEEE 830
- Stakeholder-Bedürfnisse
- System-Spezifikationen
- Constraints und Rahmenbedingungen

### 1.2 Warum Requirements Engineering?
- Projekterfolg durch klare Anforderungen
- Kostenfaktor früher vs. später Änderungen
- Kommunikation zwischen Stakeholdern
- Vertragsgrundlage

### 1.3 Requirements Engineering Prozess
1. **Elicitation** (Erhebung)
2. **Analysis** (Analyse)
3. **Specification** (Spezifikation)
4. **Validation** (Validierung)
5. **Management** (Verwaltung)

## 2. Anforderungserhebung (Requirements Elicitation)

### 2.1 Stakeholder-Analyse
- Identifikation aller Stakeholder
- Interessen und Erwartungen
- Power-Interest-Grid
- Kommunikationsplanung

### 2.2 Erhebungstechniken

#### Interviews
- Strukturierte vs. unstrukturierte Interviews
- Fragetechniken (offen vs. geschlossen)
- Aktives Zuhören
- Protokollierung

#### Workshops und Focus Groups
- Gemeinsame Erarbeitung
- Moderation
- Brainstorming-Techniken
- Konsensbildung

#### Observation (Beobachtung)
- Ethnografische Methoden
- Contextual Inquiry
- Shadowing
- Task Analysis

#### Questionnaires (Fragebögen)
- Für große Stakeholder-Gruppen
- Statistische Auswertung
- Limitation: Keine Rückfragen

#### Document Analysis
- Bestehende Systeme
- Policies und Richtlinien
- Wissenschaftliche Literatur
- Standards (TEI, Dublin Core, etc.)

#### Prototyping
- Exploratives Prototyping
- Anforderungen durch Feedback
- Throw-away vs. Evolutionary

### 2.3 DH-spezifische Erhebung
- Forscherfragen als Anforderungsquelle
- Community-Standards einbeziehen
- Interdisziplinäre Perspektiven
- Technische vs. geisteswissenschaftliche Anforderungen

## 3. Arten von Anforderungen

### 3.1 Funktionale Anforderungen
- Was soll das System tun?
- Features und Funktionen
- Eingabe-Verarbeitung-Ausgabe
- Use Cases

#### Beispiele aus DH:
- "System soll TEI-XML importieren können"
- "Volltextsuche über Korpus"
- "Export in verschiedene Formate"
- "Annotation von Textstellen"

### 3.2 Nicht-funktionale Anforderungen

#### Performance
- Response Time
- Throughput
- Skalierbarkeit
- Effizienz

#### Usability
- Learnability
- Efficiency of Use
- Memorability
- Error Prevention
- User Satisfaction

#### Reliability
- Verfügbarkeit
- Fehlertoleranz
- Recoverability
- Maturity

#### Security
- Authentication
- Authorization
- Datenschutz (DSGVO)
- Audit Trails

#### Maintainability
- Modularity
- Reusability
- Analyzability
- Modifiability
- Testability

#### Portability
- Adaptability
- Installability
- Cross-Platform-Kompatibilität

#### Compliance
- Standards und Normen
- Rechtliche Anforderungen
- Lizenzierung
- Barrierefreiheit (WCAG, EN 301 549)

### 3.3 DH-spezifische nicht-funktionale Anforderungen

#### Interoperabilität
- Standards-Konformität (TEI, MEI, IIIF, etc.)
- APIs und Schnittstellen
- Linked Open Data
- FAIR Principles

#### Langzeitarchivierung
- Datenformate
- Migrationsstrategien
- Metadaten-Standards
- Preservation Planning

#### Wissenschaftlichkeit
- Zitierfähigkeit (DOIs, URNs)
- Versionierung
- Transparenz und Nachvollziehbarkeit
- Reproduzierbarkeit

#### Community-Anforderungen
- Offene Lizenzen
- Open Access
- Open Source
- Nachnutzbarkeit

## 4. Requirements Analysis und Modellierung

### 4.1 Use Cases
- Akteure (Actors)
- Use Case Diagramme (UML)
- Use Case Beschreibungen
  - Preconditions
  - Main Flow
  - Alternative Flows
  - Postconditions
- DH-Beispiele (Researcher, Annotator, Public User, etc.)

### 4.2 User Personas
- Fiktive, aber realistische Nutzerprofile
- Demographics
- Goals und Motivations
- Frustrations und Pain Points
- Technical Proficiency
- DH-Personas: Digital Humanist, Philologe, Student, interessierte Öffentlichkeit

### 4.3 Scenarios und User Journeys
- Narrative Beschreibungen
- Step-by-Step Workflows
- Touchpoints identifizieren
- Emotional Journey

### 4.4 Datenmodellierung
- Entity-Relationship-Diagramme
- Datenstrukturen
- Ontologien und Taxonomien
- DH-spezifisch: TEI-Schema, CIDOC-CRM, etc.

## 5. Requirements Specification

### 5.1 Anforderungsdokument (SRS - Software Requirements Specification)
- IEEE 830 Standard
- Struktur und Inhalte
- Eindeutigkeit und Konsistenz
- Testbarkeit

### 5.2 Anforderungskatalog
- Tabellarische Form
- ID, Titel, Beschreibung
- Priorität
- Status
- Verantwortliche

### 5.3 Spezifikationssprachen
- Natural Language (Vor- und Nachteile)
- Strukturierte Templates
- Formale Spezifikationen (begrenzt in DH)
- User Stories als agile Spezifikation

## 6. Priorisierung von Anforderungen

### 6.1 MoSCoW-Methode
- **M**ust have (essentiell)
- **S**hould have (wichtig)
- **C**ould have (wünschenswert)
- **W**on't have (this time) (zurückgestellt)

### 6.2 Weitere Techniken
- Value vs. Effort Matrix
- Kano-Modell
- Ranking und Rating
- 100-Dollar-Test

### 6.3 Minimum Viable Product (MVP)
- Kern-Features identifizieren
- Iterative Erweiterung
- Early Feedback
- Risikominimierung

## 7. Requirements Validation

### 7.1 Validierungstechniken
- Reviews und Walkthroughs
- Prototyping und Simulation
- Test Case Generation
- Acceptance Criteria prüfen

### 7.2 Qualitätskriterien für Anforderungen
- Vollständig
- Konsistent
- Eindeutig
- Korrekt
- Testbar
- Machbar
- Notwendig
- Priorisiert

### 7.3 Stakeholder-Abnahme
- Formal Approval
- Sign-off Prozess
- Baseline setzen

## 8. Requirements Management

### 8.1 Change Management
- Change Requests
- Impact Analysis
- Traceability
- Versionierung

### 8.2 Tools
- Requirements Management Tools (JIRA, Azure DevOps, etc.)
- Spreadsheets und Dokumente
- GitHub Issues für kleinere Projekte
- Traceability Matrices

### 8.3 Traceability
- Forward Traceability (Requirements → Design → Code → Test)
- Backward Traceability (Test → Code → Design → Requirements)
- Traceability Matrix

## 9. DH-Projektspezifika

### 9.1 Typische DH-Anforderungen
- Datenmodellierung nach TEI/MEI
- Suchmaschinenfunktionalität
- Annotations-Tools
- Visualisierungen
- APIs für Mashups
- Export-Funktionen
- Mehrsprachigkeit
- Responsive Design

### 9.2 Herausforderungen
- Multidisziplinarität: verschiedene Fachsprachen
- Evolvierende Anforderungen (Forschung!)
- Balance zwischen Forschung und Praxis
- Technische Schulden vs. Forschungsinnovation

### 9.3 Best Practices für DH
- Iterative Anforderungserhebung
- Enge Zusammenarbeit zwischen Geisteswissenschaftlern und Entwicklern
- Prototyping für Exploration
- Community-Standards berücksichtigen
- Open und transparent dokumentieren

## 10. LLM-Unterstützung bei Anforderungsanalyse

### 10.1 Prompt-Strategien
- Persona-Generierung
  - "Erstelle 3 User Personas für ein digitales Editionsprojekt..."
- Use Cases ableiten
  - "Leite aus folgenden User Stories Use Cases ab..."
- Nicht-funktionale Anforderungen identifizieren
  - "Welche nicht-funktionalen Anforderungen sind für ein TEI-basiertes Publikationssystem relevant?"

### 10.2 Qualitätssicherung
- LLM-Output immer validieren
- Fachexperten einbeziehen
- Spezifischen Kontext nachliefern
- Iterative Verfeinerung

### 10.3 Dokumentationsunterstützung
- Use Case Beschreibungen formulieren
- Anforderungsdokumente strukturieren
- Glossare erstellen

## Literatur

### Pflichtlektüre
- IEEE 830: "Recommended Practice for Software Requirements Specifications"
- "Creating Digital Humanities Projects" (UCLA Library Research Guide)
- "Digital Humanities Project Planning" (USC Library Guide)

### Weiterführende Literatur
- Pohl, K. & Rupp, C.: "Requirements Engineering Fundamentals"
- Robertson, S. & Robertson, J.: "Mastering the Requirements Process"
- Wiegers, K. & Beatty, J.: "Software Requirements"
- Cooper, A.: "The Inmates Are Running the Asylum" (Personas)
- Patton, J.: "User Story Mapping"

### DH-spezifisch
- Drucker, J.: "SpecLab: Digital Aesthetics and Projects in Speculative Computing"
- Flanders, J. & Jannidis, F.: "The Shape of Data in Digital Humanities"
- Research Guides verschiedener DH-Zentren zu Projektplanung

### Standards
- TEI Guidelines: https://tei-c.org/guidelines/
- WCAG 2.1: https://www.w3.org/TR/WCAG21/
- FAIR Principles: https://www.go-fair.org/
