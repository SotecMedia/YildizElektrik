# Yıldız Elektrik - 7/24 Acil Elektrikçi & EV Şarj Servisi Web Sitesi

Bu proje; İstanbul Avrupa Yakası'nda (özellikle **Büyükçekmece, Beylikdüzü, Hadımköy, Esenyurt, Avcılar, Silivri ve Arnavutköy**) faaliyet gösteren **Yıldız Elektrik** için tasarlanmış yüksek dönüşüm odaklı, mobil öncelikli (mobile-first), hızlı açılan (Lighthouse 95+ hedefli) ve Google Haritalar (Local SEO) performansını doğrudan maksimize eden tek sayfalık (Single Page / Landing Page) kurumsal web sitesidir.

---

## 🌟 Öne Çıkan Özellikler

1. **Yüksek Dönüşüm Mimarisi (Conversion Rate Optimization):**
   - **Masaüstü & Mobil Sticky Navigasyon:** Sürekli erişilebilir telefon ve WhatsApp butonları.
   - **Hero (Karşılama) Alanı:** 5.0 Google Puanı (19 Yorum) rozeti, acil durum puls animasyonu ve 2 büyük eylem butonu (*Hemen Ara* ve *WhatsApp'tan Konum / Fotoğraf Gönder*).
   - **Mobil Sabit Alt Bar (Sticky Bottom Bar):** Mobil cihazlarda başparmak erişim alanında sabit duran çift butonlu (`📞 Hemen Ara` & `💬 WhatsApp`) hızlı arama paneli.
   
2. **Yerel SEO (Local SEO) & Schema.org Yapılandırması:**
   - **Electrician / LocalBusiness JSON-LD:** Firma adı, 7/24 çalışma saatleri, 5.0 yıldız / 19 yorum derecelendirmesi, geo koordinatları ve 7 kritik hizmet bölgesi schema formatında kodlanmıştır.
   - **FAQPage JSON-LD:** Sıkça Sorulan Sorular bölümü Google zengin arama sonuçlarında (Rich Snippets) doğrudan görünecek şekilde yapılandırılmıştır.
   - **Hadımköy & Arnavutköy Sanayi Vurgusu:** Fabrika, depo ve atölyeler için yüksek akım, kompanzasyon pano takibi ve periyodik bakım anahtar kelimeleriyle güçlendirilmiştir.

3. **Performans ve Hız (Lighthouse 95+):**
   - Saf HTML5 + Tailwind CSS CDN + Vanilla JS mimarisi.
   - Harici ağır kütüphanelere (jQuery, Bootstrap vb.) sıfır bağımlılık.
   - Sıfır render-blocking SVG ikonlar.
   - DNS Preconnect ve optimize Google Fonts yüklemesi.

---

## 📁 Proje Dosya Yapısı

```text
YildizElektrik/
├── index.html        # Ana web sayfası (Tüm bölümler, schema, akordeon JS ve mobil menü)
├── favicon.svg       # Şimşek / enerji temalı vektörel site ikonu
├── robots.txt        # Arama motoru bot yönlendirmesi
├── sitemap.xml       # Google ve Yandex için XML site haritası
└── README.md         # Dokümantasyon ve yayınlama rehberi
```

---

## 🚀 Canlıya Alma (Deployment) Rehberi

Bu proje statik dosyalardan oluştuğu için herhangi bir sunucu veya sunucusuz (serverless) platformda anında çalışır.

### Seçenek 1: Netlify (En Hızlı & Ücretsiz SSL)
1. [netlify.com](https://www.netlify.com)'a giriş yapın.
2. `Add new site` > `Deploy manually` seçeneğine tıklayın.
3. Bu klasörü sürükleyip bırakın (drag & drop). Siteniz 10 saniyede yayında!
4. `Domain Settings` bölümünden `istanbulyildizelektrik.com` alan adınızı yönlendirin.

### Seçenek 2: Vercel
1. Vercel CLI yüklüyse: `vercel deploy --prod`
2. Veya [vercel.com](https://vercel.com) panosundan GitHub reposunu bağlayıp tek tıkla yayınlayın.

### Seçenek 3: Cloudflare Pages
1. Cloudflare kontrol paneline gidin > `Workers & Pages` > `Create Application` > `Pages`.
2. Projeyi bağlayın ve `Build command` alanını boş bırakarak deploy edin.

### Seçenek 4: cPanel / Standart Hosting (Linux / Apache / Nginx)
1. Hosting kontrol panelinizdeki (cPanel, Plesk vb.) **Dosya Yöneticisi**'ni açın.
2. `public_html` (veya `httpdocs`) dizinine girin.
3. Klasördeki `index.html`, `favicon.svg`, `robots.txt` ve `sitemap.xml` dosyalarını yükleyin.

---

## 📍 Google İşletme Profili (Google Business) & Harita Bağlantısı

- **İşletme Adı:** Yıldız Elektrik
- **Telefon:** 0545 779 3858
- **WhatsApp:** +90 545 779 3858
- **Web Sitesi:** https://istanbulyildizelektrik.com
- **Google Maps Linki:** https://maps.app.goo.gl/R7xzSGVeSPQrnWcY8

> **İpucu:** Google İşletme Profilinizdeki "Web Sitesi" bağlantısına `https://istanbulyildizelektrik.com` adresini eklediğinizde, web sitesindeki Local Schema ile Google Haritalar profiliniz senkronize olacak ve yerel aramalarda (Örn: *"Büyükçekmece acil elektrikçi"*, *"Hadımköy elektrikçi"*) sıralamanız hızla yükselecektir.
