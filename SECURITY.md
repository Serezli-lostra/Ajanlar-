# Güvenlik Politikası

## Hassas Android dosyaları

Aşağıdakileri depoya eklemeyin:

- Android imzalama dosyaları: `.jks`, `.keystore`
- Firebase/Google hizmet yapılandırmaları: `google-services.json` (içerik gizli veya projeye özel ise)
- API anahtarları, erişim belirteçleri, servis hesabı anahtarları ve parolalar
- Yerel makine yolları ve özel yapılandırmalar: `local.properties`

## Güvenlik bildirimi

Güvenlik açıklarını herkese açık issue içinde yayımlamayın. GitHub deposunun Security sekmesindeki özel bildirim özelliğini kullanın (etkinse); aksi durumda depo sahibine özel GitHub kanalı üzerinden ulaşın.

## Yanlışlıkla sır yayımlanırsa

Sırrı hemen iptal edip yenileyin. Dosyayı son commit'ten silmek tek başına yeterli değildir; Git geçmişi, release varlıkları ve CI logları da incelenmelidir.

## Android inceleme başlıkları

- Gereksiz izinler ve dışa açık bileşenler
- Güvenli olmayan ağ trafiği veya cleartext ayarları
- WebView JavaScript/bridge kullanımı
- Yedekleme ve yerel veri saklama
- İmzalama ve yayınlama sırlarının korunması
