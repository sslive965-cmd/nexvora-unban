NEXVORA UNBAN — APP-READY WEBSITE PACKAGE

IMPORTANT
- Existing HTML pages and website features are preserved.
- Only PWA manifest/icon metadata and service-worker registration were added.
- This package does not yet contain a compiled APK. APK generation is the next step after deploying these files.

FILES ADDED
- manifest.webmanifest
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png
- icons/icon-maskable-192.png
- icons/icon-maskable-512.png

DEPLOY
1. Extract this ZIP.
2. Open your existing GitHub repository for NEXVORA UNBAN.
3. Upload/replace the contents inside the `nexvora-unban-main` folder at the same repository root where the current index.html lives.
4. Commit the changes and wait for Vercel deployment.
5. Open https://nexvora-unban.vercel.app/ in Chrome on Android.
6. Use Chrome menu (three dots) > Install app / Add to Home screen.

APK
After deployment, open https://www.pwabuilder.com/ in Chrome, enter https://nexvora-unban.vercel.app/, and follow its Android package workflow. A Trusted Web Activity APK may require Android package/signing details and a Digital Asset Links file on the website. Do not change existing backend/auth/payment settings for this conversion.
