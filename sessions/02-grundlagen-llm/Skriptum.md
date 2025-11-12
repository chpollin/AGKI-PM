# Skriptum Session 2: Grundlagen LLM und Prompt Engineering

## 1. Technische Grundlagen Large Language Models

### 1.1 Architektur von LLM
- Transformer-Architektur im Detail
- Attention-Mechanismus
- Encoder-Decoder vs. Decoder-Only
- Skalierung: Parameter und Modellgröße

### 1.2 Training von LLM
- Pre-Training auf großen Textkorpora
- Fine-Tuning für spezifische Aufgaben
- Reinforcement Learning from Human Feedback (RLHF)
- Instruction Tuning

### 1.3 Wichtige Konzepte
- Tokens und Tokenisierung
- Context Window und Limitierungen
- Temperature und Sampling-Strategien
- Top-p, Top-k Sampling

### 1.4 Vergleich verschiedener Modelle
- GPT-Familie (OpenAI)
- Claude (Anthropic)
- Gemini (Google)
- Open-Source Modelle (LLaMA, Mistral, etc.)
- Spezialisierte Modelle für Forschung

## 2. Systematisches Prompt Engineering

### 2.1 Prompt Engineering als Disziplin
- Definition und wissenschaftliche Grundlagen
- Sahoo et al. (2024): Systematische Taxonomie
- Best Practices aus der Forschung

### 2.2 Zero-Shot und Few-Shot Learning
- Zero-Shot Prompting
- One-Shot Examples
- Few-Shot Learning (k-shot)
- Wann welcher Ansatz?

### 2.3 Advanced Prompting Techniques
#### Chain-of-Thought (CoT)
- Prinzip des schrittweisen Denkens
- Formulierung von CoT-Prompts
- Anwendungsfälle

#### Tree-of-Thought (ToT)
- Verzweigtes Reasoning
- Exploration mehrerer Lösungspfade
- Praktische Implementation

#### Self-Consistency
- Multiple Reasoning Paths
- Konsensbildung
- Verbesserung der Zuverlässigkeit

### 2.4 Retrieval-Augmented Generation (RAG)
- Konzept und Architektur
- Wissensdatenbanken einbinden
- Halluzinationen reduzieren
- Anwendungen in DH-Projekten

## 3. Context Engineering

### 3.1 Von Prompt zu Context Engineering
- Definition nach "Survey of Context Engineering" (arXiv 2507.13334)
- Unterschied zu klassischem Prompting
- Bedeutung für komplexe Anwendungen

### 3.2 Context Retrieval und Generation
- Relevante Informationen identifizieren
- Kontext dynamisch generieren
- Externe Wissensquellen nutzen

### 3.3 Context Processing
- Strukturierung von Kontextinformationen
- Priorisierung bei begrenztem Context Window
- Kompression und Zusammenfassung

### 3.4 Context Management
- Kontext über mehrere Interaktionen
- Session-basiertes Management
- Memory Systems

### 3.5 Anwendungen in DH-Projektmanagement
- Projektspezifisches Wissen einbinden
- Fachterminologie und Konventionen
- Historische Projektdaten nutzen

## 4. Ethik und Research Integrity

### 4.1 Wissenschaftliche Standards bei LLM-Nutzung
- Transparenz und Nachvollziehbarkeit
- Reproduzierbarkeit
- Kritische Reflexion der Ergebnisse

### 4.2 Generative AI and Research Integrity
- Autorenschaft und Verantwortung
- Plagiarismus und Originalität
- Peer Review im Zeitalter von LLM

### 4.3 System 1.42: Kognition und KI
- Kognitive Verzerrungen (Cognitive Biases)
- System 1 und System 2 Denken (Kahneman)
- Delegation an KI-Systeme
- Kritisches Denken bewahren

### 4.4 Best Practices
- Dokumentation aller LLM-Nutzung
- Validierung von KI-generierten Inhalten
- Menschliche Expertise als Kontrolle
- Ethische Richtlinien einhalten

## 5. Praktische Anwendungen im Projektmanagement

### 5.1 LLM für Projektplanung
- Ideengenerierung
- Risikoidentifikation
- Zeitschätzungen
- Ressourcenplanung

### 5.2 Dokumentation und Kommunikation
- Meeting-Protokolle
- Projektberichte
- Stakeholder-Kommunikation
- Mehrsprachigkeit

### 5.3 Limitationen erkennen
- Wann LLM nicht geeignet sind
- Qualitätskontrolle
- Verantwortungsvolle Nutzung

## Literatur

### Pflichtlektüre
- Sahoo, P., et al. (2024): "A Systematic Survey of Prompt Engineering in Large Language Models: Techniques and Applications" (arXiv:2402.07927)
- "A Survey of Context Engineering for Large Language Models" (arXiv:2507.13334)
- Reading: "Generative AI and Research Integrity"
- Reading: "System 1.42"

### Weiterführende Literatur
- Wei, J., et al. (2022): "Chain-of-Thought Prompting Elicits Reasoning in Large Language Models"
- Yao, S., et al. (2023): "Tree of Thoughts: Deliberate Problem Solving with Large Language Models"
- Lewis, P., et al. (2020): "Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks"
- Prompt Engineering Guide: https://www.promptingguide.ai/
