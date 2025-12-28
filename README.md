# Office Backup & Recovery v143

![License](https://img.shields.io/badge/License-EULA--Custom-orange)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Framework](https://img.shields.io/badge/Framework-.NET%208.0-green)

**Office Backup & Recovery** ist ein spezialisiertes Tool zur Sicherung und Wiederherstellung von Microsoft Outlook-Profilen, PST-Dateien und Office-Lizenz-Tokens. Es wurde entwickelt, um Migrationen zu vereinfachen und Datenverlust vorzubeugen.

<img width="1586" height="943" alt="2025-12-28 14_24_41-Office Backup   Recovery" src="https://github.com/user-attachments/assets/af1b003e-ba08-4af1-bedb-348ff8513a5d" />
<img width="1586" height="943" alt="2025-12-28 14_30_25-Office Backup   Recovery" src="https://github.com/user-attachments/assets/b1e74023-f67a-40d8-9bf0-68247246dd54" />

## 🚀 Features

* **Komplett-Sicherung:** Sichert Outlook-Profile (Registry), PST-Dateien und Office-Aktivierungs-Tokens.
* **Deep Scan:** Findet automatisch alle vorhandenen Outlook-Profile auf dem System.
* **AES-256 Verschlüsselung:** Alle Backups werden mit militärischem Standard verschlüsselt (.enc).
* **ISO 27001 Passwort-Check:** Erzwingt sichere Passwörter für maximalen Schutz.
* **Validierung:** Prüft Archive vor der Wiederherstellung auf Integrität und Passwort-Korrektheit.
* **Modern UI:** Glas-Effekt-Design mit Echtzeit-Statusanzeige und neongrünem Log-System.

## 🛠 Installation & Anforderungen

1.  Entpacke die .zip
2.  Führe den Installer aus.
3.  Stelle sicher, dass die **.NET 8.0 Desktop Runtime** installiert ist.
4.  Starte die `Office_Backup_Recovery`.

*Hinweis: Zum Sichern der PST-Dateien muss Outlook geschlossen sein.*

## 🔒 Sicherheit

Die Sicherung erfolgt lokal. Es werden keine Daten in die Cloud übertragen. Die Verschlüsselung basiert auf einem Passwort-basierten Schlüssel (PBKDF2 mit individuellem Salt), was Brute-Force-Angriffe erheblich erschwert.

## 📄 Lizenz

Dieses Projekt unterliegt einer individuellen EULA (End User License Agreement). Die kommerzielle Weiterverbreitung ohne Zustimmung des Autors ist untersagt. Siehe [LICENSE](LICENSE) für Details.

---
**Entwickelt in Deutschland** | © 2025 Malte Speck
