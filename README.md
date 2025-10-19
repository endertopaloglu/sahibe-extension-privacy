# "Sahibe" (Sahibinden.com Ad Enhancer) Eklentisi Gizlilik Politikası

Bu eklenti, kullanıcıların gizliliğine saygı duyar ve kâr amacı gütmez.

**Veri Toplama ve Kullanımı**

Bu eklenti, kullanıcıdan (ad, e-posta, kimlik bilgisi gibi) HİÇBİR KİŞİSEL VERİ toplamaz veya herhangi bir sunucuya göndermez.

Eklentinin düzgün çalışabilmesi için YALNIZCA aşağıdaki veriler kullanıcının kendi bilgisayarında (`chrome.storage.local` ve `chrome.storage.sync`) saklanır:

1.  **İlan Durum Bilgisi:** Kullanıcının sahibinden.com'da incelediği ilanların ID'leri ve hasar durumları (`damagedAds`, `cleanAds`) saklanır. Bu, sayfa yenilendiğinde eklentinin işaretlemeleri tekrar gösterebilmesi için gereklidir.
2.  **Hasar Grafiği Önbelleği:** Kullanıcı bir ilanın üzerine geldiğinde, o ilanın hasar grafiği HTML'i (`damageHTML`) alınır ve daha hızlı yüklenmesi için önbelleğe alınır.
3.  **Ayar Bilgisi:** Gizlenen ilanların görünürlük ayarı (`storage.sync`) saklanır.

Bu verilerin hiçbiri geliştiriciyle veya üçüncü taraflarla paylaşılmaz, satılmaz veya analiz edilmez. Tüm veriler yerel olarak kalır.
