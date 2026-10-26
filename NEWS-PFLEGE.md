# News und Events pflegen

Die Startseite und „Über uns“ enthalten einen Bereich „News und Events“.
Aktuell zeigen beide dieselben drei allgemeinen Einblicke mit den bereits vorhandenen Fotos.
Neue Termine und Rückblicke können direkt in den HTML-Dateien eingetragen werden.

## Einen Beitrag ergänzen

1. Das passende Foto im Ordner `images/` ablegen, möglichst als WebP mit kurzem Dateinamen ohne Leerzeichen.
2. In `index.html` den Kommentar `NEWS-BEGIN` suchen. Eine vollständige vorhandene `<figure>…</figure>`-Karte kopieren und vor die erste Karte setzen.
3. Bildpfad in `href` und `src`, Bildbeschreibung in `alt` und `aria-label`, Überschrift und Text ersetzen. Bei einem Foto mit anderen Abmessungen auch `width` und `height` anpassen.
4. Das Label `EINBLICK` durch `ANKÜNDIGUNG` oder `RÜCKBLICK` ersetzen. Datum und Ort im Text ergänzen, sobald sie feststehen. Ein Datum kann mit `<time datetime="JJJJ-MM-TT">Datum in lesbarer Form</time>` ausgezeichnet werden; dabei die Platzhalter durch das echte Datum ersetzen.
5. In `ueber-buntbewegt.html` beim Kommentar `NEWS-BEGIN` dieselben Inhalte in einer `<article class="ab-impact-card">…</article>`-Karte ergänzen.
6. Die beiden aktualisierten HTML-Dateien und das neue Foto auf die bestehende Website laden. Anschließend beide Seiten im Browser prüfen.

Die Klassen der kopierten Karte beibehalten, damit Darstellung und Bildvergrößerung funktionieren.
Neue Beiträge oben einfügen. Für eine kompakte Übersicht können ältere Karten entfernt werden.
Beim Entfernen einer Karte nicht die umgebende Galerie oder die Kommentare löschen.

## Originalfotos einsetzen

Das nachgereichte Hochformatfoto ist in `index.html` im Bereich `id="ueber-uns"` als `images/familien-aktion.jpg` eingebunden. Das Bild bleibt vollständig sichtbar. Bei einem späteren Austausch Bildpfad, Alternativtext sowie tatsächliche Breite und Höhe anpassen; bei anderen Proportionen zusätzlich `aspect-ratio` in `.about-family-photo .about-photo-wrap` aktualisieren.

Für das Teamfoto in `ueber-buntbewegt.html` im Bereich `id="team"` das Logo innerhalb von `class="ab-team-visual"` ersetzen. Ein passender Alternativtext beschreibt das echte Teamfoto. Für eine flächige Fotodarstellung kann in `content-updates.css` die Regel `.ab-team-visual img` auf die tatsächlichen Bildproportionen angepasst werden; `height: auto` erhält das vollständige Foto.

Das Teamfoto steht noch aus. Das Markenmotiv kann bis zu seinem Eingang bestehen bleiben.
