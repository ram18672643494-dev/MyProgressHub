MY PROGRESS HUB — ANDROID PROJECT

Is ZIP mein Android Studio project source hai. Yeh abhi compiled APK nahi hai.

APK banane ka simple tareeka:
1. ZIP ko GitHub par ek naye repository mein upload karo.
2. Repository ka naam MyProgressHub rakh sakte ho.
3. Actions tab kholo.
4. "Build My Progress Hub APK" workflow select karo.
5. "Run workflow" dabao.
6. Build complete hone par Artifacts mein MyProgressHub-debug-apk download karo.
7. ZIP artifact extract karke app-debug.apk phone mein bhejo aur install karo.

Agar Android Studio wala computer available hai:
- Project open karo.
- Gradle sync hone do.
- Build > Build Bundle(s) / APK(s) > Build APK(s).
- APK app/build/outputs/apk/debug/app-debug.apk mein milega.

Note:
- App ka data isi phone ke app storage mein save hota hai.
- Phone reset/uninstall se pehle Overview mein Export backup use karna.
- Yeh debug APK personal use/testing ke liye hai; Play Store release signing included nahi hai.
