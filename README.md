# Attachment Log Book — Native Android App (Capacitor + GitHub Actions)

Build a 100% offline Android `.apk` right from your phone using GitHub Actions (no PC or Android Studio required).

## Quick Phone-Only Build Steps
1. Create a new GitHub repository (Public or Private).
2. Upload all files from this folder (preserving `www/`, `assets/`, and `.github/workflows/build-android.yml`).
3. Open the **Actions** tab in GitHub on your phone.
4. Tap **Build Android APK** → **Run workflow** (or wait for the automatic run triggered by your upload).
5. When the green checkmark finishes (~3–4 minutes), scroll to **Artifacts** and download **`attachment-logbook-android-apk`**.
6. Extract the downloaded ZIP and tap **`app-debug.apk`** to install on Android.
