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

### v1.8.1 (2026-03-15)
- **Widget-Fix**: `await requestWidgetUpdate()` vor Navigation – Race Condition behoben, Widget aktualisiert sich jetzt zuverlässig nach „Fertig"
- **Widget-Config**: Debounce (400 ms) für Live-Updates beim Slider-Ziehen, Floating Mini-Preview beim Scrollen
- **Safe Area**: Statusleiste wird im Movie-Night-Screen korrekt berücksichtigt

### v1.8.0 (2026-03-15)
- **🎬 Movie Night**: Entdecke Filme & Serien mit deinem Partner
  - TMDB-Katalog (200.000+ Titel, deutsch)
  - Filter: Genre, Erscheinungsjahr, Schauspieler (Autocomplete)
  - Gemeinsame Pärchen-Favoriten (gespeichert in Supabase)
  - Film-Details mit Backdrop, Cast-Scroll & YouTube-Trailer
  - Persistente Filtereinstellungen zwischen Sessions
- Date-Ideen Feature entfernt (ersetzt durch Movie Night)
- **Widget-Config überarbeitet**: 3 separate Skalen (Tageszahl / Info-Text / Avatar), 20 Farb-Swatches

### v1.7.0 (2026-03-14)
- **Wunschliste**: Push-Benachrichtigung wenn Partner einen Wunsch erstellt
- Partner kann Wünsche als „gekauft" markieren
- Notizen & Anmerkungsfeld im Detail-Modal für beide Partner

### v1.6.8 (2026-03-14)
- Truth-or-Dare Sync-Bug behoben
- Widget-Slider-Bug im Konfigurations-Screen behoben

### v1.6.7 (2026-03-14)
- Truth or Dare: Multiplayer-Kartenspiel mit Partner (3 Modi: Normal / Brave / FSK18)
- Widget-Fixes: Preview & Platzierung

### v1.6.5 – v1.6.6 (2026-03-14)
- Widget-Anpassungs-Screen: Farben, Schriftgröße, Herz-Toggle, Zeitaufschlüsselung

---

## 📱 Features (aktuell v1.8.1)

| Feature | Beschreibung |
|---------|-------------|
| 🎬 **Movie Night** | TMDB-Entdeckung + Pärchen-Favoriten + Filter + Trailer |
| 💬 **Chat** | Echtzeit, E2E-verschlüsselt, Sticker, Sprachnachrichten, Reaktionen |
| 📸 **Timeline** | Geteiltes Fotoalbum + Tagebuch mit Kommentaren |
| ✨ **Moments** | Zeitgesteuerte Foto-Botschaften (optional ephemeral) |
| 📝 **Notizen** | Geteilte Pärchen-Notizen & To-Do-Listen (Realtime) |
| 🎯 **Gamification** | Level, XP, 24 Badges, Avatar-Frames durch Streaks |
| 🔥 **Truth or Dare** | Multiplayer-Kartenspiel (3 Modi), Realtime-Sync |
| 🎁 **Wunschliste** | Geheime Liste mit Partner-„Gekauft"-Toggle & Push |
| 🖼️ **Widget** | Homescreen-Widget (Tage, Level, Streak) – vollständig anpassbar |
| 🏆 **Meilensteine** | Automatische Zeit-Meilensteine + eigene (mit GPS) |
| 🔔 **Push-Nachrichten** | Chat, Moments, Timeline, Kommentare, Pokes |

---

## 🔧 Systemanforderungen

- Android 7.0 (API 24) oder neuer
- ~150 MB freier Speicher
- Internetverbindung für Sync-Features

---

*Made with ❤️ for couples*
