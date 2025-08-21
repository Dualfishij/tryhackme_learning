# TryHackMe – Lernen Teil 1

## Offensive Security
- Erkennen und Ausnutzen von Systemschwachstellen, um Sicherheitsmaßnahmen zu verbessern  
- Ausnutzen von Softwarefehlern, unsicheren Setups oder fehlenden Zugriffskontrollen  
- **Red Teams** und **Penetration Tester** sind auf diese offensiven Techniken spezialisiert  

---

## Defensive Security
- Verhindern von Angriffen  
- Erkennen und Reagieren auf Angriffe  
- Typische Maßnahmen:
  - Sicherheitsbewusstsein der Nutzer schulen
  - Systeme und Geräte dokumentieren und verwalten
  - Systeme regelmäßig aktualisieren und patchen
  - Intrusion Prevention Systeme (**IPS**) einsetzen  
  - Logging- und Monitoring-Systeme einrichten  
- **IPS** blockiert jeglichen Netzwerkverkehr, der mit bekannten Angriffssignaturen übereinstimmt  
- **Blue Teams** sind für die defensive Sicherheit zuständig  

**Weitere Bereiche:**
- **Security Operations Center (SOC)**
- **Threat Intelligence**
- **Digital Forensics and Incident Response (DFIR)**
- **Malware Analysis**

---

## Security Operations Center (SOC)

### Aufgaben eines SOC
- **Schwachstellen**: Sicherheitslücken erkennen → Updates oder Patches einspielen  
- **Regelverstöße**: Verstöße gegen interne Sicherheitsrichtlinien erkennen  
  - Beispiel: Hochladen vertraulicher Daten in externe Cloud-Dienste  
- **Unbefugte Aktivitäten**: Nutzung gestohlener Login-Daten erkennen und blockieren  
- **Netzwerkangriffe**: z. B. Klicks auf bösartige Links oder Ausnutzung öffentlicher Server → schnellstmöglich entdecken  

👉 Das SOC übernimmt verschiedene Schutzaufgaben, u. a. **Threat Intelligence**

---

## Threat Intelligence
- **Intelligence braucht Daten** → Daten sammeln, verarbeiten und analysieren  
- **Quellen:**
  - Interne Quellen (z. B. Netzwerkprotokolle)  
  - Öffentliche Quellen (z. B. Foren)  
- **Datenverarbeitung**: Rohdaten so aufbereiten, dass sie analysiert werden können  
- **Analysephase**:
  - Informationen über Angreifer und deren Ziele sammeln  
  - Handlungsempfehlungen und Abwehrmaßnahmen entwickeln  
  - Strategien, Taktiken und Techniken gegen Angreifer festlegen  

---

## Digital Forensics and Incident Response (DFIR)

### Forensik
Wissenschaftliche Methoden zur Untersuchung von IT-Sicherheitsvorfällen und Feststellung von Fakten.  

**Quellen für Analysen:**
- **Dateisystem**: Forensische Abbilder zeigen installierte Programme, Dateien, auch gelöschte Spuren  
- **Arbeitsspeicher**: Malware kann direkt im Speicher laufen → Speicherabbilder liefern wichtige Infos  
- **Systemlogs**: Protokolldateien enthalten viele Hinweise, auch wenn Angreifer versuchen, Spuren zu verwischen  
- **Netzwerkprotokolle**: Zeigen, ob Angriffe stattgefunden haben und in welchem Umfang  

---

### Incident Response
Ein Sicherheitsvorfall kann ein Angriff, eine Fehlkonfiguration oder ein Regelverstoß sein.  

**Phasen der Incident Response:**
1. **Vorbereitung** – Maßnahmen treffen, um Vorfälle möglichst zu verhindern  
2. **Erkennung & Analyse** – Vorfälle identifizieren und deren Schwere bewerten  
3. **Eindämmung, Beseitigung & Wiederherstellung** – Angriff stoppen, entfernen und Systeme reparieren  
4. **Nachbereitung** – Bericht erstellen, Erkenntnisse dokumentieren und Maßnahmen für die Zukunft ableiten  

---

## Malware-Analyse
**Malware = Schadsoftware** (Programme, Dokumente oder Dateien mit schädlicher Funktion).  

### Typen von Malware:
- **Virus**: Befällt Programme, verbreitet sich über Dateien und verändert oder löscht Daten  
- **Trojaner**: Gibt sich als nützliches Programm aus, enthält aber schädliche Funktionen  
- **Ransomware**: Verschlüsselt Dateien und fordert Lösegeld für die Entschlüsselung  

---

## Extra
- Hilfreiche Open-Source-Datenbanken für IP-Reputation und Standortanalysen:  
  - **AbuseIPDB**  
  - **Cisco Talos Intelligence**  
