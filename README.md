# Office Backup & Recovery M365 (v2.1.0)

![License](https://img.shields.io/badge/License-Proprietary-red)
![Security](https://img.shields.io/badge/Security-ISO%2027001%20Compliant-red)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Framework](https://img.shields.io/badge/Framework-.NET%208.0%20WPF-orange)

Ein professionelles Werkzeug zur Sicherung und Wiederherstellung von Microsoft Office-Lizenzen (Tokens), Outlook-Profilen und PST-Datenarchiven. Entwickelt für Administratoren und Power-User, um Migrationen und Systemwiederherstellungen zu vereinfachen.

## 📄 Lizenz & Nutzung

**Lizenz: Proprietär (Free for private use only)**

Dieses Programm ist proprietäre Software. Die Nutzung ist ausschließlich für **private, nicht-kommerzielle Zwecke** gestattet. 
- Ein Verkauf, Verleih oder kommerzieller Einsatz ist untersagt.
- Sämtliche Copyright-Hinweise (© Malte Speck) müssen erhalten bleiben.
- Die Nutzung erfolgt auf eigene Gefahr (Haftungsausschluss bei Datenverlust).

## 🚀 Hauptfunktionen

### 🔍 Audit & Sicherung (Deep Scan)
* **Multi-Datenbank-Discovery (NEU):** Erkennt beim Start automatisch alle im Verzeichnis liegenden `*_Vault.db` Dateien und führt sie in einer zentralen Historie zusammen.
* **Deep Scan Technologie:** Findet automatisch alle registrierten Outlook-Profile in der Windows-Registry sowie in Standard-Systempfaden.
* **PST-Mapping:** Identifiziert alle verknüpften `.pst` und `.ost` Dateien, unabhängig von ihrem Speicherort.
* **Lizenz-Harvesting:** Sichert digitale Office-Lizenzen (Tokens) aus `ProgramData`, `Local` und `Roaming` Verzeichnissen.
* **Automatisches Schließen:** Erkennt geöffnete Office-Prozesse, um Dateisperren während der Sicherung zu verhindern.

### 🔐 Sicherheit & Kompression
* **ISO 27001 Konformität:** Erzwingt sichere Passwörter (Min. 10 Zeichen, Groß-/Kleinschreibung, Zahlen, Sonderzeichen) für jedes Archiv.
* **AES-256 Verschlüsselung:** Alle Backups werden als `.enc` Dateien hochverschlüsselt gespeichert.
* **Intelligente Benennung:** Erzeugt automatisch ISO-konforme Dateinamen nach dem Schema `RECHNER__YYYY-MM-DD_Vault.db`.

### 🛠 Validierung & Recovery
* **Archiv-Vorschau:** Validiert Passwörter und zeigt den Inhalt eines Backups in einer Baumstruktur an, ohne das System zu verändern.
* **Hybrides Recovery:**
    * **Original-Pfad (Default):** Schreibt Daten exakt an den Ursprungsort zurück.
    * **Benutzerdefinierter Pfad:** Erlaubt die Extraktion in einen beliebigen Ordner (ideal für Datenrettung).
* **NUR PST/OST Modus:** Erlaubt die reine Datenextraktion ohne Registry-Eingriffe.

### 💾 Datenbank-Management (USB/Netz Support)
* **Multi-Import Funktion:** Lade externe Datenbanken von USB-Sticks oder Netzlaufwerken. Das Tool kopiert diese lokal und integriert sie nahtlos in die Historie (Merge-Logik).
* **Relativ-Suche:** Findet verschlüsselte Backups automatisch, auch wenn sich Laufwerksbuchstaben geändert haben.

## 📸 Screenshots
<img width="1586" height="943" alt="Office Backup Recovery Main" src="https://github.com/user-attachments/assets/af1b003e-ba08-4af1-bedb-348ff8513a5d" />
<img width="1586" height="943" alt="Office Backup Recovery Scan" src="https://github.com/user-attachments/assets/b1e74023-f67a-40d8-9bf0-68247246dd54" />

## 📋 Systemvoraussetzungen
* **Betriebssystem:** Windows 10 / 11 (64-Bit)
* **Laufzeitumgebung:** .NET 8.0 Desktop Runtime
* **Berechtigungen:** Administratorrechte erforderlich (für Registry-Zugriff und Lizenz-Token)

---
**Entwickler:** Malte Speck  
**Copyright:** © 2025 - | Alle Rechte vorbehalten.
