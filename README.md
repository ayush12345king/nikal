# Nikal — Android app

The whole game lives in `www/index.html`. GitHub builds the Android app automatically
every time you upload a change (see `.github/workflows/build-android.yml`).

Ads use Google's official TEST ad IDs. Swap in your own AdMob IDs before publishing:
- App ID: in `.github/workflows/build-android.yml` (the `ca-app-pub-...~...` value)
- Ad unit IDs: in `www/index.html`, search for `AD_IDS`
