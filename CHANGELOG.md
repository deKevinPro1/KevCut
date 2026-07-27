# KevCut – Versionsverlauf

## 1.1.3 – Juli 2026 · Großes Bugfix- & Performance-Update

Das größte Stabilitäts-Update bisher.

**Leistung**
- Wiedergabe drastisch beschleunigt: Bilder auf der Timeline werden als fertige GPU-Bitmaps gehalten – Projekte, die vorher mit 14 fps ruckelten, laufen jetzt butterweich
- Proxy-Vorschau jetzt auch für MP4/MOV-Dateien; Erzeugung läuft nur im Leerlauf und pausiert automatisch bei Wiedergabe
- Video-Ressourcen werden intelligent verwaltet – auch sehr große Projekte (Filme, hunderte Clips) bleiben flüssig

**Stabilität**
- Beschädigte oder unvollständige Videodateien machen die Vorschau nicht mehr schwarz: KevCut zeigt ein Standbild, warnt mit genauer Sekundenangabe und exportiert korrekt
- Import legt echte lokale Kopien der Medien an – nachträglich verschobene oder veränderte Originaldateien können Projekte nicht mehr beschädigen
- Neue Werkzeuge: „Medien prüfen“ (liest jede Datei vollständig) und „Medien lokal übernehmen“ (Reparatur bestehender Projekte)

**Datensicherheit**
- Automatische Sicherungen: jedes Speichern legt zusätzlich eine Projektdatei in `Dokumente\KevCut-Sicherungen` ab (rollierend, die letzten 10 Stände)
- Projektspeicher gegen automatische Bereinigung durch den Browser-Unterbau geschützt

**Diagnose**
- Neue Leistungsanzeige (Menü Wiedergabe): zeigt Bildrate, Frame-Aufschlüsselung und benennt Clips, die nicht gezeichnet werden können

## 1.1.0 – Juli 2026

- Raumklang: 5.1/7.1, virtueller Surround, Raumklang je Clip und Spur, 5.1-Export
- Neues Erscheinungsbild, weichere Animationen, Einstellungen-Dialog
- Zahlreiche Fehlerbehebungen

## 1.0.0 – Juli 2026

- Erste Veröffentlichung: kompletter Videoeditor mit Timeline, Keyframes, Effekten, Ton-Studio, KI-Werkzeugen und Export
