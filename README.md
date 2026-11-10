# Auto-Mods für 7 Days to Die

Fertige Windows-Releases der Auto-Mods von Bloody. Das aktuelle Paket steht unter **Releases** (rechts) und ist
gebaut für **7 Days to Die V 3.4.0 (b10)**.

## Die Mods

- **AutoCore** – gemeinsame Grundlage aller Auto-Mods: Einstellungen, Einstellungsmenü im Spiel, Mehrspieler
- **AutoStash** – Items per Taste oder Knopf in passende Kisten in der Nähe ablegen, Kisten sortieren
- **AutoCraft** – Zutaten für Herstellen, Reparieren und Blockaufwertung direkt aus Kisten in der Nähe nehmen
- **AutoStations** – Arbeitsstationen automatisch bedienen: Sammler und Werkstationen leeren und nachfüllen,
  Pflanzbeete ernten und neu bepflanzen, Dauer-Herstellen, gepflanzte Bäume fällen (im Menü einschaltbar)
- **AutoPower** – Generatoren und Fallen aus Kisten nachfüllen, Strom-Monitor mit Produktion und Verbrauch
- **AutoCams** – benannte Bewegungsmelder-Kameras mit Alarm und Kamera-Monitor mit Livebild

## Installation für Spieler

1. Unter **Releases** die Datei `AutoMods-Installer.exe` herunterladen.
2. 7 Days to Die vollständig beenden.
3. Die EXE starten und den erkannten Spielordner bestätigen.
4. Das Spiel ohne Easy Anti-Cheat starten – am einfachsten über den Installer (auch per Desktop-Verknüpfung).

## Was der Installer kann

- findet das Spiel automatisch, auch in zusätzlichen Steam-Bibliotheken
- lädt das aktuelle Mod-Paket, prüft Signatur und SHA-256-Prüfsumme und installiert erst dann
- zeigt vor dem Installieren, was neu ist
- zeigt seine eigene Version, meldet veraltete Mods und aktualisiert sich bei Bedarf selbst
- sichert vorhandene Auto-Mods und behält im Spiel geänderte Einstellungen
- kann die Auto-Mods auch wieder entfernen
- lässt den Vanilla-Mod `0_TFP_Harmony` und fremde Mods unangetastet

Wenn `0_TFP_Harmony` fehlt: in Steam die installierten Spieldateien auf Fehler überprüfen.

## Mehrspieler

Server und alle Spieler brauchen **dieselben Mod-Versionen** und dieselbe Spielversion, und auf dem Server muss
Easy Anti-Cheat aus sein. Nach einem Update auf dem Server installiert jeder Spieler das neue Paket einfach erneut
mit dem Installer.

## Release-Dateien

- `AutoMods-Installer.exe` – eigenständiger Windows-x64-Installer
- `AutoMods-Paket.zip` – alle sechs fertigen Mod-Ordner
- `AutoMods-Paket.sha256` – SHA-256-Prüfsumme des ZIP-Pakets
- `AutoMods-Manifest.json` – Versionen, Spielversion, Neuigkeiten und Prüfsummen des Releases
- `AutoMods-Manifest.sig` – Signatur des Manifests; der Installer installiert nur Pakete mit gültiger Signatur

Der Quellcode und die Entwicklungsdaten werden nicht in diesem öffentlichen Download-Repository verwaltet.
