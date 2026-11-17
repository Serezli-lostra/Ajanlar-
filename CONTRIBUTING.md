# Katkıda Bulunma

## Android geliştirme kuralları

- Projenin mevcut Gradle Wrapper ve JDK gereksinimlerini kullanın; sürümleri gerekçesiz yükseltmeyin.
- Her özellik veya hata düzeltmesi için ayrı dal kullanın: `feature/`, `fix/`, `docs/`, `chore/`.
- Uygun olduğunda unit test ve instrumentation test ekleyin.
- Manifest izinlerini, ağ erişimini ve dışa açık Android bileşenlerini değiştirirken gerekçeyi PR'da açıklayın.
- İmzalama anahtarları, servis hesapları, API anahtarları ve kişisel yapılandırmaları commit etmeyin.

## PR kontrol listesi

- [ ] Değişiklik kapsamı ve kullanıcı etkisi açıklandı.
- [ ] İlgili Gradle test/derleme görevleri çalıştırıldı ve sonuçları eklendi.
- [ ] Manifest/izin değişiklikleri açıklandı.
- [ ] Gizli bilgiler, keystore veya yerel yapılandırma eklenmedi.
- [ ] Geri alma yolu belirtildi.

## Birleştirme

Gerekli kontroller ve kod incelemesi tamamlanmadan `main` dalına birleştirme yapılmamalıdır.
