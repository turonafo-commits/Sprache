# Sprachen

Offline Android-Sprachlern-App fuer Deutsch/Russisch als UI-Sprachen und Englisch/Spanisch als Lernsprachen.

## Erster funktionsfaehiger Stand

- Native Android-App ohne Backend und ohne Online-Datenabruf
- UI-Umschaltung Deutsch/Russisch
- Lernsprachen Englisch und Spanisch
- Level A0, A1, A2, B1 und B2
- Mehrere lokale Benutzerprofile
- Multiple-Choice-Uebungen
- Lokaler Fortschritt pro Benutzer, Lernsprache und Level
- GitHub-Actions-Workflow fuer eine installierbare Debug-APK

## Build

Lokal mit installiertem Android SDK:

```bash
gradle assembleDebug
```

In GitHub Actions wird nach jedem Push auf `main` die Datei `app/build/outputs/apk/debug/app-debug.apk` als Artifact `sprachen-debug-apk` hochgeladen.

