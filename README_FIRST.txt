CUSTOM AI - ANDROID STARTER

This is a starter Android project. Version 1 supports:
- Tap-to-speak speech recognition (Hindi-first locale hint)
- Spoken response using Android Text-to-Speech
- Opens the phone dialer for a spoken phone number (you confirm the call)
- Sends a play-music intent to compatible music apps

AI question answering, contact-name lookup, always-listening wake word, and advanced phone control are NOT included yet.

BUILD WITHOUT A PC:
1. Create/sign in to a GitHub account in your phone browser.
2. Create a NEW repository named CustomAI (Public or Private).
3. Upload the contents of this ZIP to the repository root (not the ZIP file itself).
4. Open the repository's Actions tab.
5. If prompted, enable GitHub Actions.
6. Open "Build Custom AI APK" and tap "Run workflow", or wait for the first push build.
7. When the run succeeds, open it and download the "CustomAI-debug-apk" artifact.
8. Extract the downloaded artifact ZIP and install app-debug.apk.
9. Android may ask you to allow installs from that browser/file manager. Only install the APK built from your own repository.

NOTES:
- This starter has no API key and makes no AI API calls.
- Speech recognition may use Google's/device speech service and may need internet.
- Calls are opened in the dialer; the app does not place calls automatically.
- Music behavior depends on installed apps.
- Do not add private API keys directly to source code or a public repository.
