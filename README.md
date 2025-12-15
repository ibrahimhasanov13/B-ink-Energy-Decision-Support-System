
# ⚡ B-ink Enerji - Karar Destek Sistemi (Decision Support System)

Bu proje, enerji sektörü verilerini analiz eden, kullanıcıya anlık piyasa takibi sunan ve elektrikli araç (EV) dönüşümünü destekleyen algoritmalar içeren **Ghost CMS** tabanlı bir web platformudur.

## 🚀 Proje Hakkında
Geleneksel statik web sitelerinin aksine; Node.js altyapısı üzerinde çalışan, **Code Injection** teknikleriyle özelleştirilmiş ve canlı API bağlantılarıyla beslenen dinamik bir sistem geliştirilmiştir.

Amacım; son kullanıcıların enerji maliyetlerini hesaplayabileceği ve piyasaları takip edebileceği interaktif bir araç sunmaktır.

## 🛠 Kullanılan Teknolojiler ve Yöntemler
* **CMS & Altyapı:** Ghost CMS, Node.js
* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Veri Görselleştirme:** Chart.js
* **API Entegrasyonları:**
    * **Frankfurter API:** Canlı Döviz Kurları (USD/TRY)
    * **TradingView Widgets:** Borsa ve Enerji Hisseleri Takibi
    * **wttr.in:** Bölgesel Hava Durumu ve GES Verimlilik Tahmini
* **DevOps & Test:** Ngrok (Tünelleme ve Mobil Testler)

## 🌟 Öne Çıkan Özellikler

### 1. Akıllı Algoritmalar
* **EV Şarj Hesaplayıcı:** Batarya kapasitesi (kWh) ve istasyon gücünü (kW) baz alarak, %10 enerji kaybı toleransıyla şarj süresini hesaplar.
* **Tasarruf Robotu:** Benzinli vs Elektrikli araç maliyetlerini karşılaştırarak yıllık tasarrufu analiz eder.
* **Karbon Ayak İzi:** Elektrik faturası üzerinden yıllık CO2 salınımını ve dikilmesi gereken ağaç sayısını hesaplar.

### 2. Gelişmiş Kullanıcı Deneyimi (UX)
* **Persistent Dark Mode:** Kullanıcının tema tercihi `localStorage` üzerinde tutulur, sayfa yenilense bile tercih hatırlanır.
* **KVKK/Çerez Yönetimi:** Kullanıcı onayı hafızaya alınır, onaylanmadan tekrar sormaz.
* **Mobil Entegrasyon:** Masaüstü kullanıcıları için mobil siteye hızlı geçiş sağlayan dinamik QR Kod modülü.

## 📂 Dosya Yapısı
Bu repository, Ghost CMS üzerine enjekte edilen özel kod bloklarını içerir:
* `Header_Kodlari.html`: TradingView borsa şeridi ve global CSS ayarları.
* `Footer_Kodlari.html`: Çerez yönetimi, Dark Mode, Chatbox ve QR modülleri.
* `Sayfa_Ici_Araclar.html`: Hesaplama araçları ve grafiklerin kaynak kodları.

---
*Geliştirici: Ibrahim Hasanov
*Lisans: MIT*
