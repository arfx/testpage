# Obsidian Site mit GitHub Pages

Dies ist ein minimales Setup, um deine **Obsidian-Markdown-Dateien** mit **GitHub Pages** online zu veröffentlichen.

## 🚀 Deployment

1. Repository auf GitHub erstellen (z. B. `obsidian-site`).
2. Diese Dateien ins Repo hochladen (per Drag & Drop oder `git push`).
3. In **Settings → Pages** einstellen:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Nach einigen Sekunden ist deine Seite online unter:
   ```
   https://deinname.github.io/obsidian-site/
   ```

## 📂 Struktur

```
obsidian-site/
 ├─ _config.yml        # Jekyll-Konfiguration
 ├─ index.md           # Startseite
 └─ notizen/
      └─ beispiel.md   # Beispiel-Notiz
```

## ✍️ Eigene Notizen hinzufügen

- Lege einfach neue Markdown-Dateien im Ordner `notizen/` an.
- Beispiel: `notizen/meine-idee.md`
- GitHub Pages baut die Seite automatisch neu.

## ⚙️ Anpassungen

- In `_config.yml` kannst du Titel, Beschreibung und Theme ändern.
- Standardmäßig wird das Jekyll-Theme **minima** genutzt.

---

Viel Spaß mit deiner Obsidian-Seite ✨
