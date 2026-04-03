# WCI Interactive — World Cleanup Institute

Interactive single-page website for the **World Cleanup Institute (WCI)** and the **We Create Future (WCF)** programme.

## Live-URL (nach GitHub Pages Setup)

`https://<dein-username>.github.io/wci-interactive`

oder mit eigener Domain:

`https://wecreatefuture.world`

---

## Inhalt

```
wci-interactive/
├── index.html      ← Komplette Website (alle Assets inline)
├── CNAME           ← Custom Domain (anpassen!)
├── start.sh        ← Lokaler Dev-Server (macOS / Linux)
├── start.bat       ← Lokaler Dev-Server (Windows)
└── README.md
```

## Seiten

| Seite | Beschreibung |
|-------|-------------|
| Home | WCI Übersicht |
| We Create Future | Programmseite mit Kits, Jersey, Scholarship, Partner |
| WCD Campaign | World Cleanup Day Kampagnenseite |

---

## Lokal starten

**macOS / Linux:**
```bash
bash start.sh
```

**Windows:**
Doppelklick auf `start.bat`

Öffnet automatisch `http://localhost:8080`

---

## GitHub Pages aktivieren

1. Repo auf GitHub pushen
2. **Settings → Pages → Source:** `main` / `/ (root)`
3. Speichern → Site ist unter `<username>.github.io/wci-interactive` erreichbar

## Custom Domain (Cloudflare)

1. `CNAME`-Datei anpassen: eigene Domain eintragen
2. In Cloudflare DNS: A-Records auf GitHub Pages IPs setzen
3. In GitHub Pages: Custom Domain eintragen + HTTPS erzwingen

Detaillierte Anleitung: siehe Projekt-Dokumentation.

---

## Tech Stack

- Plain HTML / CSS / JS — keine Abhängigkeiten
- Alle Bilder & Logos als Base64 eingebettet
- Keine Build-Tools nötig
