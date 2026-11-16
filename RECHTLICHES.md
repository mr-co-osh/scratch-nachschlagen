# Rechtliches für die Seiten „Profil Coding“

Stand 16.11.2026 (Kontaktdaten abgeglichen mit der Schulhomepage). Übernommen aus dem Repository `physik-energie` (Seitenfuß und `datenschutz.html`), angepasst an die Scratch-Seiten. Umsetzung im Code: `std_page.py` (Kopfzeile, Seitenfuß, `datenschutz.html`).

## Geltungsbereich

Das Impressum der Schule und diese Datenschutztexte gelten **nur für Seiten, die die Lehrkraft dienstlich für Schüler:innen nutzt**. Private Projekte im Konto mr-co-osh bekommen weder Schul-Impressum noch Schul-Datenschutztexte; dafür wird gesondert entschieden.

## 1. Impressum

> **Oberschule an der Hermannsburg**
> Hermannsburg 32f
> 28259 Bremen
> Telefon: 0421-361-15960
> E-Mail: 505@schulverwaltung.bremen.de
>
> Vertreten durch den Schulleiter Achim Kaschub

Der Schulname steht nur im Impressum (STANDARDS.md, Abschnitt 2). Gültige E-Mail-Adresse der Schule: 505@schulverwaltung.bremen.de (nicht 505@schule.bremen.de).

## 2. Datenschutz im Seitenfuß (jede Seite)

Seitenfuß im Stil der Energie-Seiten: Pflichtsatz, darunter drei Schalter ▸ Datenschutz ▸ Impressum ▸ Lizenzen; es ist immer nur ein Bereich aufgeklappt, ohne JavaScript ist alles offen.

- **Keine Datensammlung:** Diese Seite erhebt keine personenbezogenen Daten. Keine Anmeldung, keine Cookies, kein Tracking, keine Formulare, die Daten verschicken.
- **Speicherung nur im Browser:** je Seite angepasst (siehe Abschnitt 4). Du kannst die Daten in den Einstellungen deines Browsers löschen.
- **Hosting:** Die Seite liegt bei GitHub Pages (GitHub, Inc., USA). GitHub verarbeitet beim Aufruf technisch notwendige Daten wie deine IP-Adresse. Link: Datenschutzerklärung von GitHub.
- **Nichts von fremden Servern:** Schriften, Skripte und Bilder werden von dieser Seite selbst geladen.
- **Deine Rechte:** Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung, Beschwerde bei einer Datenschutz-Aufsichtsbehörde.
- **Verantwortlich:** siehe Impressum.
- **Behördlicher Datenschutzbeauftragter:** Sven Venke-Caprarese, datenschutz nord GmbH, Konsul-Smidt-Straße 88, 28217 Bremen, Telefon 0421-69 66 32-0, office@datenschutz-nord.de, www.dsn-group.de
- Link „Ausführliche Datenschutzhinweise“ → `datenschutz.html`

## 3. Ausführliche Datenschutz-Seite (`datenschutz.html` in jedem Repository)

Aufbau wie bei Energie: Kurz gesagt · Verantwortlich (siehe Impressum) · Datenschutzbeauftragter · Hosting bei GitHub Pages (mit Anschrift GitHub, Inc., 88 Colin P. Kelly Jr. Street, San Francisco, CA 94107, USA) · Speicherung im Browser · Schriften · Links zu anderen Seiten · Deine Rechte (zuständig: die Landesbeauftragte für Datenschutz und Informationsfreiheit der Freien Hansestadt Bremen) · Stand.

**Noch offen (Platzhalter wie bei Energie):**
- Rechtsgrundlage: [Art. 6 Abs. 1 lit. e DSGVO i. V. m. dem Bremischen Schuldatenschutzgesetz – bitte mit der/dem Datenschutzbeauftragten abstimmen]
- Stand: [Datum]

## 4. Speicherung je Seite

| Seite | Speicherung | Text im Fuß |
|---|---|---|
| scratch-nachschlagen | nichts | Diese Seite speichert nichts – auch nicht im Browser. |
| scratch-hilfen | sessionStorage: freigeschaltete Hilfen der Sitzung | Freigeschaltete Hilfen werden nur bis zum Schließen des Browsers gemerkt (sessionStorage) und nicht übertragen. |
| scratch-debugging | localStorage: gelöste Aufgaben | Gelöste Aufgaben werden nur im Speicher deines Browsers auf diesem Gerät abgelegt (localStorage) und nicht übertragen. |

Rechtsgrundlage für die Speicherung im Browser: § 25 Abs. 2 Nr. 2 TDDDG (für die selbst aufgerufene Funktion nötig, keine Einwilligung erforderlich).

## 5. Schriften (alle lokal in `assets/fonts/`, Lizenztexte in `assets/fonts/LIZENZEN.txt`)

Ausgewählt nach Lesbarkeit (der Inhalt steht im Vordergrund) und passend zu den Scratch-Blöcken:

| Schrift | Verwendung | Copyright | Lizenz | Bezug |
|---|---|---|---|---|
| Atkinson Hyperlegible Next (400, 700, 400 kursiv) | Fließtext und Überschriften | 2020–2024 The Atkinson Hyperlegible Next Project Authors | SIL OFL 1.1 | Fontsource 5.3.0, Web-Teilmengen latin/latin-ext |
| Atkinson Hyperlegible Mono (400) | Code und Blocknamen im Text | 2020–2024 The Atkinson Hyperlegible Mono Project Authors | SIL OFL 1.1 | Fontsource 5.3.0, Web-Teilmengen latin/latin-ext |
| TeX Gyre Heros (Regular, Bold) | Beschriftung der Scratch-Blöcke (gleiche Maße wie beim Zeichnen der Blöcke) | © 2007–2018 Bogusław Jackowski und Janusz M. Nowacki | GUST Font License | Debian-Paket fonts-texgyre, unveränderte OTF |

Dazu fremder Code: **scratchblocks** (© 2013–2021 Tim Radvan, MIT-Lizenz), Lizenztext `LICENSE-scratchblocks.txt`.

Hinweis im Fuß: „Scratch ist ein Projekt der Scratch Foundation. Diese Seite steht in keiner Verbindung zur Scratch Foundation.“
