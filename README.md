# SimpleHelloApp

تطبيق Android بسيط باللغة العربية.

## البناء السحابي

المشروع يحتوي على GitHub Actions في `.github/workflows/build-apk.yml`.

بعد رفع المشروع إلى GitHub:

1. افتح تبويب **Actions**.
2. اختر **Build Android APK**.
3. اضغط **Run workflow**.
4. بعد نجاح البناء افتح الـworkflow.
5. من قسم **Artifacts** نزّل `SimpleHelloApp-debug`.
6. فك الضغط وثبّت `app-debug.apk` على هاتف Android.

لا يحتاج بناء الـAPK إلى Android Studio؛ GitHub Actions يجهز Java وGradle وAndroid SDK ويبني التطبيق سحابيًا.
