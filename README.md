# LesePilot PWA – Demo

Eine eigenständige, mobile Progressive Web App (PWA), die als Lernprototyp dient.

## Test im Browser

Für einen einfachen lokalen Ansichtstest `index.html` in einem Browser öffnen. Mikrofonzugriff oder Installation sind beim direkten Öffnen einer lokalen Datei unter Umständen nicht verfügbar.

## Veröffentlichen auf GitHub Pages (HTTPS)

1. Ein neues öffentliches GitHub-Repository erstellen, z. B. `lesepilot`.
2. **Den Inhalt** dieses Ordners (nicht nur die ZIP-Datei) in die oberste Ebene des Repositorys hochladen: `index.html`, `app.js`, `styles.css`, `manifest.webmanifest`, `sw.js` und den Ordner `icons`.
3. Unter **Settings → Pages → Build and deployment** `Deploy from a branch`, dann `main` und `/ (root)` auswählen und speichern.
4. GitHub zeigt nach Veröffentlichung die HTTPS-Adresse an (typisch `https://BENUTZERNAME.github.io/lesepilot/`).
5. Die Adresse im Chrome-Browser auf Android öffnen und im Browsermenü **Zum Startbildschirm hinzufügen** oder **App installieren** wählen.

Alternativ ist jeder beliebige statische HTTPS-Webhost geeignet.

## Funktionen

- Fester Demo-Einstiegstest (18 Aufgaben), manuelle Bewertung
- Einfache Übungsempfehlung anhand der Ergebnisse
- Üben mit Lauten, Silben, Wörtern und Sätzen
- Optionale experimentelle Spracherkennung mit Web Speech API (`de-DE`)
- Optionale grobe Sprechbeginn-Erkennung per Audioanalyse
- Lehrpersonenübersicht
- Lokale Datenspeicherung auf dem Gerät; keine eigene Serverdatenbank
- Offline-Anzeige der Oberfläche nach erstmaligem Laden (Spracherkennung kann weiterhin eine Internetverbindung benötigen)

## Grenzen

**Keine pädagogisch oder sprachdiagnostisch validierte App.** Das Wortmaterial, die Stufen und die automatischen Empfehlungen sind illustrativ und entsprechen keinem geprüften vollständigen Reuter-Liehr-Katalog. Die Browser-Spracherkennung kann falsche Ergebnisse liefern; Sprachaufnahmen können durch einen externen Dienst des Browsers verarbeitet werden. Bei einzelnen Lauten ist die automatische Erkennung häufig unzuverlässig. Die Lehrperson bestätigt jede Bewertung. Die Timing-Analyse ist eine grobe Erkennung des Sprechbeginns und keine wissenschaftlich abgesicherte Messung der Automatisierung.

Keine echten Kinder- oder personenbezogenen Daten ohne entsprechende Datenschutzprüfung verwenden.
