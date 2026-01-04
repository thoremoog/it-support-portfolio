# Case 01 — DNS Problem (WLAN verbunden, kein Internet)

## 1) Problem
„WLAN verbunden, aber Webseiten laden nicht.“

## 2) Umgebung
- Windows 11
- WLAN Heimnetz
- Browser: Chrome/Edge

## 3) Analyse
1. `ipconfig` geprüft → IP vorhanden
2. `ping 8.8.8.8` → OK
3. `ping google.com` → Fehler
→ Schluss: DNS Problem

## 4) Lösung
DNS manuell gesetzt:
- 8.8.8.8
- 1.1.1.1

## 5) Verifikation
- Webseiten laden
- Ping auf Domain funktioniert

## 6) Lessons Learned
Wenn IP + Ping auf IP geht, aber Domains nicht: DNS zuerst prüfen.
