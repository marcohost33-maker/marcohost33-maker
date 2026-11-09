# Coworkerz

> **English summary:** Engineering and research workshop of Marco at Coworker Research (Coworkerz):
> a human-plus-AI collective building apps, tooling and reproducible scientific software in small, verified steps.

Engineering- und Forschungs-Werkstatt von Marco (Coworker Research / Coworkerz).
Mensch-plus-KI-Kollektiv, das Apps, Tooling und reproduzierbare wissenschaftliche
Software in kleinen, verifizierten Schritten baut.

## Oeffentliche Projekte

### Physik und Quanten-Forschung

- [Liouscope](https://github.com/marcohost33-maker/Liouscope) — Relaxations-Diagnostik fuer offene
  Quanten-Gittersysteme (GKSL/Lindblad); Python-Paket auf PyPI, zitierbar ueber Zenodo-DOI.
- [qec-engine](https://github.com/marcohost33-maker/qec-engine) — Monte-Carlo/MCRG-Verifikations-Harness
  fuer Schwellen der Quanten-Fehlerkorrektur; Forschungsprototyp.
- [phi-hex](https://github.com/marcohost33-maker/phi-hex) — XY/BKT-Physik auf Dreiecks-, Honeycomb-
  und Kagome-Gittern (Wolff, Wang-Landau, Finite-Size-Scaling); Forschungscode.
- [hexa-ntk](https://github.com/marcohost33-maker/hexa-ntk) — PyTorch-Trainings- und Experiment-Infrastruktur
  fuer Neural-Operator-Laeufe auf hexagonalen Gittern; Forschungscode, kein trainiertes Modell.
- [atomic-information-lab](https://github.com/marcohost33-maker/atomic-information-lab) — exakter
  Informationswert und optimales Stoppen fuer diskrete Zwei-Zustands-Messmodelle, mit unabhaengigem
  Orakel in rationaler Arithmetik; nur synthetische Modelle, keine Hardware-Aussage.

### Sicherheit, Integritaet und Verifikation

- [ultratreiber](https://github.com/marcohost33-maker/ultratreiber) — Forschungs-Demonstrator eines
  isolierten, nur lesenden Zugriffs-Brokers (Linux, Windows); nicht produktionsreif.
- [safeforge](https://github.com/marcohost33-maker/safeforge) — absturzfeste Datei- und SQLite-Aufnahme:
  Referenzbibliothek und Pruefstand (Intent-first-Commit, fsync, atomares Veroeffentlichen,
  gehaertete ZIP-Pruefung) mit ausfuehrbarer Falsifikation gaengiger Atomaritaets-Annahmen.
- [equal3](https://github.com/marcohost33-maker/equal3) — Forschungsprototyp fuer authentisierten
  lokalen Zustand mit externen Zeugen; Release-Entscheid NO-GO.

### Apps und Laufzeiten

- [HexGol](https://github.com/marcohost33-maker/HexGol) — hexagonales Game of Life (Carter-Bays-Topologie)
  mit reellwertigen Physik-Modi und 16 klassischen Hex-Regeln; live auf
  [golhex.pages.dev](https://golhex.pages.dev).
- [browser](https://github.com/marcohost33-maker/browser) — Offline-faehige Laufzeit fuer fremde
  Web-Apps; Architektur- und Sicherheits-Grundlage, noch keine lauffaehige Laufzeit.
- [Lumos](https://github.com/marcohost33-maker/Lumos) — Erinnerungen und Google-Drive-Sync als
  Python-Bibliothek und `lumos`-CLI.

Gemeinsame Issue- und PR-Vorlagen liegen im [`.github`](https://github.com/marcohost33-maker/.github)-Repo.

## Nicht oeffentliche Projekte

Die meisten Projekte sind **privat** (Standard-Policy): derzeit rund 60 aktive Repos zu
Forschung (Physik, Numerik, Wissenschafts-Werkzeuge), Spielen und 3D-Welten, KI-Begleitern,
Compliance- und Arbeitsplanungs-Apps sowie interner Qualitaets-Infrastruktur. Sie werden
einzeln und erst nach Pruefung freigegeben. Wenn du hier landest, ohne ein bestimmtes Repo
zu sehen: das ist beabsichtigt.

## Arbeitsweise

- **Reality-Anchor:** belegte Resultate statt Behauptungen; "Tests N/N PASS (verified)".
- **Draft-first:** Beitraege starten als Draft-PR und werden erst nach einer
  verifizierten Definition-of-Done auf "ready" gesetzt.
- **Review-vor-Merge:** ein unabhaengiger Verifikations-Schritt geht jedem Merge voraus,
  bei sicherheitsnahen Aenderungen zusaetzlich eine Pruefung durch eine zweite Modellfamilie.

Details zu Beitraegen stehen in der PR-Vorlage des `.github`-Repos.
