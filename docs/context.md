# Course Context

## Course Type

Type: self-paced
Working Title: DiAgnostiK Lehr- und Lernraum – Tischler und Schreiner

## Course Profile

Terminology:
  sessions-called: Lerneinheit
  lectures-called: Lernmodul

Persona type: coach
Agenda required: yes
Pacing: learner-driven
Assessment defaults: quizzes

## Conventions & Standards

Language: de
Tone: formal
Person: Sie
Accessibility: required

LiaScript conventions:
  - Metadata header required for every file: author, email, version, language, narrator, date, icon, logo, tags, comment, title
  - language: de | narrator: Deutsch Male (default)
  - Custom CSS linked via: `link: ./style.css`
  - Shared macro libraries imported from GitHub (Ifi-DiAgnostiK-Project org)
  - Tags: Tischler, Schreiner (primary tags for all files in this course)
  - Alt text required on all media elements (accessibility: required)
  - Animation counters reset to 0 after each ## heading
  - Exactly one # heading per file (course/material title)
  - File naming: descriptive slugs (e.g. `holzarten_01_theorie.md`) — kein `{n}-{type}.md` Schema
  - Theorie-Dateien folgen dem Muster: `{thema}_theorie.md`
  - Quiz-/Übungsdateien behalten ihre bestehenden Dateinamen

## Additional Notes

- Scope: Dieser Kurs deckt ausschließlich den Tischler-/Schreinerbereich ab
- Struktur: Hybrid — thematische Lernmodule (eigenständig nutzbar) + sequenzielle Lehrgangs-Spur (G-TSM → TSM 1 → TSM 2)
- Jede thematische Lerneinheit besteht aus einer Theorie-Datei (neu) gefolgt von einem oder mehreren Quiz/Übungsdateien (bestehend)
- Publishing: LiaScript Exporter via GitHub Actions → GitHub Pages; project YAML in Projekt-Root
- Brand colors: Primary #1A2F5E (Marineblau), Accent #C9A84C (Handwerksgold)
- Logo: `assets/img/Logo_234px.png` | Hero image: `assets/img/slogan_hero.jpg`
- Betreiber: GKZ e.V. / uelu-digital.de | Gefördert durch EU/Freistaat Sachsen
- Kein `skeletons/` Ordner — Materialien werden direkt erstellt
- Shared macro repos: Piktogramme, LiaScript_DragAndDrop_Template, LiaScript_ImageQuiz, Bildersammlung, Holzarten
- Neue Theorie-Seiten folgen denselben Header-Konventionen wie bestehende Materialien
