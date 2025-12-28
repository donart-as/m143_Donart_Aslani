# Wert von Daten

Daten haben heute einen sehr hohen Wert:

- Sie sind die Grundlage für Entscheidungen
- Sie ermöglichen Geschäftsprozesse und Planungen
- Datenverlust kann hohe Kosten oder sogar Firmenpleiten verursachen

→ Deshalb werden Daten oft als **„digitales Kapital“** bezeichnet.

---

# Nutzen von Daten

Daten werden genutzt für:

- Organisation und Verwaltung (Kunden, Mitarbeiter, Finanzen)
- Analyse und Auswertung (Statistiken, Prognosen)
- Automatisierung von Abläufen
- Wettbewerbsvorteile für Unternehmen

---

# Arten von Daten

- **Personenbezogene Daten** (Name, Adresse, Geburtsdatum)
- **Geschäftsdaten** (Rechnungen, Verträge)
- **Technische Daten** (System-, Konfigurationsdaten)
- **Unwichtige Daten** (z. B. temporäre Dateien)

---

# Rechtliches (Gesetze & Pflichten)

- **Datenschutz (DSGVO)** – Schutz personenbezogener Daten
- **Aufbewahrungspflichten** (z. B. Rechnungen, Buchhaltung)
- **Datensicherheit** – Schutz vor Verlust, Missbrauch und unbefugtem Zugriff

---

# Schutz von Daten

- Backups / Datensicherungen
- Zugriffsrechte
- Verschlüsselung
- Technische und organisatorische Massnahmen

---

# Image, Backup und Archiv

| Begriff | Bedeutung | Zweck |
|-------|----------|-------|
| Image | 1:1-Abbild eines Datenträgers | Systemwiederherstellung |
| Backup | Regelmässige Datensicherung | Wiederherstellung einzelner Daten |
| Archiv | Langfristige, unveränderbare Speicherung | Gesetzliche Aufbewahrung |

---

# Datenschutz vs. Datensicherheit

- **Datenschutz**: Schutz personenbezogener Daten
- **Datensicherheit**: Schutz vor Verlust, Missbrauch und Schäden

---

# Bedrohungsarten im ICT-Umfeld

| Höhere Gewalt | Kriminell | Menschlich |
|--------------|----------|------------|
| Erdbeben | Diebstahl | Löschen |
| Feuer | Malware | Fehlbedienung |
| Hardwaredefekt | Sabotage | Falsche Rechte |

---

# Schutzmassnahmen

| Technisch | Baulich | Organisatorisch |
|---------|--------|-----------------|
| Backup | Alarmanlage | Prozesse |
| Antivirus | Zugangskontrolle | Schulung |
| Verschlüsselung | Erdbebensicher | Verantwortliche |

---

# Restore & Disaster Recovery

## Restore
- Rückspielen gesicherter Daten

## Disaster Recovery (DR)
- Wiederherstellung nach grossen Ausfällen

---

# RPO / RTO

| Begriff | Erklärung |
|-------|-----------|
| RPO | Wie viele Daten dürfen verloren gehen |
| RTO | Wie lange darf der Ausfall dauern |

| Szenario | RPO | RTO |
|---------|-----|-----|
| PC | 24 h | 1–2 Tage |
| KMU | 4 h | 8 h |
| Online-Shop | Minuten | Minuten |

---

# Speicherarten

## DAS
- Direkt angeschlossen
- Einfach, günstig
- Nicht skalierbar

## NAS
- Netzwerkbasiert
- Mehrbenutzerfähig
- Zentrale Ablage

## SAN
- Hochleistungsnetz
- Sehr schnell
- Teuer & komplex

---

# Vergleich Speicher

| System | Vorteile | Nachteile |
|------|---------|-----------|
| DAS | Günstig | Kein Netzwerk |
| NAS | Zentral | Limitierte Performance |
| SAN | Sehr schnell | Hohe Kosten |

---

# RAID

RAID schützt vor Festplattenausfall, **ersetzt kein Backup**.

| Level | Vorteil | Nachteil |
|------|--------|---------|
| RAID 0 | Schnell | Keine Sicherheit |
| RAID 1 | Sicher | 50 % Kapazität |
| RAID 5 | Ausgewogen | Rebuild-Risiko |
| RAID 6 | Sehr sicher | Langsame Writes |

---

# WORM

- Einmal schreiben, mehrfach lesen
- Unveränderbar

| Art | Vorteil | Nachteil |
|----|--------|---------|
| Hardware | Sehr sicher | Teuer |
| Software | Günstig | Weniger sicher |

---

# ZFS

| Merkmal | Beschreibung |
|-------|-------------|
| Vorteil | Selbstheilung |
| Nachteil | Hoher RAM |
| Features | Snapshots, Replikation |

---

# Backup-Arten

| Art | Vorteil | Nachteil |
|----|--------|---------|
| File-Level | Einfach | Speicherintensiv |
| Image-Level | Schnell | Grosse Backups |
| Block-Level | Effizient | Komplex |
| Object | Skalierbar | Teurer |

---

# Backup-Strategien

| Strategie | Beschreibung |
|---------|--------------|
| 3-2-1-1-0 | Sicherste Methode |
| Inkrementell | Nur Änderungen |
| Differenziell | Seit Vollbackup |
| Voll | Komplett |
