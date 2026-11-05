# DockTab

macOS 27 ve üzeri / Apple silicon için Dock pencere önizlemeleri.

## İndir

[Son sürümün kurulum paketini indirin](https://github.com/erhanulas/DockTab-Downloads/releases/latest). `DockTab-<sürüm>.pkg`, uygulamayı `/Applications/DockTab.app` konumuna kurar.

## Uygulama içinden güncelleme

0.16.2 ve sonrasında **Ayarlar → Güncellemeler → Güncellemeleri otomatik denetle** seçeneği varsayılan açıktır. DockTab çalışırken yaklaşık 24 saatte bir yeni sürüm kontrol edilir. Seçeneği kapatabilirsiniz; daha önce kapatılmış bir Sparkle tercihi varsa korunur. Yeni sürüm bulunduğunda haber verilir; indirme ve kurulum sizin onayınızla ilerler.

0.11.0 ve sonrasında menü çubuğundaki DockTab → **Güncellemeleri Denetle…** komutunu seçin. Yeni sürüm varsa güncelleme penceresindeki kurulum düğmesiyle indirin ve kurun. Uygulama yeniden başlatılır. macOS gerekirse yönetici onayı ister.

0.10.0 ve daha eski sürümlerde güncelleyici bulunmaz; ilk geçiş için yeni PKG’yi bir kez kurun. Sonraki sürümler uygulama içinden alınabilir.

Günlük kontrolün zamanlamasını Sparkle yönetir; otomatik indirme/kurulum ve uygulama telemetrisi kapalıdır. Ayarlardaki **Şimdi Denetle…** düğmesi ve menüdeki elle denetleme komutu, otomatik kontrol kapalıyken de kullanılabilir. Paketler HTTPS üzerinden indirilir ve Sparkle Ed25519 imzasıyla doğrulanır. GitHub hesabı gerekmez.

## İzinler ve dağıtım

Dock simgelerini/pencereleri bulmak için Erişilebilirlik, pencere görüntüleri için Ekran Kaydı izni gerekir. İzinler Ayarlar ekranından istenir. Önizleme görüntüleri cihaz dışına gönderilmez.

Bu paketler kalıcı yerel kod imzalama sertifikasıyla üretilir; Apple Developer ID ve notarization içermez. Diğer Mac’lerde macOS güvenlik onayı veya kurulum engeliyle karşılaşılabilir.

Bu repo yalnızca indirme paketleri ve güncelleme beslemesi içindir; uygulamanın kaynak kodu burada yayımlanmaz.
