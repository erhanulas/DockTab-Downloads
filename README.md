# DockTab

macOS 27 ve üzeri / Apple silicon için Dock pencere önizlemeleri.

## İndir

[Son sürümün kurulum paketini indirin](https://github.com/erhanulas/DockTab-Downloads/releases/latest). `DockTab-<sürüm>.pkg`, uygulamayı `/Applications/DockTab.app` konumuna kurar.

## Pencereler arasında klavyeyle seçim

0.16.3 ve sonrasında **Ayarlar → Command + Tab → Çok pencereli uygulamalarda önizlemelere geç** seçeneğini açabilirsiniz. Varsayılan kapalıdır. Birden fazla penceresi olan uygulamada sağ/sol oklarla önizlemeyi seçin, Enter ile açın veya Escape ile iptal edin. Command bırakıldığında çoklu pencere seçimi açık kalır. Command + Tab uygulamalar arasında dolaşmayı sürdürür. Bu seçenek DockTab seçicisini kullanır; penceresiz uygulamaları gizleme tercihi bağımsızdır.

0.16.4 ve sonrasında sağ/sol oklarla seçilen pencerenin büyük önizlemesi, seçicinin arkasında gerçek pencere konumunda gösterilir. Pencere Enter'a basılana kadar aktive edilmez. Enter, Escape veya uygulama değiştirme büyük önizlemeyi kapatır.

0.16.5 ve sonrasında seçili pencere kartının altında parlayan turkuaz neon çizgi görünür. Çizgi, sağ/sol oklarla veya fareyle seçilen kartı takip eder; açık ve koyu görünüme uyarlanır.

## Uygulama içinden güncelleme

0.16.2 ve sonrasında **Ayarlar → Güncellemeler → Güncellemeleri otomatik denetle** seçeneği varsayılan açıktır. DockTab çalışırken yaklaşık 24 saatte bir yeni sürüm kontrol edilir. Seçeneği kapatabilirsiniz; daha önce kapatılmış bir Sparkle tercihi varsa korunur. Yeni sürüm bulunduğunda haber verilir; indirme ve kurulum sizin onayınızla ilerler.

0.11.0 ve sonrasında menü çubuğundaki DockTab → **Güncellemeleri Denetle…** komutunu seçin. Yeni sürüm varsa güncelleme penceresindeki kurulum düğmesiyle indirin ve kurun. Uygulama yeniden başlatılır. macOS gerekirse yönetici onayı ister.

0.10.0 ve daha eski sürümlerde güncelleyici bulunmaz; ilk geçiş için yeni PKG’yi bir kez kurun. Sonraki sürümler uygulama içinden alınabilir.

Günlük kontrolün zamanlamasını Sparkle yönetir; otomatik indirme/kurulum ve uygulama telemetrisi kapalıdır. Ayarlardaki **Şimdi Denetle…** düğmesi ve menüdeki elle denetleme komutu, otomatik kontrol kapalıyken de kullanılabilir. Paketler HTTPS üzerinden indirilir ve Sparkle Ed25519 imzasıyla doğrulanır. GitHub hesabı gerekmez.

## İzinler ve dağıtım

Dock simgelerini/pencereleri bulmak için Erişilebilirlik, pencere görüntüleri için Ekran Kaydı izni gerekir. İzinler Ayarlar ekranından istenir. Önizleme görüntüleri cihaz dışına gönderilmez.

Bu paketler kalıcı yerel kod imzalama sertifikasıyla üretilir; Apple Developer ID ve notarization içermez. Diğer Mac’lerde macOS güvenlik onayı veya kurulum engeliyle karşılaşılabilir.

Bu repo yalnızca indirme paketleri ve güncelleme beslemesi içindir; uygulamanın kaynak kodu burada yayımlanmaz.
