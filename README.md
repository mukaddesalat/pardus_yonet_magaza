# Pardus Sınıf Yönetimi — Komut Mağazası (Topluluk Deposu)

Bu depo, **Lab Kaptanı (Pardus Sınıf Yönetimi)** uygulaması için öğretmenler tarafından hazırlanan hazır sınıf yönetim araçlarını ve bash betiklerini barındırır.

## 📦 Katalog Dosyası
Okullardaki Lab Kaptanı uygulaması, tüm depoyu klonlamadan doğrudan bu depodaki `katalog.json` dosyasını HTTP GET ile çeker.
URL: `https://raw.githubusercontent.com/mukaddesalat/pardus_yonet_magaza/main/katalog.json`

## 🧰 Hazır Araçlar Listesi (Katalog)
1. **Veyon Servisini Kontrol Et ve Başlat** (`veyon-servis-ac`)
2. **Yerel Alan Adı (Hosts) Dağıt** (`hosts-kayit-ekle`)
3. **Kullanıcı ve Ev Dizinini Sil** (`kullanici-ev-dizini-sil`)
4. **Disk ve RAM Sağlık Özeti** (`disk-bellek-raporu`)
5. **Kilitli ve Bozuk Paketleri Onar** (`bozuk-paket-onar`)
6. **Öğrenci Masaüstü ve İndirilenleri Temizle** (`ogrenci-masaustu-temizle`)
7. **Tarayıcı Önbellek ve Açık Oturumları Temizle** (`tarayici-sifirla`)
8. **Ağ ve Ağ Geçidi Bağlantı Testi** (`ag-baglanti-testi`)

## 🤝 Katkıda Bulunma Rehberi (Öğretmenler İçin)
1. Bu depoyu çatallayın (Fork) veya doğrudan bir dal (branch) açın.
2. `araclar/<arac-id>/` klasörü altına aracınızı ekleyin.
3. PR göndererek diğer öğretmenlerle paylaşın.
