# Kleine Füße, große Welt

Statische Website für den deutschsprachigen Familien-Reiseblog **„Kleine Füße, große Welt"**
— Mama und ihr Sohn Thadeo entdecken die Welt mit Kleinkindaugen. Warmherzige „Traumreisen",
erzählt als Dialog, illustriert im Comic-Look.

Kein Backend, keine Frameworks: reines **HTML + CSS + Vanilla-JavaScript**, mobile-first.

## Seiten
- `index.html` — Startseite (Hero, „Reise des Monats", aufziehende Comic-Galerie, Newsletter)
- `reisen.html` — Reise-Archiv mit **Filter** (Jahreszeit × Fahrzeug × Region, UND-verknüpft)
- `reise-beispiel.html` — Muster-Reiseseite (Ankommen · Dialog · Für die Großen · Fundstück · Praktisch · Weiterlesen)
- `ratgeber.html` + `ratgeber-herbstcamping.html` — Ratgeber-Übersicht und ausformulierter Artikel
- `reisearten.html` · `weltkarte.html` · `ausmalbilder.html` · `videos.html` · `buecherregal.html` · `shop.html` · `ueber-uns.html`
- `impressum.html` · `datenschutz.html` — Pflichtseiten (Platzhalter)
- `assets/` — `styles.css` (Design-System, Comic-Look), `main.js`, `filter.js`
- `content/` — aufgehobene Rohinhalte (z. B. Herbstcamping-Restcontent) für spätere Verwendung

## Lokal ansehen
```bash
python3 -m http.server 8000
# dann http://localhost:8000 im Browser öffnen
```

## Vor dem Livegang ausfüllen
- **Impressum** und **Datenschutzerklärung** enthalten Platzhalter („VOR VERÖFFENTLICHUNG AUSFÜLLEN").
- **Illustrationen**: Die `[Comic: …]`-Flächen sind Platzhalter für spätere Bilder.
- **Newsletter-/Download-Formulare** sind Attrappen — Anbindung an einen Dienst
  (Mailchimp, CleverReach, Brevo o. ä.) ist im Code als `TODO` markiert.
- **Affiliate-Links** (mit `*` gekennzeichnet) durch echte Partnerlinks ersetzen.

## Hosting
Da alles statisch ist, läuft die Seite auf jedem Static-Host (GitHub Pages, Netlify,
Vercel, klassisches Webhosting). Für GitHub Pages einfach den `main`-Branch als Quelle wählen.
