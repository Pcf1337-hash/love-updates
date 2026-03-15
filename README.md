# Love Tracker – Releases

[![Latest](https://img.shields.io/github/v/release/Pcf1337-hash/love-updates?label=Latest&color=ff6b8a)](https://github.com/Pcf1337-hash/love-updates/releases/latest)

> Dieses Repository enthält ausschließlich die APK-Releases der **Love Tracker** App.  
> Source Code & Issues: [Pcf1337-hash/love](https://github.com/Pcf1337-hash/love)

---

## 📥 Installation

1. Auf dem Android-Gerät **Einstellungen → Sicherheit → Unbekannte Quellen** aktivieren  
   *(oder „Installation aus unbekannten Quellen" für den Browser/Datei-Manager erlauben)*
2. Neueste APK herunterladen → **[Releases](https://github.com/Pcf1337-hash/love-updates/releases/latest)**
3. APK öffnen und installieren
4. Beim ersten Start die Einrichtung durchlaufen

> **Hinweis:** Die App prüft automatisch auf neue Versionen und zeigt einen In-App-Update-Dialog.

---

## 📋 Changelog

### v1.8.2 (2026-03-15)
- **🎬 Movie Night: Watchlist-System**
  - Neuer Tab „Watchlist" mit zwei Sektionen: **Noch zu Schauen** & **Bereits Gesehen**
  - Titel zur Watchlist hinzufügen mit **+**-Button auf der Karte im Entdecken-Tab
  - Als gesehen abhaken (✓) → Titel wandert in „Bereits Gesehen" mit Datum
  - Zurücksetzen (↩) und Löschen (🗑) im „Bereits Gesehen"-Bereich
  - **Favorit ⭐** innerhalb der Watchlist: Pinnt Titel nach oben + leuchtender Rahmen
  - Im Entdecken-Tab: horizontale „Noch zu Schauen"-Leiste oben (pinned Titel leuchten)
  - Watchlist ist couple-synchron – beide Partner sehen dasselbe in Echtzeit (Supabase)
- **Filter & Sortierung**
  - Sortierung wählbar: Beliebtheit, Neueste, Beste Bewertung, Einspielergebnis
  - Filterauswahl bleibt beim erneuten Öffnen des Filter-Sheets erhalten

### v1.8.1 (2026-03-15)
- **Widget-Fix**: Race Condition behoben, Widget aktualisiert sich nach „Fertig" zuverlässig
- **Widget-Config**: Debounce (400 ms) + Floating Mini-Preview beim Scrollen
- **Safe Area**: Statusleiste im Movie-Night-Screen korrekt behandelt

### v1.8.0 (2026-03-15)
- **🎬 Movie Night**: Entdecke Filme & Serien mit deinem Partner
  - TMDB-Katalog (200.000+ Titel, deutsch), Filter, Favoriten, Film-Details, Trailer

### v1.7.0 (2026-03-14)
- **Wunschliste**: Push-Benachrichtigung, Partner-Kaufstatus, Notizen

### v1.6.8 (2026-03-14)
- Truth-or-Dare Sync-Bug & Widget-Slider-Bug behoben

### v1.6.7 (2026-03-14)
- Truth or Dare: Multiplayer-Kartenspiel (Normal / Brave / FSK18)

### v1.6.5 – v1.6.6 (2026-03-14)
- Widget-Anpassungs-Screen: Farben, Schriftgröße, Herz-Toggle, Zeitaufschlüsselung

---

## 📱 Features (aktuell v1.8.2)

| Feature | Beschreibung |
|---------|-------------|
| 🎬 Movie Night | Filme & Serien entdecken, Watchlist (Noch zu Schauen / Bereits Gesehen), couple-sync |
| 💬 Chat | Textnachrichten, Bilder, Sprachnachrichten, Reaktionen |
| 📔 Tagebuch | Gemeinsame Einträge mit Fotos & Standort |
| 📸 Fotoalbum | Pärchen-Fotoalbum mit Kommentaren |
| 🎯 Challenges | Tägliche & individuelle Pärchen-Challenges |
| 🎰 Truth or Dare | Multiplayer-Kartenspiel mit 3 Modi |
| 🎁 Wunschliste | Wünsche mit Kaufstatus & Notizen |
| 💌 Liebesbriefe | Private Briefe schreiben & versenden |
| 📅 Meilensteine | Wichtige Daten & Jahrestage tracken |
| 🧩 Widget | Konfigurierbares Homescreen-Widget |
| 🔔 Push-Notifications | Echtzeit-Benachrichtigungen |
| 🌙 Dark/Light Mode | Automatisch oder manuell |
