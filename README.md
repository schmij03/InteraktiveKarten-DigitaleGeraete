# Interaktive Karten: Digitale Geräte im Alltag

Kartenübungen für Medien und Informatik, 1. Sek, Kapitel «Digitale Geräte im Alltag». Die Seiten sind für das iPad (Safari) gemacht. Die Schülerinnen und Schüler verschieben Karten mit dem Finger. Wer nicht ziehen will, tippt zuerst auf eine Karte und dann auf ein Feld.

## Inhalt

| Datei | Inhalt |
| --- | --- |
| `a1e/index.html` | Seite für die Klasse A1e |
| `b1e/index.html` | Seite für die Klasse B1e |

Jede Seite hat drei Übungen:

1. **Vielseitigkeitslinie:** Geräte von «sehr spezialisiert» bis «sehr vielseitig» ordnen (A1e: 8 Karten, B1e: 5 Karten).
2. **Begriffe sortieren:** Hardware, Betriebssystem oder Anwendungssoftware (A1e: 15 Karten, B1e: 9 Karten).
3. **Situationskarten Akku:** Hält der Akku länger oder kürzer? Nach dem Prüfen steht unter jeder Karte der Grund (A1e: 10 Karten, B1e: 6 Karten).

Pro Übung gibt es die Knöpfe «Prüfen», «Neu mischen» und «Herunterladen». Nach dem Prüfen sind richtige Karten grün und fest. Falsche Karten sind rot und lassen sich weiter verschieben. Karten, die noch im Kartenstapel liegen, zählen als nicht gelöst.

## Herunterladen als Bild oder PDF

Unter jeder Übung gibt es den Knopf «Herunterladen». Im Fenster wählen die Schülerinnen und Schüler:

* **Name (freiwillig):** Der Name steht danach oben in der Datei und im Dateinamen.
* **Umfang:** nur die aktuelle Übung oder alle drei Übungen.
* **Format:** «Als Bild» (PNG) oder «Als PDF» (A4, eine Seite pro Übung).

Die Datei zeigt den aktuellen Stand: Karten in den Feldern, Karten im Stapel, nach dem Prüfen auch Farben, Ergebnis und Gründe. Danach folgt eine kleine Vorschau. Mit «Datei speichern» landet die Datei am iPad in der App Dateien im Ordner «Downloads». Mit «Teilen oder sichern» öffnet sich das Teilen-Menü. Dort lässt sich ein Bild auch in Fotos sichern oder direkt weitergeben, zum Beispiel per AirDrop. Der zweite Knopf erscheint nur, wenn das Gerät dies unterstützt.

Beispiel für einen Dateinamen: `A1e_Lea_Muster_Begriffe_sortieren_2026-11-01.png`

Jede Seite ist eine einzige Datei mit HTML, CSS und JavaScript. Sie lädt nichts aus dem Internet. Sie funktioniert darum auch offline: Datei herunterladen und im Browser öffnen.

## Veröffentlichung auf GitHub Pages

1. **Repository anlegen:** Auf github.com anmelden. Oben rechts auf «+» und «New repository» tippen. Einen Namen eingeben, zum Beispiel `digitale-geraete`. Sichtbarkeit «Public» wählen. Auf «Create repository» tippen.
2. **Dateien hochladen:** Im neuen Repository auf «uploading an existing file» oder «Add file» und «Upload files» tippen. Die Ordner `a1e` und `b1e` sowie die Datei `README.md` in das Fenster ziehen. Unten auf «Commit changes» tippen.
3. **Settings öffnen:** Im Repository oben auf «Settings» tippen.
4. **Pages einrichten:** Links auf «Pages» tippen. Unter «Build and deployment» bei «Source» die Option «Deploy from a branch» wählen. Bei «Branch» den Branch `main` und den Ordner `/ (root)` wählen. Auf «Save» tippen.
5. **Link kopieren:** Nach ein bis zwei Minuten die Seite neu laden. Oben steht «Your site is live at …». Diesen Link kopieren und den Ordner anhängen:
   * `https://BENUTZERNAME.github.io/REPOSITORY/a1e/`
   * `https://BENUTZERNAME.github.io/REPOSITORY/b1e/`

   Jeder Klasse nur ihren eigenen Link geben. Die Hauptadresse ohne Ordner zeigt diese README.

Änderungen an den Dateien sind nach dem nächsten Hochladen nach etwa einer Minute online.

## Datenschutz

* Die Seiten sind **öffentlich erreichbar**. Jede Person mit dem Link kann sie öffnen. Auch das Repository ist öffentlich einsehbar.
* Die Seiten enthalten **keine Personendaten**: keine Namen, keine Fotos, keine Noten.
* Bild und PDF entstehen direkt auf dem Gerät. Der freiwillige Name steht nur in dieser Datei. Er wird weder gespeichert noch gesendet.
* Die Seiten speichern nichts und senden nichts. Es gibt keine Cookies, kein localStorage, kein Tracking und keine Anmeldung. Nach dem Neuladen ist alles zurückgesetzt.
* GitHub als Betreiber der Plattform kann technische Zugriffsdaten wie die IP-Adresse erfassen. Das gilt für jede Webseite im Internet.

## Inhalte anpassen

Die Karten stehen in jeder `index.html` im Skript ganz oben unter `var UEBUNGEN`. Dort lassen sich Texte, Lösungen und Gründe ändern. Nach dem Ändern die Seite im Browser testen und die Datei neu hochladen.
