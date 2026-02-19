# TanhuStok POS - Android Uygulaması

## Kurulum Adımları

### Gereksinimler
- Android Studio (https://developer.android.com/studio)
- JDK 8 veya üzeri

### Build Etme
1. Android Studio'yu aç
2. "Open an Existing Project" seç
3. Bu klasörü seç (TanhuStokApp)
4. Gradle sync tamamlanana kadar bekle
5. Build > Build Bundle(s) / APK(s) > Build APK(s)
6. APK: app/build/outputs/apk/debug/app-debug.apk

### APK'yı İmzalama (Opsiyonel)
Build > Generate Signed Bundle / APK
Yeni keystore oluştur ve imzala.

### Uygulama Bilgileri
- Package: com.tanhustokpos
- Min Android: 5.0 (API 21)
- Target Android: 13 (API 33)
- İzinler: İnternet, Kamera, Dosya okuma/yazma
