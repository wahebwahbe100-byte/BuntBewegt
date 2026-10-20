BuntBewegt — responsive Überarbeitung, Oktober 2026

START
index.html öffnen. Alle neun Seiten funktionieren ohne Build-Schritt und ohne externe JavaScript-Bibliotheken.

NEU
- Vier eigene Hochformat-Motive für Mobilgeräte, jeweils als 640- und 1024-Pixel-WebP. Unter 741 px wird automatisch das passende Motiv geladen.
- Die vier Desktop-Motive bleiben erhalten und werden als optimierte WebP-Dateien geladen. Nicht benötigte Bildoriginale sind aus dem kompakten Mobilpaket entfernt.
- Neuer grüner Button „Alle Angebote ansehen“ mit dezenten Markenfarben.
- Ruhigere „Unsere Wirkung“-Galerie mit mehr Freiraum und vergrößerbaren Bildern.
- „So einfach seid ihr dabei“ als responsive Drei-Schritte-Sektion direkt vor „Gut zu wissen / Noch neugierig?“.
- Mobile Navigation bis 900 px: animierter Öffnen-/Schließen-Button, Hintergrundfläche, Escape-Schließen, Tastatur-Fokusführung und Scroll-Sperre.
- Sanfter Bildwechsel alle 4 Sekunden mit Pfeilen, Punkten, Pause und Wischgeste. Der Wechsel pausiert bei Tastaturfokus, geöffnetem Menü und auf Wunsch über die Pausentaste.
- Dezente Einblendungen. Die Systemeinstellung „Bewegung reduzieren“ wird berücksichtigt.
- Sanft öffnende FAQ und Weitergabe des gewählten Angebots an das Kontaktformular.

KONTAKT
Das Kontaktformular bereitet eine Nachricht lokal vor. Besucher kopieren sie und senden sie selbst über Instagram. Es gibt keinen automatischen E-Mail-Versand und keine Nachrichten-Datenbank.

PRÜFUNG
Lokale Seiten-, Bild-, Skript-, Stylesheet- und Ankerverweise sowie JavaScript-Syntax wurden geprüft. Die Live-Darstellung und Bedienung in einem Browser konnten in dieser Arbeitsumgebung nicht überprüft werden.
Die bereitgestellten Seiten Impressum und Datenschutzhinweise enthalten weiterhin Platzhalter für Anbieter- und Hostingangaben.

DATEIEN
refinements.css enthält die neuen responsiven Designregeln.
script.js enthält Navigation, Hero, Kontakt, Bildansicht, FAQ und Einblendungen.
design/hero-mobile-prompts.txt dokumentiert die Motive und verwendeten Prompts.

HERO-ANPASSUNG (Angebote + Über BuntBewegt)
- Die Panorama-Illustrationen sind als optimierte WebP-Dateien direkt in die beiden Hero-Bereiche eingebunden.
- Desktop: vollbreites Hero-Bild mit dezentem Textkontrast. Mobil: gut sichtbares Bild unter der Einleitung statt einer stark beschnittenen Hintergrundgrafik.
- Die redundanten Brotkrumen „Start / Angebote“ und „Start / Über BuntBewegt“ sind entfernt.
- Die Hauptnavigation mit „Start“, „Angebote“, „Über BuntBewegt“ und „Kontakt“ bleibt erhalten.
- Die ursprünglichen Panorama-PNGs sind aus dem Mobilpaket entfernt; die Website verwendet kleinere WebP-Dateien.

HERO UPDATE: Bild 1 nutzt eine schärfere, farblich optimierte WebP-Version des Originalfotos in Desktop- und Mobilgrößen. Die Fotoüberlagerung wurde am rechten Bildbereich aufgehellt.

MOBILE-FIX (Oktober 2026)
- Das Handy-Menü sperrt nicht länger das Scrollen des HTML-Dokuments;
  berührt man die halbtransparente Fläche, schließt es wieder.
- Der Menü-Hintergrund verzichtet auf rechenintensives Live-Blur.
- Auf iPhones können Menüliste und Unterseiten wieder sicher geöffnet werden;
  ältere Safari-Versionen erhalten einen MediaQueryList-Fallback.
- Beim automatischen Bildwechsel wird kein aufwendiger Neuaufbau der
  Hero-Titel mehr erzwungen. Nicht aktive Bilder werden verzögert geladen.
- Skript- und CSS-Versionskennungen wurden auf allen Seiten aktualisiert.

GRÖSSE / PERFORMANCE
- Große PNG-Webbilder wurden durch visuell hochwertige WebP-Dateien ersetzt.
- Die beiden gleichen Logo-PNGs teilen sich dieselbe Datei.
- Unbenutzte Bildoriginale werden nicht mit ausgeliefert.
