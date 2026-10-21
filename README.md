# Kommentarliste – kostenlose iPhone-Web-App

Eine statische Web-App ohne Anmeldung, Backend, Tracking oder externe Bibliotheken.

## Einrichtung über GitHub Pages

1. Erstelle ein öffentliches GitHub-Repository, z. B. `kommentarliste`.
2. Lade **alle Dateien dieses Ordners** direkt in die oberste Ebene des Repositorys hoch (`index.html`, `manifest.webmanifest`, `sw.js`, beide PNG-Symbole und `.nojekyll`).
3. Öffne im Repository `Settings` → `Pages`.
4. Wähle `Deploy from a branch` → `main` → `/(root)` → `Save`.
5. Öffne die von GitHub Pages angezeigte HTTPS-Adresse im **Safari** deines iPhones.
6. Tippe auf `Teilen` → `Zum Home-Bildschirm` / `Zu Home-Bildschirm hinzufügen`, wähle gegebenenfalls `Als Web-App öffnen` und bestätige mit `Hinzufügen`.
7. Starte die App über das neue Home-Bildschirm-Symbol und importiere deine `.txt`-Datei über `+ TXT laden`.

Danach erscheinen deine Kommentare bei jedem Öffnen automatisch wieder. Bei iOS kann der Speicher der Home-Bildschirm-Web-App vom normalen Safari-Speicher getrennt sein. Importiere die TXT am besten **in der installierten App**.

## Bedienung

- **Gelbes Quadrat mit Haken (rechts):** Kopiert nur den Kommentartext (ohne `001 |`) in die Zwischenablage. **Nur bei erfolgreichem Kopieren** verschwindet die Zeile.
- **Kommentartext antippen:** Vollständige Vorschau aufklappen/zuklappen.
- **Menü (drei Punkte):** Neue Liste importieren, die verbleibenden Kommentare als TXT sichern, den letzten Haken zurücknehmen, die Liste zurücksetzen oder entfernen.
- **Lokale Speicherung:** Alle Einträge und der Fortschritt werden im Browser/der Web-App auf dem jeweiligen Gerät gespeichert. Die TXT-Datei wird **nicht an einen Server hochgeladen**.

## Unterstütztes Format

```txt
001 | Erster Kommentar 🤩
002 | Zweiter Kommentar
003 | @beispiel.name 🔥
```

Auch unnummerierte Zeilen funktionieren; dann vergibt die App eigene Nummern. Leerzeilen werden ignoriert. Dateien bis 3 MB werden verarbeitet.

## Hinweise

- GitHub Pages veröffentlicht die App selbst im Internet; **die importierten Kommentare bleiben lokal** und werden nicht in das GitHub-Repository übertragen.
- Kein automatisches Posten in Instagram oder andere Plattformen.
- Wenn Website-Daten gelöscht werden oder der iPhone-Speicher von iOS bereinigt wird, kann der Fortschritt verloren gehen. Über das Menü kannst du deshalb die offenen Kommentare als TXT exportieren.
- Für die Kopierfunktion sollte die Seite über **HTTPS** auf GitHub Pages geöffnet werden.
