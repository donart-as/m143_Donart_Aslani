# Tag 1 (14.11.2025)

## Auftrag 1 

**11 Thesen**

1. Daten Backups kostet nichts
Antwort:  Falsch Hardware, Lizenzen, Mitarbeiter, Miete

2. Backups sind heute nicht mehr erforderlich
Antwort:  doch! Steueramt, wertvoll

3. Daten in der Cloud sind immer sicher.
Antwort:keine 100% Garantie, Cloud am sichersten

4. Nach dem Einrichten eines Backups ist sichergestellt, dass alle Daten immer werden.
Antwort: Nein! Backup -> RESTORE, Aktuell?, Ausfall

5. Der Datenverlust in einer Firma kostet nichts
Antwort:30% nichts / 70% -> Milliarden

6. Es müssen immer alle Daten gesichert werden.
Antwort:nein, Klassifiziezierung: Sensible daten bis junk

7. Eine Datensicherung pro Woche genügt.
Antwort:Nein, 1 Wo: Full / 1 Tag

8. Es gibt nur eine Art von Daten. deshalb kann die Backuperstellung immer gleich ausgeführt werden.
Antwort: nein, systemdaten benutzer-, app-, konfigurationdaten

9. Der Faktor zeit spielt bei der Backuperstellung keine Rolle.
Antwort:Doch, Backupzeit, restorezeit

10. Google macht von der Benutzerdaten keine Backups.
Antwort: Muss selber organisieren erst dann ist es sicher

11. Das erstellen von Backups ist im geschäftsumfeld freiwillig.
Antwort §: 10 sonst nicht


## Aufgabe 2

| Daten ↓ / Art →    | Image / 1:1 Klonen | Backup / Original → 1:1 Kopie | Archiv / Original → verschieben |
|-------------------|---------------------|-------------------------------|----------------------------------|
| **Systemdaten**   | ✔️                  | ❌                            | ❌                               |
| • OS              | ✔️                  | ❌                            | ❌                               |
| • Einstellung     | ✔️                  | ❌                            | ❌                               |
| **Apps**          | ✔️  (Installer)     | ❌                            | ❌                               |
| • Einstellung     | ✔️                  | ❌                            | ❌                               |
| **Benutzerdaten** | ❌                  | ✔️                            | ✔️       (Wichtig Ja)            |
| **Prozessdaten**  | ❌                  | ✔️                            | ❌         (wichtig ja)          |
| **Sensible Daten**| ❌                  | ✔️        Verschlüsselt sein  | ✔️ (verschlüsselt)               |
| **Medien**        | ❌                  | ❌                            | ❌                               |
| **Analoge Daten** | ❌                  | ❌                            | ✔️            (Digitalisieren)   |

Priorisieren:

1. Sensible Daten 
2. Wichtige Prozessdaten, Benutzerdaten
3. Prozessdaten, Benutzerdaten
4. Medien, Rest