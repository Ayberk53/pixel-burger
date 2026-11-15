# 🍔 Pixel Burger — Çok Sayfalı Restoran Web Uygulaması

**Pixel Burger**, kullanıcıların menüyü kategorilere göre filtreleyebildiği, dinamik bir sepet yönetimine sahip olduğu ve 3 aşamalı sipariş akışıyla adres bilgilerini girerek sipariş oluşturabildiği modern bir web uygulamasıdır.

🔗 **Canlı Demo:** [pixel-burger-six.vercel.app](https://pixel-burger-six.vercel.app)

## 🚀 Öne Çıkan Özellikler
* **Çok Sayfalı Mimari (SPA):** `React Router` ile sayfa yenilenmeden **Ana Sayfa**, **Yemekler**, **Hakkımızda** ve **Sipariş** sayfaları arasında kesintisiz geçiş.
* **Dinamik Kategori Filtreleme:** Menüler, Tekli Burger ve İçecekler kategorileri arasında anlık filtreleme.
* **Kalıcı Sepet Yönetimi (`localStorage`):** Sayfa yenilense dahi tarayıcı hafızasında korunan sepet verisi, dinamik ürün adedi (`+` / `-`) ve toplam tutar hesaplaması.
* **3 Aşamalı Sipariş Akışı:** Sepet özeti, teslimat/iletişim bilgileri formu ve sipariş onay ekranından oluşan adım adım kullanıcı deneyimi.
* **İnteraktif Arayüz:** Otomatik ve manuel kontrollü görsel slayt (Cross-fade & Zoom) ve sepete ürün eklendiğinde tetiklenen anlık bildirim (Toast) sistemi.

## 🛠️ Kullanılan Teknolojiler
* **Frontend:** React.js (Vite)
* **Yönlendirme (Routing):** React Router DOM
* **İkon Seti:** Lucide React
* **Stil:** Modern CSS3 (Grid, Flexbox, CSS Animations)
* **Deployment:** Vercel

## 💻 Kurulum ve Çalıştırma
```bash
git clone [https://github.com/Ayberk53/pixel-burger.git](https://github.com/Ayberk53/pixel-burger.git)
cd pixel-burger
npm install
npm run dev
