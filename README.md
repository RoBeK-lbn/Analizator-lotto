# Analizator Lotto — APK z aplikacji HTML

Ta paczka buduje gotową aplikację Android APK z wbudowanym plikiem `index.html` w WebView.

## Jak zrobić gotową APK przez GitHub

1. Wejdź na https://github.com i utwórz nowe repozytorium, np. `analizator-lotto-apk`.
2. Rozpakuj tę paczkę ZIP na komputerze.
3. Wgraj całą zawartość folderu do repozytorium na GitHub.
   - Najprościej: w repo kliknij **Add file → Upload files**, przeciągnij wszystkie pliki i foldery, potem **Commit changes**.
4. Wejdź w zakładkę **Actions**.
5. Wybierz workflow **Build Android APK**.
6. Jeżeli nie uruchomi się automatycznie, kliknij **Run workflow**.
7. Po zakończeniu kliknij zakończony build i pobierz artefakt **Analizator-Lotto-APK**.
8. Rozpakuj pobrany artefakt — w środku będzie `app-debug.apk`.
9. Przenieś APK na telefon i zainstaluj. Android może poprosić o zgodę na instalowanie aplikacji z nieznanych źródeł.

## Ważne

- APK jest debugowe, więc nadaje się do instalacji na telefonie, ale nie do publikacji w Google Play.
- Aplikacja ma uprawnienie internetu, żeby pobierać aktualne wyniki.
- Dane zapisane lokalnie w aplikacji korzystają z WebView/localStorage.
