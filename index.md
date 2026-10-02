# Gizlilik Politikası — Toplu İlan Yenileme (letgo için)

*Son güncelleme: 2 Ekim 2026*

Bu uzantı, letgo.com üzerinde süresi dolmuş ilanları toplu olarak yeniden yayınlamanıza yardımcı olan bir Chrome uzantısıdır. letgo veya OfferUp ile resmi bir bağlantısı yoktur; bağımsız bir geliştirici tarafından geliştirilmiştir.

**Veri sorumlusu / geliştirici:** AD SOYAD — İletişim: DESTEK_E_POSTANIZ

## 1. Yalnızca tarayıcınızda saklanan veriler (sunucuya gönderilmez)
- Yenileme sırasının ilerleme durumu
- "İlanlarım" sayfasından taranan ilanların adı, görseli, fiyatı ve bağlantısı; hariç tuttuğunuz ilanların listesi
- Ayarlarınız (ör. mola tercihi) ve yazıp henüz göndermediğiniz geri bildirim taslağı
- Kullanım sayacı, lisans durumu ve uzantı tarafından üretilen rastgele cihaz kimliği

letgo.com'daki ilan içerikleriniz, mesajlarınız, şifreniz ve gezinme geçmişiniz toplanmaz, kaydedilmez ve hiçbir sunucuya gönderilmez.

## 2. Sunucuya gönderilen veriler
Uzantı, Google Apps Script üzerinde çalışan lisans sunucusuyla iletişim kurar. Gönderilen veriler yalnızca aşağıdaki işlemler sırasında iletilir:

- **Ücretsiz aylık hak ve Pro doğrulaması:** Her ilan yenilemeden önce ve uzantı penceresi açıldığında; rastgele cihaz kimliği, (varsa) lisans anahtarı ve (Chrome'a giriş yaptıysanız) Chrome profil e-postanızın tek yönlü kriptografik özeti (SHA-256; e-posta adresinin kendisi gönderilmez ve özetten geri elde edilemez). Amaç: aylık ücretsiz hakkın ve lisansın doğrulanması, bir anahtarın birden fazla cihazda kullanılmasının engellenmesi.
- **Pro lisans anahtarı etkinleştirme:** Lisans anahtarı ve cihaz kimliği. Sunucu size 6 haneli bir müşteri kimliği atar.
- **Pro sipariş verdiğinizde:** Seçtiğiniz paket, ad soyad, e-posta, telefon ve cihaz kimliği. Amaç: siparişi eşleştirmek, ödemeyi onaylamak, lisans anahtarını size iletmek ve destek sağlamak.
- **Geri bildirim gönderdiğinizde:** Mesajınız, türü, (isteğe bağlı) iletişim bilginiz, plan türü, uzantı sürümü ve cihaz kimliği. Yalnızca "Gönder"e bastığınızda iletilir.

Bu veriler Google Sheets tablosunda saklanır; yalnızca geliştirici erişebilir. Veriler reklam, profilleme veya analiz amacıyla kullanılmaz; satılmaz ve üçüncü taraflarla paylaşılmaz (altyapı sağlayıcısı Google hariç).

## 3. İstenen izinler ve nedenleri
- **storage:** Ayarların, ilerlemenin ve lisans durumunun saklanması
- **scripting / letgo.com erişimi:** İlan tarama ve yenileme adımlarının letgo.com sayfasında yürütülmesi
- **identity.email:** Ücretsiz hakkın yeniden kurulumla sıfırlanmaması için e-postanın tek yönlü özetinin hesaplanması
- **script.google.com erişimi:** Lisans sunucusuyla iletişim

## 4. Saklama süresi ve silme
Sipariş, lisans ve geri bildirim kayıtları, hizmetin sunulması ve olası destek talepleri için gerektiği süre boyunca saklanır. Silinmesini talep etmek için DESTEK_E_POSTANIZ adresine müşteri kimliğinizle yazabilirsiniz. Tarayıcıda saklanan veriler uzantıyı kaldırdığınızda silinir.

## 5. Haklarınız (KVKK ve ilgili mevzuat)
Kişisel verilerinizin işlenip işlenmediğini öğrenme, düzeltme, silme ve itiraz hakkına sahipsiniz. Taleplerinizi DESTEK_E_POSTANIZ adresine iletebilirsiniz.

## 6. Çocuklar
Uzantı 18 yaşın altındaki kişilere yönelik değildir.

## 7. Değişiklikler
Politika güncellenirse güncel sürüm bu sayfada yayınlanır; üstteki tarih değiştirilir.

## 8. İletişim
DESTEK_E_POSTANIZ
