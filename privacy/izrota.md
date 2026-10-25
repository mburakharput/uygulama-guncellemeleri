# İzrota — Gizlilik Politikası

**Son güncelleme:** 26 Ekim 2026  
**Uygulama:** İzrota — Bağlantı Asistanı (Chrome/Edge eklentisi)  
**Yayıncı:** mburakharput

## Eklentinin amacı
İzrota, desteklenen PSA film ve dizi sayfalarında görünen film, sezon, bölüm ve sürüm adlarını okuyarak alternatif bağlantı adaylarını ReleaseBB ve Knaben arama kaynaklarında sorgular ve sonuçları sayfa üzerinde gösterir. Desteklenen ara bağlantı sayfalarında gezinmeye de yardımcı olur. Eşleşmeler dosya adına dayanır; dosya içeriği veya bağlantının güvenliği doğrulanmış değildir.

## İşlenen bilgiler ve dış servisler
- Eklenti desteklenen sayfalardaki film/dizi adı, yıl, sezon/bölüm ve sürüm metinlerini arama sorgusu üretmek için işler.
- Arama sorguları **search.rlsbb.to / rlsbb.to / post.rlsbb.to (ReleaseBB)** ve **api.knaben.org (Knaben)** hizmetlerine gönderilir. Bu servisler isteği ve bağlantı kaynaklı teknik bilgileri (örneğin IP adresi) kendi politikalarına göre işleyebilir; yayıncı bu servislerin veri işleme uygulamalarını kontrol etmez.
- ReleaseBB aramalarında ağ isteği `credentials: omit` kullanır; Knaben istekleri de çerez göndermeyecek biçimde yapılır.
- Desteklenen yönlendirme sayfalarında ziyaret edilen URL'ler ve bulunan hedef adresler, bağlantı yardımcısının çalışması için işlenir. Eklenti genel tarayıcı geçmişini toplamak için Chrome History API'sini kullanmaz.
- Kullanıcı hesabı oluşturulmasını gerektirmez; eklentide geliştiriciye veri gönderen ayrı bir analitik, reklam veya ödeme sistemi bulunmaz.

## Cihazda saklanan veriler
- Etkin/duraklatılmış durum ve otomatik tarama seçimi yerel tarayıcı depolamasında tutulur.
- Önceden bulunan yönlendirme eşleşmeleri cihazda en çok **7 gün** saklanır; önbellek en fazla **200 kayıt** içerir. Bu kayıtlar kaynak ve hedef URL içerebilir.
- Geçici yönlendirme zincirleri oturum depolamasında tutulur ve ilgili sekme kapatıldığında veya zincir tamamlandığında temizlenebilir.
- Arama sonuçları kısa süreli olarak eklentinin belleğinde önbelleğe alınabilir.
- Eklenti menüsündeki **Hatırlanan bağlantıları temizle** seçeneği yerel yönlendirme önbelleğini ve geçici oturum kayıtlarını temizler. Tarayıcıdan eklentiyi kaldırmak eklentinin yerel depolamasını siler.

## İzinler
- **storage:** Kullanıcı tercihleri, bağlantı önbelleği ve geçici yönlendirme bilgileri.
- **activeTab:** Kullanıcının seçili sekmedeki eklenti durumunu kontrol etmek ve talep ettiği işlemi başlatmak.
- **scripting:** Kullanıcının ayrıca izin verdiği sitelere ilgili içerik betiklerini eklemek.
- **Site erişimi:** PSA sayfalarında sürüm bilgilerini okumak, desteklenen yönlendirmeleri işlemek ve ReleaseBB/Knaben kaynaklarında arama yapmak. Diğer HTTPS sitelerine erişim için kullanıcıdan ayrıca tarayıcı izni istenir.

## Paylaşım, satış ve kullanım
İzrota, kullanıcı verilerini satmaz ve kredi değerlendirmesi veya ilgisiz reklam profillemesi amacıyla kullanmaz. Yukarıda belirtilen arama bilgileri, kullanıcıya alternatif bağlantıları sunmak amacıyla ilgili üçüncü taraf arama servislerine iletilir. Kullanıcı, hangi bağlantıların açılacağına kendisi karar verir; harici bağlantıların kendi gizlilik koşulları geçerlidir.

## Haklar ve iletişim
Yerel bağlantı önbelleği eklenti arayüzünden silinebilir. Eklentiyi kaldırarak kullanım sonlandırılabilir. Politika veya eklentiye ilişkin sorular için GitHub profilindeki iletişim kanalları kullanılabilir: https://github.com/mburakharput

Bu politika eklentinin mevcut işleyişini açıklar. Veri işleme davranışı değişirse metin güncellenir.
