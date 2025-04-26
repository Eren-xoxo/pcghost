# pcghost

Custom Windows OS Installation Guide

## 📥 Download

- Lade das passende Windows 11 24H2 Pro Image hier herunter:
  [Download Update 14](https://ghostclouds.xyz/wp/w11-24h2-pro/)

- Mit [Rufus](https://rufus.ie/) das Image auf einen USB-Stick schreiben.

## ⚙️ Vorbereitung

- Secure Boot im BIOS aktivieren.
- USB-Stick als Bootgerät auswählen.

## 🖥️ Installation

1. Vom USB-Stick booten.
2. Unten auf das Windows-Symbol klicken -> "Install Old Theme" -> "Superlite" auswählen.
3. Festplatte formatieren, löschen und dann Installation starten.
4. Warten, bis das System neu startet.

**Wichtig:**  
Bei Meldungen zur automatischen Installation vom Mainboard ("Auto Install") immer **"Nein"** klicken.

## 🛠️ Ersteinrichtung

1. Time & Location einstellen:
   - Zeitzone setzen.
   - Synchronisieren.

2. Ghost Toolbox starten und folgende Befehle ausführen:

- `99` ➔ Ghost Toolbox Update (usdw)
- `32` ➔ Visual C++ All in One installieren ➔ danach `1` auswählen
- `33` ➔ DirectX online installieren (Bing Bar NICHT mitinstallieren)
- `1` ➔ Action Center deaktivieren
- `2` ➔ Event Viewer Logs löschen (zuerst `2`, dann `1`)
- `3` ➔ Update Cache löschen und Clean Up Now ausführen
- `4` ➔ Ghost Activator starten
- `5` ➔ Hibernation einstellen ➔ dann `3` SysMain deaktivieren
- `8` ➔ Windows Update bis 2077 stoppen
- `52` ➔ Browser installieren
- `ghostmode` ➔ eingeben, dann `7` (Reduced Processes) ➔ dann `2` für Mode 1 wählen

## 🧩 Nachbereitung

- Treiber von der Mainboard-Herstellerseite installieren.
- Rechtsklick auf Desktop -> Power Management -> Dynamic Boost aktivieren.
- Optional: Temp-Dateien bereinigen.

## 🎮 Grafiktreiber Hinweis

- Nvidia-Treiber wird normalerweise automatisch installiert.
- Falls nicht, manuell installieren (kann auf beschädigte Installation hindeuten).

## ✅ Abschluss

Nach der Treiberinstallation ist dein System fertig eingerichtet und bereit zum Einsatz.
