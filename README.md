# Windows uygulama güncellemeleri

MediAsist, Playlist Studio, Kanal-i-zasyon ve Mizansen kurulumları için resmi dağıtım deposu. Kaynak kodlar özel depolarda tutulur.

## Windows x64 kurulumları

| Uygulama | Sürüm | Kurulum |
|---|---|---|
| MediAsist | 2026.10.24.8 | [Setup indir](https://github.com/mburakharput/uygulama-guncellemeleri/releases/download/MediAsist-v2026.10.24.8/MediAsist-2026.10.24.8-Setup-x64.exe) |
| Playlist Studio | 4.3.3 | [Setup indir](https://github.com/mburakharput/uygulama-guncellemeleri/releases/download/PlaylistStudio-v4.3.3/PlaylistStudio-4.3.3-Setup-x64.exe) |
| Kanal-i-zasyon | 0.5.7 | [Setup indir](https://github.com/mburakharput/uygulama-guncellemeleri/releases/download/Kanal-i-zasyon-v0.5.7/Kanal-i-zasyon-0.5.7-Setup-x64.exe) |
| Mizansen | 2026.10.24.3 | [Setup indir](https://github.com/mburakharput/uygulama-guncellemeleri/releases/download/Mizansen-v2026.10.24.3/Mizansen-2026.10.24.3-Setup-x64.exe) |

İlk kez bu setupları bir kez indirip kurun. Kurulumdan önce çalışan uygulamayı normal biçimde kapatın. Sonraki sürümlerde uygulama yeni sürüm bilgisi verir; **Güncellemeler → Güncelleştir** paketi doğrulayıp kurulumu uygular ve uygulamayı yeniden açar. **Güncellemeleri kontrol et** yalnız bilgi gösterir.

Windows yayıncı sertifikası kullanılmadığından ilk kurulumda **bilinmeyen yayıncı** uyarısı görülebilir. Uygulama içindeki güncellemeler geliştiricinin sabit açık anahtarıyla doğrulanan Ed25519 imzalı sürüm kayıtları üzerinden yapılır.

GitHub’ın otomatik **Source code** arşivleri yalnız bu dağıtım deposuna aittir; uygulamayı kurmak için yukarıdaki **Setup indir** bağlantılarını kullanın.

## Gizlilik

Kurulumlar kişisel fotoğraf, kanal listesi, katalog/veritabanı, yüz profili, Spotify oturumu, Google OAuth dosyası veya erişim anahtarı içermez. Programı kuran kişi kendi arşivini ve bağlantılarını ekler.

## Sürüm düzeni

Her uygulama kendi etiketlerini izler: MediAsist-vSÜRÜM, PlaylistStudio-vSÜRÜM, Kanal-i-zasyon-vSÜRÜM, Mizansen-vSÜRÜM. Taslaklar ve ön sürümler güncelleyicide görünmez.

Yayımlamadan önce Windows açılışı, ilk kurulum, aynı paketle yerinde yeniden kurulumda sentetik verilerin korunması, kaldırma, SHA-256 ve geliştirici imzası doğrulanır. Aynı paketle yeniden kurulum testi farklı eski sürümlerden gerçek kullanıcı verisi geçişinin yerine geçmez. Özel imzalama anahtarı kaynak kodda, Actions’ta veya kurulum paketlerinde tutulmaz.
