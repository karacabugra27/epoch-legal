---
title: Gizlilik politikası ve KVKK aydınlatma metni
permalink: /privacy
---

# Gizlilik politikası ve KVKK aydınlatma metni

Son güncelleme: 14 Kasım 2026

Bu metin, Epoch'u ("uygulama") kullandığında kişisel verilerinin nasıl işlendiğini 6698 sayılı Kişisel
Verilerin Korunması Kanunu ("KVKK") kapsamında açıklar.

## Veri sorumlusu

Veri sorumlusu, uygulamayı geliştiren ve işleten Buğrahan Karaca'dır. Bu metinle ilgili her soru ve
başvuru için: {{ site.contact_email }}

## Hangi verileri işliyoruz

- **Hesap bilgileri:** e-posta adresin ve şifrenin geri çevrilemez özeti (argon2). Şifrenin kendisini
  saklamayız.
- **Oturum bilgileri:** açık oturumların, her oturumun tarayıcı/cihaz bilgisi (user agent), oluşturulma
  ve son kullanım zamanı.
- **Senin girdiğin içerik:** alanlar, zaman kayıtları, planlar, hedefler, gün kapanış notları, fikirler,
  projeler, görevler, müşteriler ve iletişim kişileri, fırsatlar, teklifler, faturalar ve ödemeler.
- **Tercihler:** dil, saat dilimi, para birimi, günlük hedefler, pomodoro süreleri.
- **Teknik veriler:** IP adresin, kötüye kullanımı önlemek için (deneme sınırları) yalnızca sunucu
  belleğinde kısa süre tutulur ve veritabanına yazılmaz. Sunucu kayıtları (log) güvenlik ve hata
  ayıklama için kısa süre saklanabilir.
- **Kayıt anı:** kullanım koşullarını ve bu metni kabul ettiğin zaman.

Müşterilerine ait bilgileri (ad, e-posta, telefon vb.) uygulamaya sen girersin. Bu kişiler açısından
veri sorumlusu sensin; bu bilgileri girmek için gerekli hukuki dayanağa sahip olmak senin
sorumluluğundadır. Biz bu verileri yalnızca sana hizmet vermek için saklarız.

## Neden ve hangi hukuki sebeple işliyoruz

- Hesabını açmak, girişini sağlamak ve uygulamayı sunmak: sözleşmenin kurulması ve ifası
  (KVKK m. 5/2-c).
- Şifre sıfırlama e-postası göndermek: sözleşmenin ifası (m. 5/2-c).
- Hesabını ve hizmeti korumak (deneme sınırları, bot doğrulaması, güvenlik kayıtları): meşru menfaat
  (m. 5/2-f).
- Yasal yükümlülükleri yerine getirmek ve resmi taleplere cevap vermek: m. 5/2-ç.

Verilerini reklam, profil çıkarma veya satış amacıyla kullanmayız. Analitik ya da izleme aracı
kullanmayız.

## Kimlere aktarıyoruz

Hizmeti sunmak için şu hizmet sağlayıcılarla çalışırız. Her biri verini yalnızca bizim adımıza ve
gerektiği kadar işler:

| Sağlayıcı | Ne için | Hangi veri | Konum |
|---|---|---|---|
| Hostinger | Sunucu ve veritabanı | Tüm hesap verilerin | {{ site.server_location }} |
| Resend | Şifre sıfırlama e-postası | E-posta adresin, e-postanın içeriği | ABD |
| Cloudflare (Turnstile) | Kayıt ve şifre sıfırlamada bot doğrulaması | IP adresin, tarayıcı sinyalleri | ABD ve küresel ağ |
| Yedekleme sağlayıcısı (Backblaze B2 veya Cloudflare R2) | Şifreli günlük veritabanı yedekleri | Tüm hesap verilerin | Sağlayıcının seçilen bölgesi |

Yurt dışındaki sağlayıcılara aktarım KVKK m. 9'a uygun olarak, Kurul'un ilan ettiği standart
sözleşmeler gibi uygun güvencelerle yapılır. Bunların dışında verini kimseyle paylaşmayız; yalnızca
kanunen zorunlu olduğunda yetkili kurumlara aktarabiliriz.

## Ne kadar saklıyoruz

- Hesabın açık olduğu sürece verilerini saklarız.
- Hesabını sildiğinde tüm verilerin veritabanından hemen silinir. Yedeklerdeki kopyalar en geç 30 gün
  içinde, yedekler döndükçe silinir.
- Şifre sıfırlama bağlantıları 3 saat sonra geçersiz olur; kullanıldığında ya da şifren değiştiğinde
  silinir.
- Kapattığın oturumlar hemen silinir. Süresi dolan oturumlar bir sonraki girişinde temizlenir.

## Çerezler ve tarayıcı depolama

Yalnızca girişini sürdürmek için zorunlu bir oturum çerezi kullanırız (HttpOnly, üçüncü taraflarla
paylaşılmaz). Tema ve dil tercihin tarayıcının yerel depolamasında tutulur. Kayıt ve şifre sıfırlama
sayfalarındaki Cloudflare Turnstile, bot doğrulaması için kendi teknik verilerini işleyebilir. Reklam veya
izleme çerezi kullanmayız.

## Güvenlik

Bağlantılar HTTPS ile şifrelenir. Şifreler argon2 ile özetlenir, oturum anahtarları veritabanında
özetlenmiş olarak tutulur. Her hesabın verisi diğer hesaplardan ayrıdır; başka bir kullanıcı senin
verini göremez.

## Hakların

KVKK m. 11 uyarınca verilerinin işlenip işlenmediğini öğrenme, bilgi isteme, işlenme amacını ve
aktarıldığı kişileri öğrenme, eksik veya yanlış verinin düzeltilmesini, silinmesini ve bunların
aktarıldığı kişilere bildirilmesini isteme, otomatik analizle aleyhine bir sonuç çıkmasına itiraz etme
ve zarara uğrarsan tazminat isteme hakkın vardır.

Bunların çoğunu doğrudan uygulamadan yapabilirsin: **Ayarlar → Hesap ve güvenlik** bölümünden tüm
verilerini JSON olarak indirebilir, oturumlarını kapatabilir ve hesabını kalıcı olarak silebilirsin.
Diğer talepler için {{ site.contact_email }} adresine yaz; en geç 30 gün içinde cevap veririz.
Cevabımızı yeterli bulmazsan Kişisel Verileri Koruma Kurulu'na şikâyette bulunabilirsin.

## Yaş sınırı

Uygulama 18 yaşından küçükler için tasarlanmamıştır.

## Değişiklikler

Bu metni değiştirirsek üstteki tarihi güncelleriz. Önemli değişiklikleri uygulama içinden duyururuz.
