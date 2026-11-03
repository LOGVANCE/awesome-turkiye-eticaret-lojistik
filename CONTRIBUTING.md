# Katkı Rehberi

Katkılarınızı bekliyoruz. Bu liste, Türkiye e-ticaret ve lojistik ekosistemindeki geliştiriciler ve operasyon ekipleri için tarafsız bir kaynak listesi olmayı amaçlar.

## Kabul kriterleri

- Bağlantı çalışıyor olmalı ve içerik, yazılan açıklamayla uyuşmalı.
- Kaynak Türkiye pazarına özgü olmalı ya da Türkçe olmalı. Genel araçlar (barkod, depo yönetimi gibi) Türkiye'deki kullanımı açıksa kabul edilir.
- Açık kaynak projelerde son 2 yıl içinde commit bulunmalı ve depo arşivlenmemiş olmalı.
- Resmi dokümanlar, kamu kaynakları ve bağımsız projeler tercih edilir.

## Kabul edilmeyenler

- Reklam, tanıtım yazısı, kampanya veya indirim sayfaları.
- Affiliate, referans kodu veya izleme parametresi içeren bağlantılar.
- Giriş yapmadan içeriği görülemeyen sayfalar.
- Bakımı bırakılmış veya yalnızca kopya içerik barındıran projeler.

## Madde formatı

```markdown
- [Kaynak Adı](https://ornek.com/) - Kısa ve tarafsız tek cümlelik açıklama
```

- Açıklama tek cümle ve en fazla 15 kelime olmalı.
- "En iyi", "lider", "ücretsiz deneyin" gibi pazarlama ifadeleri kullanılmamalı.
- Her bölümde maddeler alfabetik sıradadır (Türkçe alfabe). Yeni maddeyi doğru yere ekleyin.
- Aynı bağlantı listede yalnızca bir kez yer alabilir.

## Pull request nasıl açılır

1. Depoyu fork'layın ve yeni bir dal oluşturun.
2. `README.md` dosyasında ilgili bölüme maddeyi ekleyin. Uygun bölüm yoksa önerinizi PR açıklamasında belirtin.
3. Yerelde `npx awesome-lint` komutunu çalıştırıp hataları giderin.
4. Her PR'da yalnızca bir kaynak ekleyin veya tek bir konuyu düzeltin.
5. PR açıklamasında kaynağın neden listeye uygun olduğunu kısaca yazın.

Kırık bağlantılar haftalık olarak otomatik taranır. Kırık bir bağlantı görürseniz issue açabilir veya düzeltme PR'ı gönderebilirsiniz.
