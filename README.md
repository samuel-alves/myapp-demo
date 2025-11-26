# MyApp Demo – Android App Links via GitHub Pages

This repo demonstrates how to host Android App Links using GitHub Pages.

## URLs

### Landing page:
https://YOUR_USERNAME.github.io/myapp-demo/

### App Link Screens:
- Screen 1: https://YOUR_USERNAME.github.io/myapp-demo/open?screen=screen1
- Screen 2: https://YOUR_USERNAME.github.io/myapp-demo/open?screen=screen2

## Asset Links file:
https://YOUR_USERNAME.github.io/myapp-demo/.well-known/assetlinks.json

Android verifies this file automatically via:
android:autoVerify="true"

## Notes
- Replace the SHA-256 fingerprint in `.well-known/assetlinks.json`
- Edit the app package name
