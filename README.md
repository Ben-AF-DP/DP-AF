
# Öffentliche PDF-Website (statisch)

Diese Mini-Seite dient dazu, **eine oder mehrere PDF-Dateien** öffentlich zu veröffentlichen – ohne Backend.

## Nutzung
1. Öffne `index.html` lokal im Browser oder hoste den Ordner z. B. via GitHub Pages, Netlify, Azure Static Web Apps oder jedem beliebigen Webserver.
2. Lege deine PDF(s) in den Ordner `files/` und passe bei Bedarf die Links in `index.html` an.
3. Die eingebettete Ansicht nutzt `<object type="application/pdf">`. Browser ohne PDF-Viewer zeigen automatisch einen **Download-Link**.

## Häufige Anpassungen
- **Dateiname ändern**: Ersetze `files/beispiel.pdf` durch `files/dein_dokument.pdf`.
- **Mehrere PDFs**: Weitere `<li><a href="files/…">…</a></li>`-Einträge unter „Mehrere PDFs“ ergänzen.
- **Branding**: Farben in `styles.css` anpassen, Titel/OG-Tags in `index.html` ändern.

## Hosting-Hinweise
- **GitHub Pages**: Repository erstellen → Dateien hochladen → Settings → Pages → Branch `main` → Save.
- **Netlify**: Ordner-Inhalt per Drag&Drop deployen → sofort öffentlich.
- **Azure Static Web Apps**: App anlegen → Repo verbinden → kein Build notwendig.

Viel Erfolg!
