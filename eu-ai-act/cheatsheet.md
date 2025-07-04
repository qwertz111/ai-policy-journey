# EU AI Act – Cheatsheet  

**12 Quick Facts**  
1. Definition „KI-System“  
2. Risikostufen  
3. Verbotene Praktiken  
4. High-Risk-Pflichten  
5. Konformitätsbewertung  
6. Marktüberwachung  
7. Transparenzauflagen  
8. Datengovernance  
9. Human Oversight  
10. Genauigkeit & Robustheit  
11. Aufzeichnungspflichten  
12. Durchsetzung & Bußgelder  

### Zweck des EU AI Acts (Art 1(1)
- Besseres Funktionieren des Binnenmarkts
- Förderung einer **auf den Menschen ausgerichteten** KI
- Schutz der:
  - Gesundheit
  - Sicherheit
  - Grundrechte (Basis: Charta der Vereinten Nationen)
    - Demokratie
    - Rechtsstaatlichkeit
    - Umweltschutz
- Schutz vor schädlichen Auswirkungen von KI-Systemen allgemein
- Unterstützung der Innovation

### KI-Campus · AI Act Essentials – Modul 1.1.1 „Eine Technologie wie keine Andere“[^kc1]

| Merkmal | KI-System | Traditionelle Software |
|---------|-----------|------------------------|
| **Lernfähigkeit** | Lernt aus Daten, passt Modelle an | Keine eigene Lernfähigkeit – folgt festem Code |
| **Verhalten über Zeit** | Kann sich dynamisch ändern | Vorhersehbar; ändert sich nur bei Updates |
| **Weiterentwicklung** | Neues (Re-)Training möglich, teils sogar im Feld | Erfordert manuellen Code-Eingriff & Release |
| **Unbekannte Szenarien** | Muss improvisieren – Risiko falscher Reaktion bei Datenlücken | Befolgt fixe Regeln, kann nicht improvisieren |

> **Kurz-Erläuterung:** KI-Systeme sind *datengetrieben* und entwickeln sich nach der Inbetriebnahme weiter. Das erklärt die strengen Vorgaben zu **Risikomanagement (Art. 9)** und **Post-Market-Monitoring (Art. 61 ff.)** im EU AI Act.

[^kc1]: Quelle: KI-Campus Online-Kurs *AI Act Essentials*, Modul 1 – 2025 · Lizenz CC BY-SA 4.0



## Art. 9 – Risikomanagement  
…  
### Typische Bias-Quellen in KI-Systemen

| # | Bias | Kurzbeschreibung | Typische Ursache | Beispiel |
|---|------|-----------------|------------------|----------|
| 1 | **Sampling Bias** (Stichprobenverzerrung) | Trainingsdaten repräsentieren die Zielpopulation nicht ausreichend. | Daten stammen v. a. aus leicht zugänglichen Quellen oder bestimmten Regionen. | Gesichtserkennung, die überwiegend mit Bildern hellhäutiger Personen trainiert wurde. |
| 2 | **Selection Bias** | Bestimmte Gruppen werden systematisch häufiger in den Daten ausgewählt. | Nutzer:innen wählen sich selbst in die Datenerhebung ein (Self-selection). | Empfehlungs­system, das Filmbewertungen nur von aktiven Fans berücksichtigt. |
| 3 | **Historical Bias** | Vergangene gesellschaftliche Ungleichheiten spiegeln sich 1:1 in den Daten wider. | „As-is“-Daten ohne Korrektur genutzt. | Einstellungs-KI übernimmt frühere Diskriminierung gegen Frauen. |
| 4 | **Representation Bias** | Minderheiten oder Randgruppen sind unter- oder falsch repräsentiert. | Datenerhebung fokussiert Mainstream-Nutzer. | Sprachmodell versteht Dialekte schlechter als Hochsprache. |
| 5 | **Measurement Bias** | Ungeeignete Proxy-Variablen oder ungenaue Messmethoden. | Indirekte Features statt Zielgröße gemessen. | Kredit-Scoring nutzt Postleitzahl als Ersatz für Ausfallrisiko. |
| 6 | **Label Bias** | Labels enthalten subjektive oder inkonsistente Urteile. | Menschliche Annotator:innen interpretieren Kriterien unterschiedlich. | Hate-Speech-Dataset mit uneinheitlicher Definition von „toxisch“. |
| 7 | **Algorithmic Bias** | Lernverfahren verstärkt vorhandene Ungleichheiten oder verzerrt Feature-Gewichte. | Loss-Funktion ohne Fairness-Regularisierung. | Klassifikator priorisiert das Mehrheitslabel, weil es Genauigkeit maximiert. |
| 8 | **Confirmation Bias** | Entwickler suchen (unbewusst) nach Ergebnissen, die ihre Annahmen bestätigen. | Hypothesen-getriebene Feature-Selektion. | Nur Features behalten, die erwartete Korrelation zeigen. |
| 9 | **Temporal Bias** | Datenbasis veraltet, spiegelt aktuelle Realität nicht mehr wider. | Lange Iterationszyklen, seltenes Retraining. | Nachfrage-Forecast ignoriert verändertes Kaufverhalten nach einer Krise. |
| 10 | **Automation Bias** | Nutzer:innen vertrauen KI-Ausgabe übermäßig und hinterfragen sie nicht. | „Black-box“-Systeme ohne Erklärbarkeit. | Radiologe übersieht Fehlklassifikation, weil das System „99 % sicher“ meldet. |

> **Hinweis:** Mehrere Bias-Arten können gleichzeitig auftreten. Ein robustes **Risikomanagement (Art. 9 EU AI Act)** sollte deshalb Datenerhebung, Modellierung und Nutzung ganzheitlich prüfen – inklusive regelmäßiger **Fairness-Metriken** (z. B. Demographic Parity, Equalized Odds) und **Post-Market-Monitoring**.

