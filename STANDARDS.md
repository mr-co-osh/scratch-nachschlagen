# Standards für das Unterrichtsmaterial „Profil Coding“

Diese Regeln gelten dauerhaft für alle Seiten dieses Projekts – für bestehende und für jede neue Seite.

**Hintergrund:** Die Seiten sind Unterrichtsmaterial für Schüler:innen (Profil Coding, Sekundarstufe I, Bremen), liegen öffentlich auf GitHub Pages (Konto mr-co-osh) und werden per Link weitergegeben.

Repositories dieses Projekts: `scratch-nachschlagen`, `scratch-hilfen`, `scratch-debugging`.

## 1. Technik und Datenschutz

- Jede HTML-Seite beginnt mit:
  ```html
  <meta charset="utf-8">
  <meta name="robots" content="noindex, nofollow, noarchive">
  ```
- Nichts von fremden Servern laden: keine Google Fonts, keine CDNs, keine eingebetteten Videos, Editoren oder Spielwiesen (YouTube, CodePen, Replit, Scratch-Einbettungen usw.). Schriften und Bibliotheken (z. B. p5.js) liegen lokal im Repository, mit Lizenzdatei. Externe Angebote höchstens als normaler Link, den man bewusst anklickt.
- Keine Anmeldung, keine Cookies, kein Tracking, keine Formulare, die Daten verschicken. Fortschritt oder Code der Schüler:innen nur im Browser speichern (localStorage), mit try/catch.
- Keine Aufgaben, die ein Konto bei einem externen Dienst verlangen, ohne ausdrückliche Freigabe der Lehrkraft.
- Keine API-Schlüssel, Passwörter oder Zugangsdaten im Code.

## 2. Personen

- Keine echten Namen, Fotos, Stimmen oder Arbeiten von Schüler:innen auf den Seiten oder im Repository. Beispielnamen sind erfunden.
- Kein Name der Schule und keine Kontaktdaten, außer im Impressum.

## 3. Inhalte und Urheberrecht

- Texte, Aufgaben, Code-Beispiele, Bilder und Töne sind selbst erstellt oder stehen unter einer freien Lizenz, die genannt wird. Nichts aus Schulbüchern, Arbeitsheften, Online-Kursen oder Tutorials übernehmen, auch nicht leicht umformuliert.
- Fremden Code nur mit passender Lizenz (MIT, Apache, CC0 o. Ä.) und mit Lizenzhinweis verwenden.
- Keine Logos, Markenfiguren oder Screenshots fremder Programme.

## 4. Seitenfuß auf jeder Seite

- Satz: „Eigenes Unterrichtsmaterial. Kein offizielles Material der Bremer Bildungsbehörde. Dein Fortschritt wird nur in diesem Browser gespeichert.“
- Aufklappbarer Datenschutzhinweis mit den Punkten: keine Datensammlung, Speicherung nur im Browser, Hosting über GitHub Pages (GitHub, Inc., USA, verarbeitet die IP-Adresse), nichts von fremden Servern, Rechte nach DSGVO, Verantwortlicher.
- Impressum: Platzhalter vorsehen. Die Angaben liefert die Lehrkraft nach. Nichts erfinden.

## 5. Arbeitsweise

- Vor jeder Änderung den aktuellen Stand holen (`git pull`), nie mit force pushen. Andere Sitzungen ändern dieselben Repositories.
- Zuerst alle bestehenden Seiten gegen diese Regeln prüfen und eine kurze Liste der Abweichungen vorlegen. Erst nach Okay der Lehrkraft ändern. Inhaltliche Aufgaben nicht ungefragt umschreiben.
- Nach jeder Änderung die Seite im Browser laden und prüfen, dass keine Anfrage an einen fremden Server geht.
