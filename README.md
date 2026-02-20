# 📱 Hepsiburada Mobil Otomasyon Projesi (Maestro)

Bu proje, Hepsiburada Android uygulaması üzerinde temel kullanıcı senaryolarını test etmek amacıyla **Maestro** kullanılarak hazırlanmıştır.

## 🚀 Proje Hakkında
Bu otomasyon çalışması, uygulamanın ana akışlarını (Arama, Filtreleme, Sepete Ekleme) kapsayan uçtan uca (E2E) bir test senaryosudur.

## 🛠️ Test Edilen Senaryolar
* **Arama:** Uygulama içinde ürün araması yapılması.
* **Filtreleme:** Beden (42), Fiyat Aralığı (3000-5000 TL), Renk (Beyaz) ve Cinsiyet (Erkek) filtrelerinin uygulanması.
* **Doğrulama:** Filtrelerin doğru şekilde uygulandığının ve sonuç sayısının güncellendiğinin kontrolü.
* **Sepet İşlemleri:** Seçilen ürünün sepete eklenmesi ve sepet içeriğinin doğrulanması.

## 🔧 Kullanılan Teknolojiler
* **Maestro:** Mobil UI Otomasyon aracı.
* **YAML:** Test akışlarının tanımı.

## 🏃 Testi Çalıştırma
Maestro yüklü bir sistemde aşağıdaki komut ile testi başlatabilirsiniz:

```bash
maestro test hepsiburada.yaml
