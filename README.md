# TRENDHUNTER AI v2 — statische mobile Browser-App

## Veröffentlichung auf GitHub Pages

1. **Alle Dateien dieses ZIP-Inhalts** (index.html, app.js, manifest.webmanifest, README.md) in das Hauptverzeichnis des öffentlichen Repositorys `trendhunter-ai` hochladen. ZIP zuerst entpacken, keinen übergeordneten Ordner hochladen.
2. GitHub → Repository → Settings → Pages → Deploy from a branch → main → /(root) → Save.
3. Nach Bereitstellung `https://BENUTZERNAME.github.io/trendhunter-ai/` auf dem iPhone in Safari öffnen.

## Echte Datenanbindung

Die Registerkarte **Live-Daten** nutzt `https://hn.algolia.com/api/v1/search` ohne API-Schlüssel. Sie vergleicht Suchtreffer in Hacker-News-Beiträgen und -Kommentaren in zwei aufeinanderfolgenden 30-Tage-Zeitfenstern und zeigt aktuelle Treffer. Abrufe erfolgen direkt im Browser; Internet und CORS-Freigabe des Anbieters sind nötig. Die API kann sich ändern oder ausfallen. Das ist ein echter Diskussionsindikator, aber keine Verkaufs- oder Nachfragevalidierung und stark technologieorientiert. Für alle Branchen stehen manuelle Recherchelinks zu Alibaba, Amazon, eBay, Google Trends, TikTok etc. bereit.

## Sonstiges

- Keine Backend-/Cloud-/Datenbankkosten; kein API-Schlüssel.
- Lokale Merkliste mit CSV-Export und JSON-Backup.
- Gewinnrechner ist eine grobe Schätzung, nicht steuer- oder betriebswirtschaftlich vollständig.
- Keine automatische Erfassung von Alibaba-/Amazon-Preisen und keine garantierte Millionenseller-Prognose.
- Dateien können auch lokal mit `python -m http.server 8000` getestet werden.
