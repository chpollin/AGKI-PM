# Skriptum Session 3: Git und GitHub im Kontext von DH-Projekten

## 1. Grundlagen der Versionskontrolle

### 1.1 Warum Versionskontrolle?
- Historische Entwicklung
- Probleme ohne Versionskontrolle
- Vorteile systematischer Versionierung
- Kollaborative Arbeit ermöglichen

### 1.2 Zentralisierte vs. Verteilte Versionskontrolle
- SVN und zentrale Systeme (historisch)
- Git als verteiltes System
- Vor- und Nachteile
- Paradigmenwechsel

### 1.3 Git: Philosophie und Konzepte
- Linus Torvalds und die Entwicklung von Git
- Snapshots vs. Deltas
- Integrität und Kryptografie (SHA-1 Hashes)
- Die drei Zustände: Working Directory, Staging Area, Repository

## 2. Git: Technische Grundlagen

### 2.1 Repository-Konzept
- Lokales Repository
- Remote Repository
- .git Verzeichnis
- Git Objects (Blobs, Trees, Commits)

### 2.2 Grundlegende Git-Befehle
#### Initialisierung und Konfiguration
```bash
git init
git config
git clone
```

#### Basis-Workflow
```bash
git add
git commit
git status
git log
git diff
```

#### Remote-Operationen
```bash
git remote
git push
git pull
git fetch
```

### 2.3 Branching und Merging
- Was sind Branches?
- Branch-Strategien (Git Flow, GitHub Flow, etc.)
- Merging vs. Rebasing
- Merge-Konflikte lösen

### 2.4 Best Practices
- Aussagekräftige Commit-Messages
- Atomic Commits
- .gitignore richtig nutzen
- Häufig committen, seltener pushen

## 3. GitHub als Kollaborationsplattform

### 3.1 Git vs. GitHub
- GitHub als Hosting-Service
- Zusatzfunktionen über Git hinaus
- Alternativen: GitLab, Bitbucket

### 3.2 GitHub Features für Projektmanagement
#### Issues
- Bug-Tracking
- Feature-Requests
- Aufgabenverwaltung
- Labels und Milestones

#### Pull Requests (PRs)
- Workflow
- Code Review
- Diskussionen
- Merge-Strategien

#### GitHub Projects
- Kanban-Boards
- Automatisierung
- Integration mit Issues/PRs

#### GitHub Actions
- CI/CD Grundlagen
- Automatisierte Workflows
- Relevanz für DH-Projekte

### 3.3 Dokumentation mit GitHub
- README.md als Einstiegspunkt
- Markdown-Syntax
- Wiki-Funktion
- GitHub Pages für Projektwebsites

## 4. Git und GitHub in Digital Humanities

### 4.1 Anwendungsfälle in DH-Projekten
- Forschungscode verwalten
- Daten versionieren
- Kollaborative Textedition
- Digitale Editionen
- Projektdokumentation

### 4.2 Git als Research Journal
- Transparenz schaffen
- Forschungsprozess dokumentieren
- Nachvollziehbarkeit gewährleisten
- Reproduzierbarkeit ermöglichen

### 4.3 Fallbeispiel: Git-Lit
- 50.000 digitale Editionen
- Distributed Version Control für Bücher
- Demokratisierung des Editionsprozesses
- Lessons Learned

### 4.4 Open Science und GitHub
#### Prinzipien
- Openness und Zugänglichkeit
- Transparenz
- Kollaboration
- Reproduzierbarkeit

#### GitHub für Open Access
- Public Repositories
- Forking und Weiterentwicklung
- Community-Contributions
- Issue-Tracker für Feedback

#### Versionskontrolle und wissenschaftliche Integrität
- Jede Änderung nachvollziehbar
- Autorenzuordnung
- Dezentrale Backups
- Branching für Experimente

## 5. Praktische Workflows

### 5.1 Einzelperson-Workflow
- Repository aufsetzen
- Regelmäßige Commits
- Remote Backup
- Release-Management

### 5.2 Team-Workflow
- Fork und Pull Request Model
- Shared Repository Model
- Code Review Prozesse
- Konfliktlösung

### 5.3 Integration in DH-Forschung
- Datenmanagement-Plan
- FAIR Principles (Findable, Accessible, Interoperable, Reusable)
- Langzeitarchivierung (Zenodo, Software Heritage)
- DOIs für Forschungssoftware

## 6. Spezielle Themen

### 6.1 Große Dateien und Binärdaten
- Probleme mit großen Dateien in Git
- Git LFS (Large File Storage)
- Alternativen für Forschungsdaten

### 6.2 Lizenzierung
- Warum Lizenzen wichtig sind
- Creative Commons für Inhalte
- Open-Source Lizenzen für Code (MIT, GPL, Apache, etc.)
- Choosing a License

### 6.3 Kollaboration über Institutionsgrenzen
- Externe Collaborators
- Organisation vs. persönliche Repos
- Access Management

## Literatur

### Pflichtlektüre
- "Committing to reproducibility and explainability: using Git as a research journal" (International Journal of Digital Humanities, 2023)
- GitHub Tutorial: "Version Control with Git and GitHub" (Center for Digital Research in the Humanities, University of Nebraska)
- Git-Lit Project Documentation

### Weiterführende Literatur
- Chacon, S. & Straub, B.: "Pro Git" (frei verfügbar unter https://git-scm.com/book/de/v2)
- GitHub Docs: https://docs.github.com/
- "A GitHub Garage for a Digital Humanities Course"
- Software Carpentry: "Version Control with Git"

### Online-Ressourcen
- GitHub Learning Lab
- Git Visualization Tools (Visualizing Git, Git School)
- Oh My Git! (Lernspiel für Git)
