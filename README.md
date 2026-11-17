# Ajanlar-

> Android/Gradle deposu. Uygulamanın kesin amacı, modülleri ve desteklenen Android sürümleri proje kaynakları doğrulandıktan sonra bu belgeye eklenmelidir.

## Depo güvenliği

- Android imzalama anahtarlarını (`.jks`, `.keystore`) ve `google-services.json` dosyasını Git'e eklemeyin.
- `local.properties`, IDE ayarları ve derleme çıktıları yerel kalmalıdır.
- Yayın imzalama bilgileri güvenli CI sırları veya yerel güvenli depolama üzerinden sağlanmalıdır.

## Geliştirme akışı

1. Android Studio ve projenin gerektirdiği JDK/Gradle sürümlerini mevcut Gradle yapılandırmalarından doğrulayın.
2. Her iş için ayrı bir dal açın.
3. Uygun modül testlerini ve Gradle derleme görevlerini çalıştırın.
4. Değişiklikleri PR ile incelemeye sunun; `main` dalına doğrudan push yapmayın.

## Proje bilgileri tamamlanacak

- Uygulama amacı ve ekran/özellik listesi
- Modül yapısı
- Android Gradle Plugin, Gradle ve JDK sürümleri
- Minimum/target SDK
- Test, paketleme ve yayınlama adımları
