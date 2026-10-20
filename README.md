# GarageLog – Fahrzeug- und Wartungsmanager

Eine kostenlose Web-App ohne Benutzerkonto. Erstellt als Lernprojekt mit HTML, CSS und JavaScript in **einer Datei**.

## Funktionen

- Fahrzeuge hinzufügen und Kilometerstände aktualisieren
- Nächsten Ölwechsel nach Kilometerstand verfolgen
- Wartungen mit Datum, Kategorie, km-Stand, Kosten und Notiz erfassen
- Dokumentierte Ausgaben summieren und Wartungshistorie anzeigen
- JSON-Backups exportieren und importieren
- Responsive Darstellung am PC und Smartphone

## Sofort testen

`index.html` im Browser öffnen und Testfahrzeug anlegen. Im Browser mit aktivem lokalen Speicher bleiben die Daten bei weiteren Aufrufen erhalten.

## Kostenlos über GitHub Pages veröffentlichen

1. Auf [github.com](https://github.com) ein kostenloses Konto erstellen oder anmelden.
2. Oben rechts **+ > New repository**; Name `garagelog` auswählen, Sichtbarkeit **Public**, Repository erstellen.
3. Auf **Add file > Upload files** klicken. `index.html` und optional `README.md` aus diesem Ordner hochladen. Unten **Commit changes** bestätigen.
4. Im Repository **Settings > Pages** öffnen.
5. Unter **Build and deployment** die **Source: Deploy from a branch** auswählen, darunter **main** und **/(root)** auswählen, dann **Save**.
6. Nach der Veröffentlichung ist die App normalerweise unter `https://DEIN-BENUTZERNAME.github.io/garagelog/` erreichbar.

Die URL ist ein Muster, kein bereits angelegter Link.

**Wichtig:** Die Web-App ist öffentlich sichtbar, ihre Fahrzeugdaten werden aber nur lokal im jeweiligen Browser gespeichert. Nicht automatisch zwischen Geräten synchronisiert. Browserdaten können gelöscht werden, daher regelmäßig ein JSON-Backup herunterladen. Der Name und der Code der App sind beim öffentlichen Repository für jeden sichtbar. Keine Passwörter, Kennzeichen oder andere private Daten im Quellcode hinterlegen.

## Code verstehen

Die Datei `index.html` enthält drei Teile:

- **HTML** – Aufbau, Formulare und Überschriften
- **CSS** – Gestaltung, Farben und Layout
- **JavaScript** – Funktionen, Berechnungen und lokale Datenspeicherung

Um den Titel zu ändern, `<title>...` und die sichtbare Überschrift ändern. Farben stehen im CSS am Anfang unter `:root`. Auf GitHub kannst du die Datei im Repository mit dem Stiftsymbol bearbeiten und die Änderungen committen.
