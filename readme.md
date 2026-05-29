# 🛒 MarketSepeti Frontend

Modern, mobil uyumlu ve kullanıcı dostu arayüze sahip e-ticaret frontend uygulaması.

Bu proje HTML, CSS, JavaScript ve Bootstrap kullanılarak geliştirilmiştir.

Frontend uygulaması Laravel tabanlı RESTful API ile haberleşerek kullanıcı, ürün, sepet, sipariş ve profil işlemlerini gerçekleştirmektedir.

---

# 📌 Proje Hakkında

MarketSepeti Frontend, kullanıcıların ürünleri görüntüleyebildiği, favorilere ekleyebildiği, sepete ürün ekleyebildiği, sipariş oluşturabildiği ve hesap işlemlerini yönetebildiği web tabanlı arayüz uygulamasıdır.

Proje responsive tasarım prensiplerine uygun olarak geliştirilmiş olup masaüstü, tablet ve mobil cihazlarda kullanılabilmektedir.

---

# 🚀 Sistem Özellikleri

## 👤 Kullanıcı İşlemleri

* Kullanıcı kayıt olma
* Kullanıcı giriş yapma
* Profil bilgilerini görüntüleme
* Profil güncelleme
* Adres yönetimi

---

## 🛍 Ürün İşlemleri

* Ürün listeleme
* Ürün detay görüntüleme
* Kategori filtreleme
* Marka filtreleme
* Ürün arama
* Ürün görsellerini görüntüleme

---

## ❤️ Favori Sistemi

* Favorilere ürün ekleme
* Favorilerden ürün kaldırma
* Favori ürünleri listeleme

---

## 🛒 Sepet Sistemi

* Sepete ürün ekleme
* Ürün miktarı güncelleme
* Sepetten ürün kaldırma
* Toplam tutar hesaplama

---

## 📦 Sipariş Sistemi

* Sipariş oluşturma
* Sipariş geçmişi görüntüleme
* Sipariş detay görüntüleme
* Sipariş durumlarını takip etme

---

## 💳 Cüzdan Sistemi

* Bakiye görüntüleme
* İşlem geçmişi görüntüleme

---

## 👨‍💼 Yönetim Paneli

* Dashboard
* Ürün Yönetimi
* Sipariş Yönetimi
* Banner Yönetimi
* Kullanıcı Yönetimi
* Kategori ve Marka Yönetimi

---

# 🛠 Kullanılan Teknolojiler

## Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap
* jQuery

---

## Backend API

* PHP
* Laravel
* PostgreSQL
* JWT Authentication
* RESTful API

---

# 🔗 Backend API Repository

Bu frontend uygulaması aşağıdaki Laravel API servisini kullanmaktadır:

https://github.com/icanKuleli61/MarketSepeti-api

---

# 🏗 Yazılım Mimarisi

Frontend katmanında hazır arayüz şablonları (template) kullanılmış ve proje ihtiyaçlarına göre özelleştirilmiştir.

Kullanıcı işlemleri, ürün yönetimi, sipariş süreçleri ve diğer tüm veri işlemleri Laravel API üzerinden gerçekleştirilmektedir.

Frontend ve Backend katmanları REST API aracılığıyla haberleşmektedir.

---

# 📂 Proje Yapısı

```text
admin/
components/
css/
docs/
fonts/
img/
js/
sass/
screenshots/

index.html
shop.html
product-detail.html
cart.html
favorites.html
profile.html
orders.html
checkout.html
contact.html
about.html
```

---

# 📊 ER Diagram

![ER Diagram](docs/er-diagram.png)

### PDF Versiyonu

[ER Diagram PDF](docs/er-diagram.pdf)

---

# 🔄 Sistem Akış Diyagramı

![Akış Diyagramı](docs/akis-diyagrami.png)

### PDF Versiyonu

[Akış Diyagramı PDF](docs/akis-diyagrami.pdf)

---

# 📸 Sistem Görselleri

## Ana Sayfa Banner

![Ana Sayfa](screenshots/home-banner.png)

---

## Öne Çıkan Ürünler

![Öne Çıkan Ürünler](screenshots/featured-products.png)

---

## Ürün Listeleme Sayfası

![Ürünler](screenshots/products-page.png)

---

## Ürün Detay Sayfası

![Ürün Detay](screenshots/product-detail.png)

---

## Favoriler

![Favoriler](screenshots/favorites.png)

---

## Sepet

![Sepet](screenshots/cart.png)

---

## Sipariş Oluşturma

![Checkout](screenshots/checkout-page.png)

---

## Kullanıcı Profil Sayfası

![Profil](screenshots/profile-page.png)

---

## Sipariş Geçmişi

![Siparişlerim](screenshots/my-orders.png)

---

## Adres Yönetimi

![Adresler](screenshots/addresses-page.png)

---

## Cüzdan Sistemi

![Cüzdan](screenshots/wallet-page.png)

---

## Hakkımızda Sayfası

![Hakkımızda](screenshots/about-page.png)

---

## İletişim Sayfası

![İletişim](screenshots/contact-page.png)

---

# 👨‍💼 Admin Panel

## Dashboard

![Dashboard](screenshots/admin-dashboard.png)

---

## Ürün Yönetimi

![Ürün Yönetimi](screenshots/admin-products.png)

---

## Ürün Ekleme

![Ürün Ekle](screenshots/admin-add-product.png)

---

## Kategori ve Marka Yönetimi

![Özellik Yönetimi](screenshots/admin-features.png)

---

## Sipariş Yönetimi

![Sipariş Yönetimi](screenshots/admin-orders.png)

---

## Banner Yönetimi

![Banner Yönetimi](screenshots/admin-banners.png)

---

## Kullanıcı Yönetimi

![Kullanıcı Yönetimi](screenshots/admin-users.png)

---

# 📌 Not

Bu proje Veritabanı Yönetim Sistemleri dersi kapsamında geliştirilmiştir.

Frontend tarafında hazır arayüz şablonları kullanılmış ve proje ihtiyaçlarına göre özelleştirilmiştir.

Tüm veri işlemleri Laravel tabanlı RESTful API üzerinden gerçekleştirilmektedir.
