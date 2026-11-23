SARKIN KHALID GALLERY — Android project

Abubuwan da ke ciki:
- Hotuna 6 da aka saka a cikin gallery HTML.
- App mai suna Sarkin Khalid Gallery.
- Yana aiki offline bayan an girka.
- Android app wrapper (WebView).

YADDA AKE GINA APK:
1. A bude wannan folder a Android Studio (Open).
2. A jira Gradle Sync ya gama.
3. A zabi Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Idan ya gama, a danna locate domin samun app-debug.apk.

Lura:
Wannan cikakken source project ne, amma ba APK da aka riga aka compile ba.
Ana bukatar Android Studio/Android SDK domin samar da APK.
Application ID: com.sarkinkhalid.gallery
Min Android: Android 6.0 (API 23)

AUTOMATIC BUILD OPTION (GitHub Actions):
1. Upload/unzip this project into a GitHub repository.
2. Open the repository's Actions tab.
3. Select "Build Sarkin Khalid Gallery APK".
4. Press "Run workflow".
5. When the run finishes, open the run and download the artifact named
   "Sarkin-Khalid-Gallery-APK". It contains app-debug.apk.

The workflow builds the APK automatically on GitHub. This workspace does
not currently have Android SDK/Gradle installed, so it cannot compile the
APK locally.
