# Mendura-Website Version 2 online bringen

Ziel: **https://menduradigital.de/** (Domain ist gekauft, DNS ist fertig ✓)

## 1. Repo anlegen (falls noch nicht geschehen)
github.com → Konto MenduraDigital → **+** → **New repository**
→ Name exakt `menduradigital.github.io` → **Public** → „Add a README" → Create.

## 2. ALLE Dateien aus diesem Paket hochladen
Im Repo: **Add file → Upload files** → alle 15 Dateien auswählen:
- index.html, datenschutz.html, impressum.html
- die 12 Bilddateien (s1…s10, .webp)
→ **Commit changes**.
(Mobil ggf. unten „Desktop version" wählen, dann geht Mehrfach-Upload.)

Hinweis: Die Bilder müssen NEBEN der index.html liegen (kein Unterordner).

## 3. Pages aktivieren
Repo → **Settings** → **Pages** → Source „Deploy from a branch",
Branch **main**, **/ (root)** → Save.

## 4. Deine Domain verbinden
Auf derselben Pages-Seite → Feld **Custom domain** → `menduradigital.de`
eintragen → Save. GitHub prüft die DNS-Einträge (sind schon gesetzt);
zeigt es „Pending", einfach ein paar Minuten später neu laden.
Sobald grün: Häkchen **Enforce HTTPS** setzen (Zertifikat kann bis zu
1 Stunde dauern). GitHub legt dabei eine Datei `CNAME` ins Repo – gewollt.

## 5. Später ergänzen (jeweils 2 Minuten, direkt auf GitHub editierbar)
- **impressum.html + datenschutz.html:** Platzhalter `[c/o ZERODOX-Adresse …]`
  und USt-IdNr ersetzen, sobald vorhanden.
- **Dein Foto:** Bild als `foto_alexander.jpg` ins Repo hochladen – die
  Seite zeigt es dann automatisch im „Warum Mendura"-Abschnitt an
  (ohne die Datei bleibt der Bereich unsichtbar, nichts wirkt kaputt).
- **Play-Store-Link:** Nach dem Launch in index.html den Knopf
  „Bald bei Google Play" gegen den echten Store-Link tauschen (sag mir
  Bescheid, ich liefere dir den fertigen Schnipsel).

## 6. Play Console (wenn Konto-Verifizierung durch ist)
- Website der Organisation: `https://menduradigital.de/`
- Datenschutz-URL der App: `https://menduradigital.de/datenschutz.html`
- Inhaberschaft bestätigen: search.google.com/search-console →
  „URL-Präfix" → `https://menduradigital.de/` → HTML-Datei-Methode:
  die Prüfdatei einfach mit ins Repo hochladen.

## Enthalten in Version 2
Typenschild-Hero (+ Zeile „Einarbeitung: integriert") · Galerie mit 8
Screenshots in Handy-Rahmen · Kernpunkte · Schraubi-Schulung (2 Bilder) ·
Rangliste (1 Bild) · Gründergeschichte · Fahrplan (Play-Badge „Bald
verfügbar", aktive Weiterentwicklung, PC-Zentrale) · Sticky-Navigation ·
Datenschutz (DE/EN) · Impressum.
