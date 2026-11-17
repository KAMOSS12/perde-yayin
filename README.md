# Perde — yayın

**Perde**, Windows için hafif, canlı masaüstü arka planları uygulamasıdır. Bu depo yalnızca **yayın** içindir: kurulum dosyaları ve topluluk galerisi. Uygulamanın kaynak kodu burada değildir.

## İndir

[Son sürüm → Releases](https://github.com/KAMOSS12/perde-yayin/releases/latest) — `PerdeKurulum.exe` dosyasını indirip çift tıkla. Yönetici izni gerekmez, kurulum bir dakikadan kısa sürer.

> Kurulum dosyası şimdilik imzasızdır; Windows "tanınmayan uygulama" uyarısı gösterebilir (**Ek bilgi → Yine de çalıştır**).

Perde'de **Ayarlar → Başlangıç → Güncellemeleri denetle** yalnızca sen basınca bu sayfaya bir kez bakar; kendiliğinden hiçbir şey indirmez.

## Perde Galerisi

`galeri/` klasöründeki küçük `.perde` paketleri, Perde'de **Keşfet → Perde Galerisi** ile görünür ve tek tıkla kütüphaneye eklenir. Her paket birkaç KB'tır: sahnenin kendisi ve ayarları.

- `galeri/index.json` — liste (ad, açıklama, yazar, dosya, küçük resim, boyut, SHA-256 özeti)
- `galeri/paketler/<kimlik>.perde` — paketler
- `galeri/kucuk/<kimlik>.jpg` — küçük resimler (480 px)

Perde yalnızca bu depodaki `galeri/` yollarını kabul eder ve indirilen paketin özetini `index.json` ile karşılaştırır; eşleşmeyen paket açılmaz.

### Paket eklemek

Perde'de bir arka planı seçip **Paylaş** ile `.perde` olarak kaydet; dosyayı, küçük resmini ve `index.json` girdisini ekleyen bir çekme isteği (pull request) aç.

---

# Perde — releases (English)

Light, living desktop wallpapers for Windows. This repository only hosts **releases** (installer) and the **community gallery**; the app's source code is not here. Download `PerdeKurulum.exe` from [Releases](https://github.com/KAMOSS12/perde-yayin/releases/latest). In the app, **Discover → Perde Gallery** lists the packages in `galeri/`.
