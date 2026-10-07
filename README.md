# Apparaattemperatuur – Android app

WebView-app die `app/src/main/assets/index.html` toont.

## APK bouwen
**Android Studio:** Open deze map -> wacht op Gradle sync -> Build > Build APK(s).
APK: `app/build/outputs/apk/debug/app-debug.apk`

**Zonder Android Studio:** zet de map in een GitHub-repo; de workflow in
`.github/workflows/build.yml` bouwt de APK (tab Actions > Artifacts).

Wil je de app aanpassen? Bewerk alleen `assets/index.html`.
