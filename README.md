# Haushaltsbuch (PWA)

Monatsraster wie in der Excel-Vorlage, Eintragen am Handy, Ansicht am PC, Sync über ein privates GitHub-Repo, Export als .xlsx.

## Einrichtung
1. **App-Repo** (z. B. `haushaltsbuch`) auf GitHub anlegen und alle Dateien dieses Ordners hochladen. Settings → Pages → *Deploy from a branch* → `main` / `(root)`. Die App liegt dann unter `https://DEINNAME.github.io/haushaltsbuch/`.
2. **Daten-Repo** anlegen, z. B. `haushaltsbuch-daten`, **privat**, mit README (damit es einen Branch gibt). Hier werden deine Zahlen gespeichert – nicht im öffentlichen App-Repo.
3. **Token**: GitHub → Settings → Developer settings → Fine-grained tokens → nur das Daten-Repo auswählen, Berechtigung *Contents: Read and write*.
4. In der App ⚙ öffnen: `DEINNAME/haushaltsbuch-daten` und Token eintragen (auf jedem Gerät einmal). Danach synchronisiert die App automatisch.
5. Handy: Seite öffnen → „Zum Home-Bildschirm“ / „App installieren“.

Der Token liegt nur im Browser des jeweiligen Geräts. Der Excel-Export (⬇) erzeugt das Blatt des aktuellen Monats mit Formeln.
