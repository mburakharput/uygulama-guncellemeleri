# Windows uygulama güncellemeleri

MediAsist, Playlist Studio, Kanal-i-zasyon ve Mizansen kurulumları için resmi dağıtım deposu. Kaynak kodlar özel depolarda tutulur.

## Windows x64 kurulumları

| Uygulama | Sürüm | Kurulum |
|---|---|---|
| MediAsist | 10.25.2 | [Setup indir](https://github.com/mburakharput/uygulama-guncellemeleri/releases/download/MediAsist-v2026.10.25.2/MediAsist-2026.10.25.2-Setup-x64.exe) |
| Playlist Studio | 4.3.4 | [Setup indir](https://github.com/mburakharput/uygulama-guncellemeleri/releases/download/PlaylistStudio-v4.3.4/PlaylistStudio-4.3.4-Setup-x64.exe) |
| Kanal-i-zasyon | 0.5.8 | [Setup indir](https://github.com/mburakharput/uygulama-guncellemeleri/releases/download/Kanal-i-zasyon-v0.5.8/Kanal-i-zasyon-0.5.8-Setup-x64.exe) |
| Mizansen | 2026.10.24.4 | [Setup indir](https://github.com/mburakharput/uygulama-guncellemeleri/releases/download/Mizansen-v2026.10.24.4/Mizansen-2026.10.24.4-Setup-x64.exe) |

Bu sürümler varsayılan olarak **C:\Program Files\UygulamaAdı** altına kurulur. Kurulum ve güncellemelerde Windows yönetici onayı gerekir; uygulamalar normal kullanıcı haklarıyla çalışır. Eski AppData kurulumundan geçiş için yeni Setup bir kez elle yüklenmelidir. Kişisel veriler kullanıcı klasöründe tutulur; yeni kullanıcıda gerekli boş veritabanları ilk açılışta oluşturulur. Kurulumdan önce çalışan uygulamayı normal biçimde kapatın. Sonraki sürümlerde uygulama yeni sürüm bilgisi verir; **Güncellemeler → Güncelleştir** paketi doğrulayıp kurulumu uygular ve uygulamayı yeniden açar. **Güncellemeleri kontrol et** yalnız bilgi gösterir.

Windows yayıncı sertifikası kullanılmadığından ilk kurulumda **bilinmeyen yayıncı** uyarısı görülebilir. Uygulama içindeki güncellemeler geliştiricinin sabit açık anahtarıyla doğrulanan Ed25519 imzalı sürüm kayıtları üzerinden yapılır.

GitHub’ın otomatik **Source code** arşivleri yalnız bu dağıtım deposuna aittir; uygulamayı kurmak için yukarıdaki **Setup indir** bağlantılarını kullanın.

## Gizlilik

Kurulumlar kişisel fotoğraf, kanal listesi, katalog/veritabanı, yüz profili, Spotify oturumu, Google OAuth dosyası veya erişim anahtarı içermez. Programı kuran kişi kendi arşivini ve bağlantılarını ekler.

## Sürüm düzeni

Her uygulama kendi etiketlerini izler: MediAsist-vSÜRÜM, PlaylistStudio-vSÜRÜM, Kanal-i-zasyon-vSÜRÜM, Mizansen-vSÜRÜM. Taslaklar ve ön sürümler güncelleyicide görünmez.

Yayımlamadan önce Windows açılışı, ilk kurulum, aynı paketle yerinde yeniden kurulumda sentetik verilerin korunması, kaldırma, SHA-256 ve geliştirici imzası doğrulanır. Aynı paketle yeniden kurulum testi farklı eski sürümlerden gerçek kullanıcı verisi geçişinin yerine geçmez. Özel imzalama anahtarı kaynak kodda, Actions’ta veya kurulum paketlerinde tutulmaz.
