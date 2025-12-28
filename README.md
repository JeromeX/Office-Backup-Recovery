# Office Backup & Recovery v1.4.3

![License](https://img.shields.io/badge/Security-ISO%2027001%20Compliant-red)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Framework](https://img.shields.io/badge/Framework-.NET%208.0%20WPF-orange)

Ein professionelles Werkzeug zur Sicherung und Wiederherstellung von Microsoft Office-Lizenzen (Tokens), Outlook-Profilen und PST-Datenarchiven. Entwickelt für Administratoren und Power-User, um Migrationen und Systemwiederherstellungen zu vereinfachen.

## 🚀 Hauptfunktionen

### 🔍 Audit & Sicherung (Deep Scan)
* **Deep Scan Technologie:** Findet automatisch alle registrierten Outlook-Profile in der Windows-Registry.
* **PST-Mapping:** Identifiziert alle verknüpften `.pst` Datendateien, egal wo sie auf dem System verstreut sind.
* **Lizenz-Harvesting:** Sichert digitale Office-Lizenzen (Tokens) aus `ProgramData`, `Local` und `Roaming` Verzeichnissen.
* **Automatisches Schließen:** Erkennt geöffnete Office-Prozesse, um Dateisperren (besonders bei PST-Dateien) zu verhindern.

### 🔐 Sicherheit & Kompression
* **ISO 27001 Konformität:** Erzwingt sichere Passwörter (Min. 10 Zeichen, Groß-/Kleinschreibung, Zahlen, Sonderzeichen) für jedes Archiv.
* **AES-256 Verschlüsselung:** Alle Backups werden als `.enc` Dateien hochverschlüsselt gespeichert.
* **Intelligente Kompression:** Reduziert die Archivgröße signifikant durch integrierte ZIP-Technologie vor der Verschlüsselung.

### 🛠 Validierung & Recovery
* **Archiv-Vorschau:** Validiert Passwörter und zeigt den Inhalt eines Backups in einer Baumstruktur an, ohne das System zu verändern.
* **Hybrides Recovery:**
    * **Original-Pfad (Default):** Schreibt Daten exakt dorthin zurück, wo sie gesichert wurden (garantiert Funktionsfähigkeit der Outlook-Profile).
    * **Benutzerdefinierter Pfad:** Erlaubt die Extraktion der Daten in einen beliebigen Ordner (ideal für Datenrettung auf fremden Systemen).
* **Registry-Automatisierung:** Importiert Outlook-Profile direkt zurück in die Windows-Registry.

### 💾 Datenbank-Management (USB/Netz Support)
* **Import-Funktion:** Lade externe `..._Vault.db` Datenbanken von USB-Sticks oder Netzlaufwerken.
* **Relativ-Suche:** Findet verschlüsselte Backups automatisch, auch wenn sich der Laufwerksbuchstabe des externen Datenträgers geändert hat.

## 📸 Screenshots
<img width="1586" height="943" alt="2025-12-28 14_24_41-Office Backup   Recovery" src="https://github.com/user-attachments/assets/af1b003e-ba08-4af1-bedb-348ff8513a5d" />
<img width="1586" height="943" alt="2025-12-28 14_30_25-Office Backup   Recovery" src="https://github.com/user-attachments/assets/b1e74023-f67a-40d8-9bf0-68247246dd54" />
<img width="1586" height="943" alt="2025-12-28 14_33_34-Office Backup   Recovery" src="https://github.com/user-attachments/assets/ae3988e2-4aa4-4ca1-88be-288dcf7d2851" />
<img width="1586" height="943" alt="2025-12-28 15_44_48-Office Backup   Recovery" src="https://github.com/user-attachments/assets/3b9adc7b-4690-4ec5-8171-6630cbb1db7d" />

## 📋 Systemvoraussetzungen
* **Betriebssystem:** Windows 10 / 11 (64-Bit empfohlen)
* **Laufzeitumgebung:** .NET 8.0 Desktop Runtime
* **Berechtigungen:** Administratorrechte erforderlich (für Registry-Zugriff und OSPP-Tokens)
