WINTER ARC V2.0 – Update- und Installationspaket

INHALT
- index.html: die App
- manifest.webmanifest: PWA-Metadaten
- sw.js: Offline-Cache
- icon-192.png / icon-512.png: App-Symbole

INSTALLATION AUF DEM IPHONE
1. Lade den gesamten Ordner auf einen HTTPS-fähigen statischen Webhost (z. B. GitHub Pages oder einen anderen Static-Hosting-Anbieter).
2. Öffne die veröffentlichte HTTPS-Adresse in Safari auf dem iPhone.
3. Tippe auf Teilen -> Zum Home-Bildschirm -> Hinzufügen.
4. Starte die App über das neue Home-Bildschirm-Symbol.

WICHTIG
- Eine PWA benötigt für Service Worker und Offline-Funktion HTTPS (localhost ist die Ausnahme).
- Aufgaben, Trainingsplan und Tageshistorie werden lokal im Browser auf diesem Gerät gespeichert.
- Exportiere in Setup regelmäßig ein JSON-Backup. Browserdaten löschen kann lokale App-Daten entfernen.
- Der Tageswechsel wird beim Öffnen, Fokuswechsel oder erneuter Aktivität erkannt. iOS führt eine Web-App nicht garantiert exakt um 00:00 Uhr im Hintergrund aus.
- Die drei Mahlzeiten (Frühstück, Mittagessen, Abendessen) zählen zusammen wie ein To-do mit Gewicht 2. Jede Mahlzeit zählt gleich viel.
- Gym-Übungen haben jeweils ein eigenes Gewichts-Feld; Sport- und Erholungsübungen haben keines. Trainings-Check-ins verändern den Tagesbalken nicht.
- Das Tages- und Wochen-Scoring nutzt gewichtete Aufgaben und die Mahlzeiten. Der Wochenwert ist der Durchschnitt der Tagesprozente von Montag bis zum aktuellen Tag; noch kommende Tage werden nicht als 0 gewertet.
- Die Trainingsübungen sind ein editierbarer Startvorschlag, keine medizinische oder individuelle Trainingsanweisung. Passe Lasten und Umfang an deine Erfahrung und Erholung an.

UPDATE EINER BEREITS VERÖFFENTLICHTEN V1-APP
1. Vorher in der bisherigen App unter Setup -> Daten exportieren wählen.
2. Dieses ZIP entpacken.
3. Im bestehenden GitHub-Repository die sechs Dateien im Stammverzeichnis hochladen und die vorhandenen Dateien überschreiben.
4. Änderungen committen. Die bestehende GitHub-Pages-Adresse bleibt gleich.
5. App in Safari neu laden bzw. die Home-Bildschirm-App vollständig schließen und erneut öffnen.

Die V2 verwendet denselben lokalen Speicher-Schlüssel wie V1 und migriert die gespeicherten Daten. Ein Backup vor dem Update ist trotzdem sinnvoll.
