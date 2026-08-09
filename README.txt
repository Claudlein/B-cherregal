BookVault V1.0.1 – korrigierte iPhone-Web-App

Änderungen gegenüber V1.0:
- robusterer App-Start
- Service Worker mit neuer Cache-Version, damit keine alte fehlerhafte Version festhängt
- Genre- und Trope-Auswahl wird korrekt gespeichert
- Cover direkt aus iPhone-Fotos auswählen
- Bild-URL weiterhin möglich
- PWA Scope ergänzt

Für GitHub Pages:
1. index.html, manifest.json und sw.js im Repository-Hauptverzeichnis ersetzen.
2. Einige Sekunden warten.
3. Safari komplett schließen und die Seite neu laden.
4. Falls die alte PWA installiert ist: vom Home-Bildschirm entfernen und die neue Seite erneut „Zum Home-Bildschirm“ hinzufügen.
