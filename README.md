# Automatisierte-Code-Standardisierung

Ein automatisiertes Software-Werkzeug zur Einhaltung von Corporate-Coding-Standards und Refactoring bei der Nutzung generativer KI 


## Problemstellung
Bei der Nutzung von KI-gestützten Code-Generatoren wie GitHub Copilot, Cursor AI, Claude Code und Lovable entstehen häufig stilistische Inkonsistenzen, redundante Kommentare ("KI-Fingerabdruck") und Abweichungen von unternehmensinternen Styleguides. Dies erhöht den manuellen Review- und Wartungsaufwand bei der Code-Integration.

## Zielsetzung
Entwicklung einer Python-Anwendung, die als Qualitätssicherungs-Werkzeug (Sanitizer) fungiert. Das Tool trennt Programmlogik von linguistischen Elementen, bereinigt Kommentare semantisch via LLM-API und passt Variablenstrukturen regelbasiert an Firmenvorgaben an.

## Geplanter Technologiestack
- **Sprache:** Python 3.x
- **Code-Analyse:** `ast`, `tokenize`, `re`
- **Schnittstelle:** Google GenAI SDK (`gemini-2.5-flash`)
- **Oberfläche:** CLI / GUI (tbd)

## Kernfunktionen (MVP)
- [ ] **Code-Parsing:** Strukturierte Zerlegung von Quellcodedateien.
- [ ] **Stil-Engine:** Regelbasiertes Refactoring von Variablennamen und API-gestützte Kommentarkürzung.
- [ ] **Validierung:** Syntaktische Überprüfung vor dem Datei-Export.

## Autor
- [ ] https://dynasync.de
