# DockTab

macOS 27 ve üzeri / Apple silicon için Dock pencere önizlemeleri.

## İndir

[Son sürümün kurulum paketini indirin](https://github.com/erhanulas/DockTab-Downloads/releases/latest). `DockTab-<sürüm>.pkg`, uygulamayı `/Applications/DockTab.app` konumuna kurar.

## Uygulama içinden güncelleme

0.11.0 ve sonrasında menü çubuğundaki DockTab → **Güncellemeleri Denetle…** komutunu seçin. Yeni sürüm varsa güncelleme penceresindeki kurulum düğmesiyle indirin ve kurun. Uygulama yeniden başlatılır. macOS gerekirse yönetici onayı ister.

0.10.0 ve daha eski sürümlerde güncelleyici bulunmaz; ilk geçiş için yeni PKG’yi bir kez kurun. Sonraki sürümler uygulama içinden alınabilir.

Güncelleme kontrolü kullanıcı isteğiyle yapılır; sürekli arka plan sorgusu ve uygulama telemetrisi yoktur. Paketler HTTPS üzerinden indirilir ve Sparkle Ed25519 imzasıyla doğrulanır. GitHub hesabı gerekmez.

## İzinler ve dağıtım

Dock simgelerini/pencereleri bulmak için Erişilebilirlik, pencere görüntüleri için Ekran Kaydı izni gerekir. İzinler Ayarlar ekranından istenir. Önizleme görüntüleri cihaz dışına gönderilmez.

Bu paketler kalıcı yerel kod imzalama sertifikasıyla üretilir; Apple Developer ID ve notarization içermez. Diğer Mac’lerde macOS güvenlik onayı veya kurulum engeliyle karşılaşılabilir.

Bu repo yalnızca indirme paketleri ve güncelleme beslemesi içindir; uygulamanın kaynak kodu burada yayımlanmaz.
