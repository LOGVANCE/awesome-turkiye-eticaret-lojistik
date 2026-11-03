# Awesome Türkiye E-Ticaret ve Lojistik [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Türkiye e-ticaret ve lojistik ekosistemi için seçilmiş kaynaklar: pazaryeri ve kargo API'leri, fulfillment ve depo yönetimi araçları, e-fatura, mevzuat ve açık kaynak projeler.

## İçindekiler

- [Pazaryeri API'leri ve geliştirici dokümanları](#pazaryeri-apileri-ve-geliştirici-dokümanları)
- [Pazaryeri açık kaynak istemci kütüphaneleri](#pazaryeri-açık-kaynak-istemci-kütüphaneleri)
- [Kargo firmaları: API ve takip](#kargo-firmaları-api-ve-takip)
- [Kargo entegratörleri ve kütüphaneler](#kargo-entegratörleri-ve-kütüphaneler)
- [E-ticaret altyapıları](#e-ticaret-altyapıları)
- [Fulfillment ve depo yönetimi](#fulfillment-ve-depo-yönetimi)
  - [Desi ve kargo ücreti](#desi-ve-kargo-ücreti)
  - [Barkod ve etiket](#barkod-ve-etiket)
  - [Açık kaynak depo yönetim sistemleri](#açık-kaynak-depo-yönetim-sistemleri)
- [E-fatura, e-arşiv ve e-irsaliye](#e-fatura-e-arşiv-ve-e-irsaliye)
  - [Resmi kaynaklar](#resmi-kaynaklar)
  - [E-dönüşüm hizmet sağlayıcıları](#e-dönüşüm-hizmet-sağlayıcıları)
  - [Açık kaynak e-belge araçları](#açık-kaynak-e-belge-araçları)
- [Ödeme sistemleri](#ödeme-sistemleri)
  - [Geliştirici dokümanları](#geliştirici-dokümanları)
  - [SDK ve kütüphaneler](#sdk-ve-kütüphaneler)
- [Gümrük ve dış ticaret](#gümrük-ve-dış-ticaret)
- [Mevzuat ve kurumlar](#mevzuat-ve-kurumlar)
  - [Mevzuat](#mevzuat)
  - [Kurumlar ve kamu sistemleri](#kurumlar-ve-kamu-sistemleri)
- [Veri ve raporlar](#veri-ve-raporlar)
- [Sözlük ve eğitim](#sözlük-ve-eğitim)
- [Topluluklar ve bültenler](#topluluklar-ve-bültenler)

## Pazaryeri API'leri ve geliştirici dokümanları

- [Amazon Selling Partner API](https://developer-docs.amazon.com/sp-api/) - Amazon Türkiye dahil tüm Amazon mağazaları için satıcı API referansı ve rehberleri
- [Hepsiburada API Portal](https://developers.hepsiburada.com/) - Hepsiburada pazaryeri entegrasyonu için resmi API dokümantasyon portalı
- [İdefix API](https://developer.idefix.com/api) - İdefix satıcıları için ürün ve sipariş servislerinin resmi dokümanı
- [Trendyol Entegrasyon Dokümantasyonu](https://developers.trendyol.com/) - Trendyol pazaryeri satıcı entegrasyonu için resmi API dokümantasyonu

## Pazaryeri açık kaynak istemci kütüphaneleri

- [isarud-woocommerce](https://github.com/durasi/isarud-woocommerce) - Trendyol, Hepsiburada, n11, Pazarama ve Amazon için WooCommerce yönetim eklentisi
- [n11-sp-api](https://github.com/wiensa/n11-sp-api) - n11 Seller Partner API için Laravel paketi
- [n8n-trendyol](https://github.com/actuallyzefe/n8n-trendyol) - Trendyol API ile sipariş ve ürün otomasyonu için n8n topluluk düğümü
- [nodejs-turkiye-pazaryeri](https://github.com/ygulgec/nodejs-turkiye-pazaryeri) - Trendyol, Hepsiburada ve n11 satıcı API'leri için Node.js entegrasyonları
- [pazarama-sp-api](https://github.com/wiensa/pazarama-sp-api) - Pazarama satıcı paneli API'si için Laravel paketi
- [pttavm-sp-api](https://github.com/wiensa/pttavm-sp-api) - PttAVM pazaryeri API'si için Laravel paketi
- [trendyol-api-java](https://github.com/mustafa-m-ugur/trendyol-api-java) - Trendyol pazaryeri API'si için Java istemcisi
- [trendyol-php](https://github.com/Hasokeyk/trendyol-php) - Trendyol pazaryeri API'si için PHP kütüphanesi
- [TrendyolClient.Sharp](https://github.com/bberka/TrendyolClient.Sharp) - Refit tabanlı .NET Trendyol API istemcisi

## Kargo firmaları: API ve takip

- [Aras Kargo Entegrasyon Hizmetleri](https://www.araskargo.com.tr/kurumsal-cozumlerimiz/entegrasyon-hizmetlerimiz) - B2B, B2C ve C2C gönderiler için Aras Kargo entegrasyon seçenekleri
- [DHL API Developer Portal](https://developer.dhl.com/) - DHL Group birimlerinin gönderi ve takip API'lerini sunan geliştirici portalı
- [DHL eCommerce Apizone](https://apizone.mngkargo.com.tr/) - DHL eCommerce Türkiye (eski MNG Kargo) API ürünleri ve geliştirici portalı
- [FedEx Developer Portal](https://developer.fedex.com/api/tr-tr/home.html) - FedEx gönderi ve takip API'leri için geliştirici portalının Türkiye sayfası
- [HepsiJET](https://www.hepsijet.com/) - Hepsiburada grubuna ait kargo şirketinin kurumsal sitesi
- [Kolay Gelsin](https://www.kolaygelsin.com/) - Kolay Gelsin kargo şirketinin kurumsal sitesi ve hizmet bilgileri
- [Sürat eKargo](https://ekargo.suratkargo.com.tr/) - Sürat Kargo'nun çevrim içi sanal şubesi
- [Trendyol Express](https://trendyolexpress.com/) - Trendyol grubuna ait kargo şirketinin kurumsal sitesi
- [UPS Developer Portal](https://developer.ups.com/) - UPS gönderi, takip ve fiyat API'leri ile API durum bilgisi
- [Yurtiçi Kargo E-Ticaret Gönderi Sorgulama](https://www.yurticikargo.com/tr/online-servisler/e-ticaret-gonderi-sorgulama) - Yurtiçi Kargo'nun e-ticaret gönderileri için takip ekranı

## Kargo entegratörleri ve kütüphaneler

- [Basit Kargo](https://www.basitkargo.com/) - Birden çok kargo firmasıyla ayrı anlaşma yapmadan gönderim sağlayan platform
- [DHL-Cargo-ERPNext](https://github.com/logedosoft/DHL-Cargo-ERPNext) - DHL eCommerce (MNG Kargo) REST API için ERPNext entegrasyonu
- [Geliver API](https://docs.geliver.io/) - Kargo fiyat teklifi, etiket satın alma ve gönderi takibi için API dokümanı
- [Kargo Entegratör](https://kargoentegrator.com/) - E-ticaret ve pazaryeri siparişleri için çoklu kargo entegrasyon paneli
- [Kargonomi](https://www.kargonomi.com.tr/) - Farklı kargo firmalarıyla tek hesaptan gönderim yapılan platform
- [ShipEntegra](https://www.shipentegra.com/) - E-ihracat siparişleri için lojistik ve sipariş yönetim yazılımı
- [woocommerce-aras-kargo](https://github.com/psaux-it/woocommerce-aras-kargo) - WooCommerce ile Aras Kargo arasında sunucu taraflı Bash entegrasyonu
- [yurt-ici-kargo-php](https://github.com/Hasokeyk/yurt-ici-kargo-php) - Yurtiçi Kargo web servisleri için PHP entegrasyon kütüphanesi

## E-ticaret altyapıları

- [Akinon Dokümantasyonu](https://docs.akinon.com/) - Akinon ticaret platformunun geliştirici ve ürün dokümanları
- [IdeaSoft API](https://apidoc.ideasoft.dev/) - IdeaSoft e-ticaret altyapısının API referansı
- [ikas Developer Portal](https://ikas.dev/) - ikas mağazaları için API, tema ve uygulama geliştirme dokümanları
- [Shopify Dev Docs](https://shopify.dev/) - Shopify uygulama, tema ve mağaza API'leri için resmi dokümanlar
- [Ticimax Custom Servis Dokümanı](https://static.ticimax.com/dokumanlar/CustomServis.pdf) - Ticimax SOAP web servis metotlarını parametre tablolarıyla anlatan PDF
- [WooCommerce REST API](https://woocommerce.github.io/woocommerce-rest-api-docs/) - WooCommerce mağazaları için REST API referansı

## Fulfillment ve depo yönetimi

### Desi ve kargo ücreti

- [Aras Kargo Ücret Hesaplama](https://www.araskargo.com.tr/kargo-ucreti-hesaplama) - Aras Kargo gönderileri için ücret hesaplama ekranı
- [Logvance Desi Hesaplama](https://logvance.com/desi-hesaplama/) - Koli ölçülerinden desi ve ücrete esas ağırlığı hesaplayan araç
- [Sürat Kargo Fiyat Hesaplama](https://suratkargo.com.tr/BilgiHizmetleri/GonderiStandartlarimiz/FiyatHesaplama) - Sürat Kargo gönderileri için fiyat hesaplama ekranı
- [Yurtiçi Kargo Fiyat Nasıl Hesaplanıyor](https://www.yurticikargo.com/tr/gonderi-rehberleri/fiyat-nasil-hesaplaniyor) - Desi ile gerçek ağırlık karşılaştırmasına dayalı ücretlendirmeyi anlatan rehber

### Barkod ve etiket

- [bwip-js](https://github.com/metafloor/bwip-js) - Saf JavaScript ile çok sayıda barkod türü üreten kütüphane
- [JsBarcode](https://github.com/lindell/JsBarcode) - Tarayıcıda ve Node.js'te çalışan JavaScript barkod üretim kütüphanesi
- [Labelary ZPL Viewer](https://labelary.com/viewer.html) - ZPL etiketlerini çevrim içi düzenleme ve önizleme aracı
- [Zint](https://github.com/zint/zint) - Code 128, EAN-128 ve QR dahil 50'den fazla simgeyi destekleyen barkod kütüphanesi

### Açık kaynak depo yönetim sistemleri

- [GreaterWMS](https://github.com/GreaterWMS/GreaterWMS) - Satış sonrası lojistik depolama süreçlerinden doğan açık kaynak envanter yönetim sistemi
- [InvenTree](https://github.com/inventree/InvenTree) - Parça ve stok takibi için açık kaynak envanter yönetim sistemi
- [ModernWMS](https://github.com/fjykTec/ModernWMS) - Basit ve eksiksiz olmayı hedefleyen açık kaynak depo yönetim sistemi
- [OpenBoxes](https://github.com/openboxes/openboxes) - Sağlık kurumları için stok hareketlerini izleyen depo yönetim sistemi
- [OpenWMS](https://github.com/openwms/org.openwms) - Açık kaynak depo yönetim sistemi projesi

## E-fatura, e-arşiv ve e-irsaliye

### Resmi kaynaklar

- [e-Arşiv Portal](https://earsivportal.efatura.gov.tr/) - GİB'in e-Arşiv fatura düzenleme portalı
- [e-Fatura Mevzuat ve Teknik Kılavuzlar](https://ebelge.gib.gov.tr/efaturamevzuat.html) - VUK tebliğleri, UBL-TR 1.2.1 kılavuzları ve paket dosyaları
- [e-İrsaliye Mevzuat ve Teknik Kılavuzlar](https://ebelge.gib.gov.tr/eirsaliyemevzuat.html) - e-İrsaliye tebliğleri, uygulama kılavuzu ve UBL-TR kılavuzları
- [eBelge](https://ebelge.gib.gov.tr/) - GİB'in e-Fatura, e-Arşiv ve e-İrsaliye uygulamaları bilgi sitesi
- [Özel Entegratörler Listesi](https://ebelge.gib.gov.tr/efaturaozelentegratorlerlistesi.html) - GİB'den özel entegrasyon izni almış firmaların listesi

### E-dönüşüm hizmet sağlayıcıları

- [EDM](https://www.edmbilisim.com.tr/) - e-Fatura, e-Arşiv, e-Defter ve KEP hizmetleri sunan e-dönüşüm firması
- [İZİBİZ](https://izibiz.com.tr/) - e-Fatura, e-Defter ve ön muhasebe hizmetleri sunan e-dönüşüm firması
- [Paraşüt DevHub](https://devhub.parasut.com/) - Paraşüt ön muhasebe API'si için geliştirici portalı
- [QNB eSolutions](https://www.qnbesolutions.com.tr/) - e-Fatura ve diğer e-belge ürünleri sunan e-dönüşüm firması
- [Uyumsoft](https://www.uyumsoft.com/) - ERP ve e-dönüşüm yazılımları geliştiren yazılım firması

### Açık kaynak e-belge araçları

- [e_donusum](https://github.com/Odoo-Turkey-Community/e_donusum) - Odoo için e-Fatura, e-İrsaliye, e-Defter ve e-Banka modülleri
- [eArsivPortal](https://github.com/keyiflerolsun/eArsivPortal) - GİB e-Arşiv Portal üzerinden fatura oluşturan Python kütüphanesi
- [efatura](https://github.com/furkankadioglu/efatura) - e-Arşiv üzerinden fatura oluşturan PHP kütüphanesi
- [efatura-kontrol](https://github.com/BerkantACUN/efatura-kontrol) - UBL-TR belgelerini GİB XSD ve şematron kurallarıyla yerelde doğrulayan araç
- [f/fatura](https://github.com/f/fatura) - e-Arşiv portalı üzerinden fatura oluşturan TypeScript kütüphanesi
- [mlevent/fatura](https://github.com/mlevent/fatura) - e-Arşiv Portal için e-Fatura, e-SMM ve e-Müstahsil oluşturan PHP kütüphanesi
- [UblTr](https://github.com/hkutluay/UblTr) - .NET için UBL-TR 1.2.1 (UBL 2.1) sınıf kütüphanesi

## Ödeme sistemleri

### Geliştirici dokümanları

- [iyzico Geliştirici Dokümanı](https://docs.iyzico.com/) - iyzico ödeme formu, API ve ödeme yöntemleri için resmi doküman
- [Moka United Developer Portal](https://developer.mokaunited.com/) - Moka United ödeme entegrasyonu için doküman ve destek portalı
- [Param Geliştirici](https://dev.param.com.tr/) - ParamPOS ödeme, ön provizyon, kart saklama ve iade servislerinin dokümanı
- [PayTR Geliştirici Merkezi](https://dev.paytr.com/) - PayTR sanal POS ve ödeme çözümlerinin entegrasyon dokümanları

### SDK ve kütüphaneler

- [anadolupay-node](https://github.com/Voxyfy/anadolupay-node) - Türk banka ve ödeme sağlayıcıları için tek arayüzlü Node.js ödeme kütüphanesi
- [better-payment](https://github.com/czaydev/better-payment) - iyzico, PayTR, Parampos, Sipay ve banka POS'ları için TypeScript ödeme arayüzü
- [craftgate-php-client](https://github.com/craftgate/craftgate-php-client) - Craftgate ödeme API'si için resmi PHP istemcisi
- [iyzipay-node](https://github.com/iyzico/iyzipay-node) - iyzico API'si için resmi Node.js istemcisi
- [iyzipay-php](https://github.com/iyzico/iyzipay-php) - iyzico API'si için resmi PHP istemcisi
- [iyzipay-python](https://github.com/iyzico/iyzipay-python) - iyzico API'si için resmi Python istemcisi
- [iyzipay-woocommerce](https://github.com/iyzico/iyzipay-woocommerce) - iyzico ödeme altyapısı için WooCommerce eklentisi

## Gümrük ve dış ticaret

- [4458 Sayılı Gümrük Kanunu](https://www.mevzuat.gov.tr/MevzuatMetin/1.5.4458.pdf) - Gümrük işlemlerini düzenleyen temel kanunun metni
- [Beyanname Sorgulama](https://uygulama.gtb.gov.tr/BeyannameSorgulama/) - Gümrük beyannamesinin durumunu sorgulama ekranı
- [Dijital Gümrük Uygulamaları](https://ticaret.gov.tr/gumruk-islemleri/dijital-gumruk-uygulamalari) - NCTS, Tek Pencere ve EDI/XML mesajları gibi gümrük sistemlerinin listesi
- [İhracat](https://ticaret.gov.tr/ihracat) - Ticaret Bakanlığı ihracat ve e-ihracat destekleri, mevzuat ve pazar raporları
- [Mikro İhracat BGB Duyurusu](https://ticaret.gov.tr/haberler/ticaret-bakanligindan-mikro-ihracat-yapmak-isteyenlere-kolaylastirici-adim) - İlk kez mikro ihracat yapanlar için BGB sürecindeki kolaylık (2024)
- [Tarife Arama Motoru](https://uygulama.gtb.gov.tr/Tara) - Ürün adı veya GTİP koduyla gümrük tarife pozisyonu arama aracı
- [TİM](https://tim.org.tr/tr/) - İhracatçı birliklerini bir araya getiren Türkiye İhracatçılar Meclisi
- [Türk Eximbank](https://www.eximbank.gov.tr/) - İhracat finansmanı sağlayan kamu bankası

## Mevzuat ve kurumlar

### Mevzuat

- [6475 Sayılı Posta Hizmetleri Kanunu](https://www.mevzuat.gov.tr/MevzuatMetin/1.5.6475.pdf) - Kargo ve posta hizmeti sağlayıcılarının yetkilendirilmesini düzenleyen kanun
- [6502 Sayılı Tüketicinin Korunması Hakkında Kanun](https://www.mevzuat.gov.tr/MevzuatMetin/1.5.6502.pdf) - Mesafeli satış ve cayma hakkı hükümlerinin dayandığı kanun
- [6563 Sayılı Elektronik Ticaretin Düzenlenmesi Hakkında Kanun](https://www.mevzuat.gov.tr/MevzuatMetin/1.5.6563.pdf) - E-ticaret, ticari elektronik ileti ve aracı hizmet sağlayıcı yükümlülükleri
- [6698 Sayılı Kişisel Verilerin Korunması Kanunu](https://www.mevzuat.gov.tr/MevzuatMetin/1.5.6698.pdf) - Kişisel verilerin işlenmesine ilişkin temel kanun
- [Elektronik Ticaret Aracı Hizmet Sağlayıcı Yönetmeliği](https://www.resmigazete.gov.tr/eskiler/2022/12/20221229-5.htm) - Pazaryerleri ve e-ticaret hizmet sağlayıcılarına ilişkin 2022 tarihli yönetmelik
- [Elektronik Ticarette Güven Damgası Hakkında Tebliğ](https://www.mevzuat.gov.tr/mevzuat?MevzuatNo=23634&MevzuatTur=9&MevzuatTertip=5) - E-ticaret siteleri için güven damgası şartlarını belirleyen tebliğ
- [Mesafeli Sözleşmeler Yönetmeliği](https://www.mevzuat.gov.tr/mevzuat?MevzuatNo=20237&MevzuatTur=7&MevzuatTertip=5) - Ön bilgilendirme, cayma hakkı ve teslimat yükümlülüklerini düzenleyen yönetmelik

### Kurumlar ve kamu sistemleri

- [BTK](https://www.btk.gov.tr/) - Posta ve kargo sektörünü de düzenleyen Bilgi Teknolojileri ve İletişim Kurumu
- [ETBİS](https://etbis.ticaret.gov.tr/) - E-ticaret yapan işletmelerin kayıt olduğu Elektronik Ticaret Bilgi Sistemi
- [İYS](https://iys.org.tr/) - Ticari elektronik ileti izinlerinin yönetildiği İleti Yönetim Sistemi
- [KVKK](https://www.kvkk.gov.tr/) - Kişisel Verileri Koruma Kurumu kararları ve rehberleri
- [Rekabet Kurumu](https://www.rekabet.gov.tr/) - Rekabet Kurulu kararları ve sektör incelemeleri
- [Tüketicinin Korunması ve Piyasa Gözetimi Genel Müdürlüğü](https://tuketici.ticaret.gov.tr/) - Ticaret Bakanlığı'nın tüketici mevzuatı ve başvuru bilgileri

## Veri ve raporlar

- [E-Ticaret Lojistiğinde Sorunlar ve Politika Önerileri](https://www.pwc.com.tr/tr/Hizmetlerimiz/yonetim-danismanligi/tedarik-zinciri/yayinlar/assets/e-ticaret-lojistiginde-sorunlar-ve-politika-onerileri-v2.pdf) - TÜSİAD için hazırlanan e-ticaret lojistiği sorunları ve politika önerileri raporu
- [E-Ticaretin Gelişimi, Sınırların Aşılması ve Yeni Normlar](https://www.deloitte.com/content/dam/assets-zone2/tr/tr/docs/industries/consumer/2024/e-ticaretin-gelisimi-sinirlarin-asilmasi-ve-yeni-normlar.pdf) - TÜSİAD ve Deloitte Digital'in Türkiye e-ticaret pazarı raporu
- [iyzico E-Commerce Report 2025](https://www.iyzico.com/assets/uploads/pdf/iyzico_ecommerce_report_2025.pdf) - iyzico'nun Türkiye e-ticaret eğilimleri raporu
- [Türkiye'de E-Ticaretin Görünümü Raporları](https://etbis.ticaret.gov.tr/tr/Post/postturkiyede-e-ticaretin-gorunumu-raporlari) - Ticaret Bakanlığı'nın yıllık e-ticaret raporları (2023-2025)

## Sözlük ve eğitim

- [Amazon Seller University](https://sellercentral.amazon.com.tr/learn) - Amazon Türkiye satıcıları için Türkçe eğitim içerikleri
- [e-Fatura, e-Arşiv ve e-İrsaliye Rehberi](https://github.com/alestaweb/efatura-earsiv-eirsaliye-rehberi) - E-belge süreçlerinin yazılım tarafını anlatan açık kaynak rehber
- [ETBİS E-Ticaret Akademisi](https://etbis.ticaret.gov.tr/tr/ETicaretAkademisi) - Ticaret Bakanlığı'nın e-ticaret ve e-ihracat eğitim içerikleri
- [Logvance Lojistik Sözlüğü](https://logvance.com/lojistik-sozlugu/) - Depo, stok, sipariş ve dış ticaret terimlerinin Türkçe açıklamaları
- [Trendyol Akademi](https://akademi.trendyol.com/) - Trendyol satıcıları için çevrim içi eğitim ve etkinlik platformu

## Topluluklar ve bültenler

- [ETİD](https://etid.org.tr/) - Elektronik Ticaret İşletmecileri Derneği
- [LODER](https://www.loder.org.tr/) - Lojistik Derneği
- [Lojistik Hattı](https://www.lojistikhatti.com/) - Lojistik sektörü haberleri ve UTA Lojistik dergisi
- [Türk API'leri](https://github.com/3rt4nm4n/turkish-apis) - Türkiye'ye ait API'lerin topluluk tarafından derlenen listesi
- [UND](https://www.und.org.tr/) - Uluslararası Nakliyeciler Derneği
- [UTİKAD](https://www.utikad.org.tr/) - Uluslararası Taşımacılık ve Lojistik Hizmet Üretenleri Derneği
- [Webrazzi E-Ticaret](https://webrazzi.com/etiket/e-ticaret/) - Türkiye e-ticaret girişimleri ve yatırımlarıyla ilgili haberler
