WINTER ARC – Installationspaket

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
- Das Tages- und Wochen-Scoring nutzt gewichtete Aufgaben. Der Wochenwert ist der Durchschnitt der Tagesprozente von Montag bis zum aktuellen Tag; noch kommende Tage werden nicht als 0 gewertet.
- Die Trainingsübungen sind ein editierbarer Startvorschlag, keine medizinische oder individuelle Trainingsanweisung. Passe Lasten und Umfang an deine Erfahrung und Erholung an.
